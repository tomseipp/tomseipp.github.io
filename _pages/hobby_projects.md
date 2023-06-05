---
layout: archive
title: "Hobby Projects"
permalink: /hobby_projects/
author_profile: true
---

{% include base_path %}

{% for post in site.hobby_projects reversed %}
  {% include archive-single.html %}
{% endfor %}