---
title: "Blog"
permalink: /blog/
layout: single_full
toc: false
page_css:
  - /assets/css/blog.css

# Edit these anytime
quote:
  text: "But it can also happen (even in a society that applies itself to being the fairest and best designed for assuring the harmonious development of all its members: this may be stated as a certainty without any risk of being mistaken) that isolated, maladjusted, lonely individuals, morbidly attached to their childhood, withdrawn into themselves and cultivating a more or less conscious taste for a certain form of defeat, by giving in to an apparently useless obsession, succeed in digging up and laying bare a fragment of reality that is still unknown."
  author: "Age of Suspicion, Nathalie Sarraute"
reading:
  title: "The Magic Mountain"
  author: "Thomas Mann"
show_posts: false      # ← flip to true later to display post
classes: blog-tight   # ← add this
---

<!-- Top quote (compact) -->
> “{{ page.quote.text }}”
> <span class="blog-quote__author">— {{ page.quote.author }}</span>
{: .blog-quote}

<!-- Now reading (single line) -->
<div class="now-reading now-reading--inline">
  <span class="now-reading__label">Now reading:</span>
  <span class="now-reading__text">
    {{ page.reading.title }} — {{ page.reading.author }}{% if page.reading.note %} • {{ page.reading.note }}{% endif %}
  </span>
</div>


{% if page.show_posts %}
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
{% endif %}
