---
layout: default
title: Blog
permalink: /blog/
---

# Blog

Welcome to my blog! Here you'll find my latest posts.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>