---
layout: collection
title: "Research areas: Employment and welfare"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_3101.JPG
permalink: /employment-and-welfare/
---

<!--
<p style="font-size:2em">Employment and welfare</p>
-->

<dl>
  {% for post in site.tags.employment-and-welfare %}
       <dt><a href="{{ post.url }}">{{ post.title }}</a></dt>
       <font color="gray"><em>{{ post.excerpt }}<br></em>
       <br>
  {% endfor %}


