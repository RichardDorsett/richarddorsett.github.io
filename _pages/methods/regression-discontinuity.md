---
layout: collection
title: "Methods: Regression discontinuity"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /regression-discontinuity/
---

<dl>
  {% for post in site.tags.regression-discontinuity %}
       <dt><a href="{{ post.url }}">{{ post.title }}</a></dt>
       <font color="gray"><em>{{ post.excerpt }}<br></em>
       <br>
  {% endfor %}


