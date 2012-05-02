---
layout: page
title: Code Resume
tagline: by Robert Wilkins, III
---
{% include JB/setup %}

<div class="hero-unit"><center>
    <img src="assets/caintrae_pose2smaller toside25.PNG"><h1>My Repositories</h1><br><br>
    <p>
    <a class="btn btn-primary btn-large" href='http://github.com/genome21' target="_blank">Github</a>
    <a class="btn btn-primary btn-large" href='http://stackoverflow.com/users/1330184/genome21?tab=summary' target="_blank">StackOverflow</a>
    </p>
    </center></div>
<h3>Posts on Code</h3>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

