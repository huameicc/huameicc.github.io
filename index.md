---
layout: default
title: Home
---

{% for post in site.posts %}
  {{ post.date | date:"%Y-%m-%d" }}  **<a href="{{ post.url }}" target="_blank">{{ post.title }}</a>**
 >{{ post.description }}
{% endfor %}

 
   
