---
layout: collection
title: "Methods: Synthetic control"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /synthetic-control/
---

<dl>
  {% for post in site.tags.synthetic-control %}
       <dt><a href="{{ post.url }}">{{ post.title }}</a></dt>
       <font color="gray"><em>{{ post.excerpt }}<br></em>
       <br>
  {% endfor %}


