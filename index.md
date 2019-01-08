---
title: COMP 424
layout: default-vertical

categories:
- general
- site

tags: general site home
published: true
summary: Client-Side Web Design, Spring 2019
---

Welcome to the course website for COMP 424, *Client-Side Web Design*.

This course is offered by the [Department of Computer Science](http://www.luc.edu/cs/) at [Loyola University Chicago](http://www.luc.edu).

***

#### Recent Updates
{% for post in site.posts limit: 5 %}

<!--{{ post.date | date_to_string }} | [{{ post.title }}]({{ post.url }})-->
* {{ post.date | date_to_string }} - [{{ post.title }}]({{ post.url }})

  {{ post.summary }}

{% endfor %}
