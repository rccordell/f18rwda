---
layout: post
title: Updates
nav-menu: true
description: 'What is new in RWDA?'
image: https://c2.staticflickr.com/2/1035/762896494_e1b73b73fc_z.jpg
---

{% for post in site.posts %}
\<header class="major"\>
\<h1\>{{ post.title }}\</h1\>
\</header\>
{% if post.image %}\<span class="image main"\>\<img src="{{ site.baseurl }}/{{ post.image }}" alt="" /\>\</span\>{% endif %}
{% if post.date %}\<p\>{{ post.date }}\</p\>{% endif %}
\<p\>{{ post.content }}\</p\>
{% endfor %}