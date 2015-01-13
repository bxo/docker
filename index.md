---
layout: default
title: My Blog
---

#This is Markdown
Here is _book_  
**Here is bold**
<h2>{{ page.title }}</h2>
<p>Newest posts</p>
<ul>
  {% for post in site.posts %}
    <li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>