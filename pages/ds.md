---

layout: page-fullwidth
show_meta: false
title: "Data Science Projects"
subheadline: "Interesting things I have worked on"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/projects/"

---


<ul>
      {% for post in site.categories.projects %}
        <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
</ul>
