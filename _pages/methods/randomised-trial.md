---
layout: collection
title: "Methods: Randomised trials"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /randomised-trial/
---

<dl>
  {% for post in site.tags.randomised-trial %}
       <dt><a href="{{ post.url }}">{{ post.title }}</a></dt>
       <font color="gray"><em>{{ post.excerpt }}<br></em>
       <br>
  {% endfor %}


