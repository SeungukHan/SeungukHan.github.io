---
layout: post
title: Note
permalink: /note/
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} ({{ post.date | date: "%b %d, %Y"}})</a>
    </li>
  {% endfor %}
</ul>
