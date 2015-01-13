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

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

~~this~~

**Inline code**
I think you should use an
`<addr>` element here instead.


**As Kanye West said:**

> We're living the future so
> the present is our past.

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)


1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b
   
   
* Item 1
* Item 2
  * Item 2a
  * Item 2b

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

*You **can** combine them*

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag




