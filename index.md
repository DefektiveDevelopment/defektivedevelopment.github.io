---
layout: page
title: Good News Everyone!!
tagline: or news in general
---
{% include JB/setup %}


<div>
  {% for post in site.posts %}
    <p>
        <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        {{ post.tagline }}
    </p>
  {% endfor %}
</div>
