---
layout: default
---

## Core Team
@giovino, @jeffmurphy and @wesyoung

## Recent Posts
<ul class="posts">
    {% for post in site.posts limit:site.post_limit %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.siteurl }}{{ post.url }}">[{{ post.category }}] {{ post.title }}</a></li>
    {% endfor %}
</ul>
