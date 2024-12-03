---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a first-year PHD candidate in the Department of Computer Science at Hong Kong Baptist University (HKBU) under the supervision of 

[Dr. Xin Huang]: https://www.comp.hkbu.edu.hk/~xinhuang/index.html	"Dr. Xin Huang"

. I received my BEng degree in Software Engineering from Zhejiang Normal University (ZJNU) in 2024.

 <a href='https://scholar.google.com/citations?user=WMkMTb4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。

My research interests includes:
- Graph algorithm

<span class='anchor' id='-xl'></span>
