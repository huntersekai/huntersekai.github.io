---
layout: category
title: Tonikaku Kawaii꞉ Seifuku
epsname: Pokoknya Imut: Seragam
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1044993731960512562/mpv-shot0168.jpg
---

Episode OVA dari [Tonikaku Kawaii](https://a-1.fansub.id/Tonikaku-Kawaii)

Soloyolo: Noromi

Unduh

---
  <ul>
    {% for post in site.categories['Tonikaku-Kawaii-Seifuku'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.epsname %}Episode {{ post.eps }}: {{ post.epsname }}{% else %}Episode {{ post.eps }}: {{ page.title }}{% endif %}</a></li>
  {% endfor %}
  </ul>