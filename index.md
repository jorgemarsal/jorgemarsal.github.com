---
layout: page
title: Jorge Martinez
tagline: 
---
{% include JB/setup %}

I'm a software engineer currently working in distributed systems, machine learning and cloud.
 
<jorge.marsal@gmail.com>

<h2>Blog posts</h2>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



