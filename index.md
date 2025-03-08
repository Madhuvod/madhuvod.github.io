---
layout: default
title: Madhu's Blog
---

# Hello, this is 2025 and the singularity is almost here.

![Madhu's Profile Picture](assets/images/profile.jpg){: .profile-image}

## Latest Posts

{% raw %}{% for post in site.posts %}
  <article>
    <h3>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h3>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_string }}</time>
    {{ post.excerpt }}
  </article>
{% endfor %}{% endraw %}

---

Intelligence won't be just Augmented.

This is my first blog post about singularity and everything that is going on X on 8th march 2025 - mcps, amd x tinycorp, cursor $10b valuation, and manus AI just released.