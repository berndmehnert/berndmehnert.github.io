---
layout: page
title: Blog
permalink: /posts/
---

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>