---
layout: page-no-title
title: Good News Everyone!!
tagline: or news in general
---
{% include JB/setup %}


<div class="jumbotron">
    <div class="row">
        <div class="col-xs-5 col-md-5">
            <a href="#" class="thumbnail">
            <img src="{{ site.url }}/assets/daily-delirium/level-end.png" />
            </a>
        </div>

        <div class="col-xs-7 col-md-7">
            <h1>Daily Delirium</h1>
            <p>
                A procedurally generated side scroller, that changes everyday!! Currently only
                available for Android. I will be looking into iOS when I can afford to buy
                apple's dev account.
            </p>
            <p>
                <a class="btn btn-primary btn-lg" role="button" href="https://play.google.com/store/apps/details?id=com.mentallydefective.dreamtime">Get it on Google Play</a>
                <a class="btn btn-lg" role="button" href="http://defektivedevelopment.github.io/daily-delirium/">View Game Site</a>
            </p>
        </div>
</div>
</div>


<div class="page-header">
  <h1>{{ page.title }} {% if page.tagline %} <small>{{ page.tagline }}</small>{% endif %}</h1>
</div>

<div>
  {% for post in site.posts %}
    <p>
        <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        {{ post.content }}
    </p>
  {% endfor %}
</div>
