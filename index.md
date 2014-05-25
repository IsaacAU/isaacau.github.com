---
layout: page
title: Isaac's Blog
tagline: ---- all about programming
---
{% include JB/setup %}

### Summary

This is a personal blog for recording some programming staff.

### Practice C++ on Leetcode

### Emacs Notes

### Lisp Notes

### All posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
