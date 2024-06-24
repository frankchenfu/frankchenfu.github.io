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

Course work (update at 20:03)

{% for post in site.courseworks reversed %}
  {% include archive-single.html %}
{% endfor %}