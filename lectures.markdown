---
layout: page
title: Lectures
permalink: /lectures/
---

Below is a list of lectures. Click on a lecture to view its dedicated page with notes and resources.

<ul>
    {% for lecture in site.lectures %}
        <li>
            <a href="{{ lecture.url | relative_url }}">{{ lecture.title }}</a>
        </li>
    {% endfor %}
</ul>

