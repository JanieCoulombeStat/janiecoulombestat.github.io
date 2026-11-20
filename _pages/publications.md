---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Publications on this website are not always up to date. I invite you to look at my Google Scholar account (link on the left column) for more details.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
