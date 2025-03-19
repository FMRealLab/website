---
title: News
nav:
  order: 4
  tooltip: Musings and miscellany
---

# {% include icon.html icon="a-regular fa-newspaper" %} News

Explore the latest news of our lab!

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
