---
layout: archive
title: "Startups and Initiatives"
permalink: /startups/
author_profile: true
---

{% include base_path %}

{% for post in site.startups reversed %}
  {% include archive-single.html %}
{% endfor %}
