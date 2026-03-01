---
title: "Archive"
permalink: /archive/
layout: single
author_profile: true
---

Browse every post by month.

{% assign posts_by_year = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in posts_by_year %}
  ## {{ year.name }}
  {% for post in year.items %}
  - {{ post.date | date: "%b %-d" }} — [{{ post.title }}]({{ post.url | relative_url }})
  {% endfor %}
{% endfor %}
