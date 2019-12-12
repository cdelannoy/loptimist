---
layout: page
title: Van
permalink: /van/
---

This page is for updates from the road during my travels.

![vanpic](../assets/images/van.jpg)

{% for post in site.categories.van %}
 <li> &nbsp; <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}