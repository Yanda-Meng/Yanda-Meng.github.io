---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

+ **CNN-GCN Aggregation Enabled Boundary Regression for Biomedical Image Segmentation** Medical Image Segmentation using Squeeze-and-Expansion Transformers
Shaohua Li, Xiuchao Sui, Xiangde Luo, Xinxing Xu Yong Liu Rick Siow Mong Goh
The Thirty International Joint Conference on Artificial Intelligence. IJCAI2021 (CCF A).
[paper][code]
