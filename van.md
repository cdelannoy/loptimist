---
layout: page
title: Van
permalink: /van/
---

This page is for updates from the road during my travels.

{% for post in site.categories.van %}
 <li> &nbsp; <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}