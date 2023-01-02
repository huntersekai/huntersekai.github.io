---
layout: category
title: Spy Kyoushitsu
epsname: Kelas Intel
coverPhoto: 
---

Saat ini, negara yang dilanda konflik malah melancarkan operasi rahasia. Lily direkrut untuk menjadi intel dan menjalani pelatihan, namun kemampuannya jelek sekali. Merasa tak punya kesempatann untuk lulus, dia diam-diam bergabung ke tim misterius "Tomoshibi". Naasnya tim tersebut juga berisikan intel yang putus asa. Mereka pun bersatu menyelesaikan misi mustahil dari pemandu genius mereka, tapi, tujuan sebenarnya di balik kelas mereka lebih mengerikan daripada yang mereka bayangkan ... apakah itu?

Soloyolo: ?

Unduh

---
  <ul>
    {% for post in site.categories['Spy-Kyoushitsu'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.epsname %}Episode {{ post.eps }}: {{ post.epsname }}{% else %}Episode {{ post.eps }}: {{ page.title }}{% endif %}</a></li>
  {% endfor %}
  </ul>