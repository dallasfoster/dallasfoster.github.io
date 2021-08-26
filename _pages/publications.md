---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
header:
  overlay_color: "#000"
  overlay_image: chukchi.jpg
  caption: "Phytoplankton bloom in the Chukchi Sea, June 18, 2018. credit: NASA Earth Observatory"
---

{% include base_path %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
