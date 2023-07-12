---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

Electronics
======

{% include base_path %}


{% for post in site.eeportfolio %}
  {% include archive-single.html %}
{% endfor %}

Programming
======
{% for post in site.csportfolio %}
  {% include archive-single.html %}
{% endfor %}

