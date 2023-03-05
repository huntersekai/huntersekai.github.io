---
layout: category
title: Futoku no Guild (WEB)
epsname: Serikat Amoral
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1036998735449817198/mpv-shot0164.jpg
---

Kikuru Madan, pemburu yang ingin keluar dari serikat karena hidupnya terasa hampa menjalani rutinitas yang begitu-begitu saja dan ingin menjalani kehidupan santai di kampus, namun itu semua terpaksa dibatalkan sebab dia harus melatih para pemula yang dapat menggantikannya dirinya

Penerjemah: Noromi<br>
Pengecek Terjemahan: KiryuuNii<br>
Penata Rias: Noromi<br>
Penggaya Lagu: KiryuuNii<br>
Penyelaras Waktu: Noromi<br>
Penyelaras Akhir: KiryuuNii<br>

Unduh

---
  <ul>
  <li><a style="font-weight: bold" href="{{ site.baseurl }}/kategori/Futoku-no-Guild-bd">Futoku no Guild (BD)</a></li>
    {% for post in site.categories['Futoku-no-Guild'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.epsname %}Episode {{ post.eps }}: {{ post.epsname }}{% else %}Episode {{ post.eps }}: {{ page.title }}{% endif %}</a></li>
  {% endfor %}
  </ul>