---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

 

{% include base_path %}

Publications on this website are not always up to date. I invite you to look at <u><a href="{{author.googlescholar}}">my Google Scholar profile</a> for more recent work.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
