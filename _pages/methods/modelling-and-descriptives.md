---
layout: collection
title: "Methods: Modelling and descriptives"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /modelling-and-descriptives/
---

<ul>
  {% for post in site.tags.modelling-and-descriptives %}
    {% if post.url %}
       <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

