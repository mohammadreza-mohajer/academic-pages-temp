---
title: "Mathematical Notes"
layout: single
author_profile: true
classes: wide
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

{% for post in site.posts limit:5 %}

### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt }}

---

{% endfor %}
