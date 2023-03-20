---
layout: category
title: Shadows House (BD)
epsname: SHADOWS HOUSE
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1003664979641237574/mpv-shot0109.jpg
---

Mansion yang berada di atas bukit yang dikenal dengan nama Rumah Bayangan, rumah dari bayangan yang hidup layaknya bangsawan. Mereka mengeksperesikan emosinya dengan Boneka Hidup yang sekaligus menjadi pelayan.

Soloyolo: Noromi

Unduh

---
  <ul>
    {% for post in site.categories['Shadows-House-bd'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.eps }}{% else %} Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}
  </ul>