---
layout: collection
title: "Methods: Randomised trials"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /randomised-trial/
---

<ul>
  {% for post in site.tags.randomised-trial %}
    {% if post.url %}
       <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

