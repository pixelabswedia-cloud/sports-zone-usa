---
layout: default
title: NFL News & Analysis
---

# NFL Insights
Welcome to the NFL section. Here we discuss strategies, player updates, and fantasy football tips.

### Latest NFL Articles
<ul>
  {% for post in site.posts %}
    {% if post.title contains "NFL" %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
