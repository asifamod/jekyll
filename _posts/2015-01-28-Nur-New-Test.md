---
layout: post
title: Test Post
post_date: 26 August 2014
tags: 
  - announcements
  - privacy
author: Test Team
published: true
image: "/images/blog/blog-democracy.jpg"
description: Test applied to the Foundation to expand his work on the Madison Project which...
---
## A New Post

### Title:
{{page.title}}

### Auther:
{{page.author}}

### Description:
{{page.description}}

### Post Date
{{page.post_date}}

### Tags
{% for tag in page.tags %}
[{{tag}}]({{site.baseurl}}/tag/{{ tag }})
{% endfor %}

### Image
![]({{ page.image | prepend: site.baseurl}})
