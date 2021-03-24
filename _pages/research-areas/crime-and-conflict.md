---
layout: collection
title: "Research areas: Crime and conflict"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_3101.JPG
permalink : /crime-and-conflict/
---
<!--
<p style="font-size:2em">Crime and conflict</p>
-->

<dl>
  {% for post in site.tags.crime-and-conflict %}
       <dt><a href="{{ post.url }}">{{ post.title }}</a></dt>
       <font color="gray"><em>{{ post.excerpt }}<br></em>
       <br>
  {% endfor %}

