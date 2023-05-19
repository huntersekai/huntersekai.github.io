---
layout: page
title: Manga
epsname: Kumpulan Manga Garapan A-1 Fansub
---

<section class="posts">
<h2 style="margin-top: 0"><a class="white pinkhover" href="{{ site.baseurl }}{{ site.tags['manga'][0].url }}" style="text-decoration: none;">{{ site.tags['manga'][0].title }}</h2>
<a href="{{ site.baseurl }}{{ site.tags['manga'][0].url }}"><p style="margin: .5rem 0;"><img src="{{ site.tags['manga'][0].coverPhoto }}"></p></a>
<hr><br>
<ul>
{% for post in site.tags['manga'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y.%m.%d" }}</time></li>
{% endfor %}
</ul>
</section>