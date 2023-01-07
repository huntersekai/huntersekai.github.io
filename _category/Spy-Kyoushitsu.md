---
layout: category
title: Spy Kyoushitsu
epsname: Kelas Intel
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1061182688544964658/mpv-shot0182.jpg
---

Hanazono atau Lily, direkrut ke organisasi intel bernama "Tomoshibi". Organisasi tersebut beranggotakan murid yang nyaris gagal seperti dirinya, mereka direkrut dengan tujuan menuntaskan Misi Mustahil, akankah mereka berhasil?

Soloyolo: Noromi

Unduh

---
  <ul>
    {% for post in site.categories['Spy-Kyoushitsu'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.epsname %}Episode {{ post.eps }}: {{ post.epsname }}{% else %}Episode {{ post.eps }}: {{ page.title }}{% endif %}</a></li>
  {% endfor %}
  </ul>