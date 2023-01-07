---
layout: category
title: Spy Kyoushitsu
epsname: Kelas Intel
coverPhoto: 
---

Hanazono, yang biasa dipanggil Lily, direkrut ke organisasi intel bernama "Tomoshibi". Organisasi tersebut beranggotakan murid yang nyaris gagal seperti dirinya. Merasa curiga, Lily pun turun tangan melancarkan rencananya kepada tenaga pendidiknya, akankah rencana Lily berhasil?

Soloyolo: Noromi

Unduh

---
  <ul>
    {% for post in site.categories['Spy-Kyoushitsu'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.epsname %}Episode {{ post.eps }}: {{ post.epsname }}{% else %}Episode {{ post.eps }}: {{ page.title }}{% endif %}</a></li>
  {% endfor %}
  </ul>