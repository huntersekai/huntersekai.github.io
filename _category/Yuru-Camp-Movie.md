---
layout: category
title: Yuru Camp△ Movie (WEB)
epsname: Film Kemah Santai△
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1042461075947388998/image.png
---

Berniat meramaikan kembali tempat wisata yang ditinggalkan, Rin dan kawan-kawan berencana membangun perkemahan di tempat tersebut, namun ... selebihnya silakan nonton sendiri ketimbang kena spoiler nih sinopsis.

Soloyolo: Noromi

Unduh

---
  <ul>
    {% for post in site.categories['Yuru-Camp-Movie'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.epsname %}Episode {{ post.eps }}: {{ post.epsname }}{% else %}Episode {{ post.eps }}: {{ page.title }}{% endif %}</a></li>
  {% endfor %}
  </ul>