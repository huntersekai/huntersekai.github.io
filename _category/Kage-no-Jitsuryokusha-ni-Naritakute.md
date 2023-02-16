---
layout: category
title: Kage no Jitsuryokusha ni Naritakute! (WEB)
epsname: Penguasa Bayangan
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1034804043685568532/mpv-shot0160.jpg
---

Ketabrak truk, ke isekai punya kekuatan, jadi pemimpin organisasi belakang layar .... Intinya kebelet jadi Penguasa Bayangan.

Penerjemah: KiryuuNii<br>
Pengecek Terjemahan: Noromi<br>
Penata Rias: KiryuuNii<br>
Penggaya Lagu: Noromi<br>
Peramu Video: KiryuuNii<br>
Penyelaras Waktu: KiryuuNii, Noromi<br>
Penyelaras Akhir: Noromi<br>

Unduh

---
  <ul>
    {% for post in site.categories['Kage-no-Jitsuryokusha-ni-Naritakute'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.epsname %}Episode {{ post.eps }}: {{ post.epsname }}{% else %}Episode {{ post.eps }}: {{ page.title }}{% endif %}</a></li>
  {% endfor %}
  </ul>