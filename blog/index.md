---
layout: default   # You can change this to 'blog' if you have a custom blog layout in _layouts/
title: "MLCore Blog"
description: "Work in progress. Gradually adding topics on machine learning and related fields."
permalink: /blog/    # Ensures this is located at /blog/ on your site
---
# Welcome to the MLCore Blog

Work in progress. Gradually adding topics on machine learning and related fields.

## Topics Covered
Here are some of the main topics you'll find discussed here:

- **Bayes Theorem**
- **Maximum Entropy**
- **Exponential Family**
- **Free Energy**
- **Proximal Operators**
- **Kernels**
- **Graph Laplacians**
- **Bellman Equations**
- **Random Matrices**
- **Emergence and Criticality**

---

### Recent Blog Posts:
{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
