---
layout: page
title: Tech
permalink: /tech/
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} ({{ post.date | date: "%b %d, %Y"}})</a>
    </li>
  {% endfor %}
</ul>
