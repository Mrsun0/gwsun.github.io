---
layout: archive
title: "Papers"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Patents
<span style="font-size: 0.8em; color: #777;">As the First Student Inventor for the following patents.</span>
- 一种适用于芯片倾斜布线的连通图生成方法 (2024102402830)（已授权） 丁虎，**孙国伟**，杨丽莹
- 一种芯片布线中连通图的生成方法 (2023114276571)（已公开） 丁虎，**孙国伟**，杨丽莹
