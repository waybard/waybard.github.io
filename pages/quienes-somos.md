---
layout: page
permalink: "/quienes-somos/"

header:
    title: Quienes somos
    image_fullwidth: top-generico.jpg

tags:
    - post format
categories:
    - design
---

<ul>
    {% for post in site.tags.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>