---
title: "Hello Egghead"
layout: "base.njk"
---

This is a home page.

{% for post in collections.posts %}
  <a href="{{post.url}}">{{ post.data.title }}
  {% endfor %}