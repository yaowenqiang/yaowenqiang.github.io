---
layout: default
---

# a header

i am index.md

<p><br><b>My Blog</b></p>
<ul class=”posts”>
    {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span></li>
    {% endfor %}
</ul>
