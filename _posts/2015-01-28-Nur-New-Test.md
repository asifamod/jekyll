---
layout: post
title: Nur's New Test
post_date: 28 January 2015
tags: 
  - announcements
  - privacy
author: Test Team
published: true
image: "/images/blog/blog-democracy.jpg"
description: Is this post reflecting live? I don't know ...
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
