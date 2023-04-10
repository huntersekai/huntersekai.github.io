---
layout: category
title: Tonikaku Kawaii
epsname: Pokoknya Imut
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1094990997127184434/mpv-shot0239.jpg
---

Musim Kedua [Tonikaku Kawaii]({{ site.baseurl }}/arsip/Tonikaku-Kawaii).

Soloyolo: Noromi

Unduh

---
  <ul>
  WEB
    {% for post in site.categories['Tonikaku-Kawaii-s2'] %}
  <li><a class="white pinkhover" href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.epsname }}{% else %}Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}
  </ul>