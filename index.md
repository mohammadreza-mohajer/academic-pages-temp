---
layout: home
title: "Mathematical Notes"
author_profile: true
---

Welcome to my mathematical blog.

I am a mathematician interested in analysis, partial differential equations, weighted Sobolev spaces, compact embedding theory, and arithmetic geometry.

This website contains research notes, expository articles, and discussions of mathematical ideas.


## Research Interests

- Degenerate elliptic partial differential equations
- Weighted Sobolev spaces
- Compact embeddings
- Analysis on metric measure spaces
- p-adic analysis and arithmetic geometry


## Latest Articles

{% assign posts = site.posts %}
{% for post in posts limit:5 %}

### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt }}

---

{% endfor %}
