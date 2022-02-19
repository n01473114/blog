---
title: Jose's Blog
layout: "index.njk"
---

Hello

<ul>

{%- for post in collections.posts -%}
<li>
    <a href="{{ post.url }}">
        {{ post.data.title }}
    </a>
</li>
{%- endfor -%}

</ul>
