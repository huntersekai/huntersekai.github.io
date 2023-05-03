---
layout: category
title: Laid-Back Camp△ The Movie
epsname: Film Kemah Santai△
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1042461075947388998/image.png
---

Berniat meramaikan kembali tempat wisata yang ditinggalkan, Rin dan kawan-kawan berencana membangun perkemahan di tempat tersebut, namun ... selebihnya silakan nonton sendiri ketimbang kena spoiler nih sinopsis.

Soloyolo: Noromi

Unduh

---
  <ul>
  BD
    {% for post in site.categories['Yuru-Camp-Movie-bd'] %}
  <li><a class="white pinkhover" href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.epsname }}{% else %}Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}<br>
  WEB
    {% for post in site.categories['Yuru-Camp-Movie'] %}
  <li><a class="white pinkhover" href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.epsname }}{% else %}Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}
  </ul>