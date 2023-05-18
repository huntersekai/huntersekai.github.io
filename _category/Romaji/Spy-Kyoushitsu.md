---
layout: category
title: Spy Classroom
epsname: Kelas Intel
coverPhoto: https://cdn.lewd.host/BYyHZPSL.jpg
---

Sinopsis: Hanazono atau Lily, direkrut ke organisasi intel bernama "Tomoshibi". Organisasi tersebut beranggotakan murid yang nyaris gagal seperti dirinya, mereka direkrut dengan tujuan menuntaskan Misi Mustahil, akankah mereka berhasil?

Soloyolo: Noromi

Unduh

---
  <ul>
  BD
    {% for post in site.categories['Spy-Kyoushitsu-bd'] %}
  <li><a class="white pinkhover" href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.epsname }}{% else %}Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}<br>
  WEB
    {% for post in site.categories['Spy-Kyoushitsu'] %}
  <li><a class="white pinkhover" href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.epsname }}{% else %}Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}
  </ul>