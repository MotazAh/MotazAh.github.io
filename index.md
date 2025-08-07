---
layout: default
title: Home
---

# Welcome to My Cybersecurity Blog

I'm studying for CompTIA Security+ and learning hands-on through TryHackMe.

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>