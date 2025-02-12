---
title: Welcome to my little corner of the internet
---


This was created as part of the DevSecOps course from coursera

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
