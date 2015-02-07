---
layout: page
title: Posts
---

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &nbsp; &nbsp; [ {{ post.title }} ]({{ post.url }})
{% endfor %}