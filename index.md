---
title: ""
---

## What's this?

This page is a product of a local hack, #codemodekalmar, hosted at [Webready HQ](https://webready.se) in Kalmar.  
The purpose with the hack is to get together and try out new stuff or stuff you always wanted to check out or try. 
With no requirement of achieve anything special or demo or something like just have fun around with friends.

### Posts
<ul>
  {% for post in site.posts %}
    <li>
        {{ post.date | date: "%Y-%m-%d" }} - <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>