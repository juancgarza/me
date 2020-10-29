---
layout: default
title: "JCGR's blog"
---

## JCGR's blog

### About me

My name is Juan Carlos what I mostly do is read and write code. I happily married my 5 year girlfriend in September 2020.

I like to write but don't do it frequently, I will write about anything (I'm warning future readers that halfof my posts will be about tech and products)..

## My posts
{% for post in site.posts %}<p><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></p>{% endfor %}
