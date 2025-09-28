---
title: "Blog"
permalink: /blog/
layout: single_full
toc: false
---

<p class="blog-intro">Short updates and longer thoughts. Newest first.</p>

<ul class="blog-list">
{% for post in site.posts %}
  <li class="blog-item">
    <a class="blog-link" href="{{ post.url | relative_url }}">
      <span class="blog-title">{{ post.title }}</span>
    </a>
    <span class="blog-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
    {% if post.excerpt %}
      <div class="blog-excerpt">{{ post.excerpt | strip_html | truncate: 200 }}</div>
    {% endif %}
  </li>
{% endfor %}
</ul>
