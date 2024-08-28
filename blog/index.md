---
title: Blog
layout: main
---
# Blog posts
***This blog is a work-in-progress.*** *Report any bugs or issues over on the [GitHub repo](https://github.com/theclyron.github.io). If you're looking for a pre-Clyron blog post, please check out the [Lynxmic Blog](https://clyron.is-a.dev/lynxblog).*
{% for post in site.posts %}
* **{{ post.title }}** ({{ post.date | date_to_string }} - <i class="fas fa-clock"></i>&nbsp;{{ post.content | number_of_words | divided_by: 180 }} minute read) - {{ post.desc }} ([Read]({{ post.url }}))
<hr>
  {% endfor %}
  <div style="text-align: center;">
        <a class="button" href="/">Back home</a>
    </div>