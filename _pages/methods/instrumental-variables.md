---
layout: collection
title: "Methods: Instrumental variables"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /instrumental-variables/
---

<ul>
  {% for post in site.tags.instrumental-variables %}
    {% if post.url %}
       <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

