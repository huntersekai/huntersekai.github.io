---
layout: category
title: Shadows House S2
epsname: SHADOWS HOUSE S2
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1023090125556678706/unknown.png
---

Sinopsis: Musim kedua dari serial [Shadows House](https://a-1fansub.github.io/Shadows-House-Paketan).

Penerjemah: Noromi<br>
Pengecek Terjemahan: Noromi<br>
Penata Rias: Noromi<br>
Penggaya Lagu: Noromi<br>
Peramu Video: Azkaxfannx (WEB), Noromi (BD)<br>
Penyelaras Akhir: Noromi<br>

Unduh

---
  <ul>
  BD
    {% for post in site.categories['Shadows-House-2nd-Season-bd'] %}
  <li><a class="white pinkhover" href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.epsname }}{% else %}Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}<br>
  WEB
    {% for post in site.categories['Shadows-House-2nd-Season'] %}
  <li><a class="white pinkhover" href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.epsname }}{% else %}Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}
  </ul>