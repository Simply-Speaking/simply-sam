---
layout: default
title: Simply Speaking
permalink: /
---

## Hi there!

It's so good to have you here! If you are looking to connect, brainstorm, or just catch up, pick a time that works best for you below. Alternatively, you can always check out my blog.

{% include appointment.html %}

<ul class="blog-list">
  {% for post in site.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
      <a href="{{ site.url }}/{{ post.url }}" class="post-link">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>