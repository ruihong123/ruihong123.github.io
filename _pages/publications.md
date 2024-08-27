---
permalink: /publications/
title: "Publications"
author_profile: true
redirect_from: 
  - /publications/
  - /publications.html
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

test test test