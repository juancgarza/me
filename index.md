---
layout: default
title: "JCGR's blog"
---

## JCGR's blog

### About me

My name is Juan Carlos what I mostly do is read and write code. I'll soon be happily married to my girlfriend in September.
I like to write but don't do it frequently, I will write about anything (I'm warning future readers that halfof my posts will be about tech and products)..

## My posts
{% for post in site.posts %}<p><a href="{{ post.baseurl }}/me{{ post.url }}">{{ post.title }}</a></p>{% endfor %}
