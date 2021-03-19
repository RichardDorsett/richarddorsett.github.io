---
layout: collection
title: "Methods: Regression discontinuity"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /regression-discontinuity/
---

<ul>
  {% for post in site.tags.regression-discontinuity %}
    {% if post.url %}
       <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

