---
title: Blog
layout: main
---
# Blog posts

*[Click here](/) to go back to homepage.*
{% for post in site.posts %}
* **{{ post.title }}** ({{ post.date | date_to_string }}) - {{ post.desc }} ([Read]({{ post.url }}))
  {% endfor %}
<hr>