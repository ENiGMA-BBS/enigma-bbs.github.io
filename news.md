---
layout: page
title: News
permalink: /news/
---
<ul class="posts">
    {% for post in site.posts %}
    <li>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        <span class="posted-date">- {{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
    {% endfor %}
</ul>