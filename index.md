---
layout: page
title: Code Resume
tagline: by Robert Wilkins, III
---
{% include JB/setup %}

    <div class="hero-unit">
    <h1>My Repositories</h1>
    <h2>Overview</h2>
    <p>
    <a class="btn btn-primary btn-large" href='http://github.com/genome21'>Github</a>
    <a class="btn btn-primary btn-large" href='http://stackoverflow.com/users/1330184/genome21?tab=summary'>StackOverflow</a>
    </p>
### Posts on Code

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
</div>



