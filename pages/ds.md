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
    {% for category in site.categories %}
      {% for post in category %}
        <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}{{ site.url }}{{ site.baseurl }}{{ post.url }}</a></li>
      {% endfor %}
    {% endfor %}
</ul>
