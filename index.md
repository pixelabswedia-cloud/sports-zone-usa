---
layout: default
title: Home
---

# Welcome to American Sports Insights
Stay updated with the latest NFL and NBA news. 

### Recent Articles

<ul>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url | relative_url }}">{{ post.title }}</a></strong>
      <br>
      <small>{{ post.date | date: "%B %d, %Y" }} - {{ post.excerpt | strip_html | truncatewords: 20 }}</small>
    </li>
    <hr>
  {% endfor %}
</ul>
