---
layout: archive
title: "Course Works"
permalink: /courseworks/
author_profile: true
redirect_from:
  - /course-works
  - /coursework
  - /coursework
---

{% include base_path %}

{% for post in site.courseworks %}
  {% include archive-single.html %}
{% endfor %}