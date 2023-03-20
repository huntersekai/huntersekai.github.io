---
layout: category
title: Tonikaku Kawaii꞉ Seifuku (WEB)
epsname: Pokoknya Imut꞉ Seragam
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1044993731960512562/mpv-shot0168.jpg
---

Episode OVA dari [Tonikaku Kawaii](https://a-1.fansub.id/Tonikaku-Kawaii)

Soloyolo: Noromi

Unduh

---
  <ul>
    {% for post in site.categories['Tonikaku-Kawaii-Seifuku'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.eps }}{% else %} Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}
  </ul>