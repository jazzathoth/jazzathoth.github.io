---
layout: page-fullwidth
show_meta: false
title: "Data Science Projects"
subheadline: "Interesting things I have worked on"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/ds/"
---
<ul>
    {% for post in site.categories.ds %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
