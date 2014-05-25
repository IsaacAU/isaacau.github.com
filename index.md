---
layout: page
title: Isaac's Blog
tagline: ---- all about programming
---
{% include JB/setup %}

### Summary

This is a personal blog for recording some programming staff.

### Practice C++ on Leetcode `[book](http://www.mktechnicalclasses.com/Notes/Cracking%20the%20Coding%20Interview,%204%20Edition%20-%20150%20Programming%20Interview%20Questions%20and%20Solutions.pdf)`

### Emacs Notes

### Lisp Notes

### All posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
