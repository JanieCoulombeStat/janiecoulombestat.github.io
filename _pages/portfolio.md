---
layout: archive
title: "Students supervision"
permalink: /portfolio/
author_profile: true
redirect_from: 
  - /resume/
---

{% include base_path %}
 
{% for post in site.portfolio reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
