---
permalink: /
title: "Jacobus van der Linden"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Publication highlights

{% if site.publication_category %}
  {% for post in site.publications reversed %}
    {% if post.category != 'highlights' %}
      {% continue %}
    {% endif %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
