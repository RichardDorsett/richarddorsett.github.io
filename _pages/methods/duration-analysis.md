---
layout: collection
title: "Methods: Duration analysis"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /duration-analysis/
---

<ul>
  {% for post in site.tags.duration-analysis %}
       <dt><a href="{{ post.url }}">{{ post.title }}</a></dt>
       <font color="gray"><em>{{ post.excerpt }}<br></em>
       <br>
  {% endfor %}
</ul>

