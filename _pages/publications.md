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


+ **Regression of Instance Boundary by Aggregated CNN and GCN**
Yanda Meng, Meng wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
European Conference on Computer Vision. ECCV2020. [paper](https://www.springerprofessional.de/en/cnn-gcn-aggregation-enabled-boundary-regression-for-biomedical-i/18443174).

+ **CNN-GCN Aggregation Enabled Boundary Regression for Biomedical Image Segmentation**  
Yanda Meng, Meng Wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
International Conference on Medical Image Computing and Computer-Assisted Intervention. MICCAI 2020. [paper](https://www.springerprofessional.de/en/cnn-gcn-aggregation-enabled-boundary-regression-for-biomedical-i/18443174)
