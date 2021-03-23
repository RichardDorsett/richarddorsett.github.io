---
layout: collection
title: "Methods: Difference-in-differences"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /difference-in-differences/
---

<ul>
  {% for post in site.tags.difference-in-differences %}
       <dt><a href="{{ post.url }}">{{ post.title }}</a></dt>
       <font color="gray"><em>{{ post.excerpt }}<br></em>
       <br>
  {% endfor %}
</ul>

