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

+ **Spatial Uncertainty-Aware Semi-Supervised Crowd Counting**  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Xiaoyun Yang, Xuesheng Qian, Xiaowei Huang, and Yalin Zheng.      
IEEE International Conference on Computer Vision. **ICCV 2021**. [paper](https://arxiv.org/abs/2107.13271) [code]()

+ **Unsupervised Parameter-specific Affine Registration for 2D/3D Medical Images using Convolutional Neural Networks**  
Xu Chen,  **Yanda Meng**, Yitian Zhao, Rachel Williams, Srinivasa Vallabhaneni, Yalin Zheng.    
International Conference on Medical Image Computing and Computer-Assisted Intervention. **MICCAI 2021**.

+ **A regularization term for slide correlation reduction in whole slide image analysis with deep learning**  
Hongrun Zhang, **Yanda Meng**, Xuesheng Qian, Xiaoyun Yang, Sarah E.Coupland, and Yalin Zheng.  
Medical Imaging with Deep Learning. **MIDL 2021**. [paper](https://openreview.net/forum?id=2vCFIoWDS6E) [code](https://github.com/hrzhang1123/SlideCorrelationReduction)

+ **Introducing the GEV Activation Function for Highly Unbalanced Data to Develop COVID-19 Diagnostic Models**  
Joshua Bridge, **Yanda Meng**, Yitian Zhao, Yong Du, Mingfeng Zhao, Renrong Sun, and Yalin Zheng.  
IEEE JOURNAL OF BIOMEDICAL AND HEALTH INFORMATICS, VOL. 24, NO. 10, OCTOBER 2020. **IEEE-JBHI** [paper](https://ieeexplore.ieee.org/document/9151288) [code](https://github.com/JTBridge/GEV)

+ **CNN-GCN Aggregation Enabled Boundary Regression for Biomedical Image Segmentation**  
**Yanda Meng**, Meng Wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
International Conference on Medical Image Computing and Computer-Assisted Intervention. **MICCAI 2020 (oral)**. [paper](https://www.springerprofessional.de/en/cnn-gcn-aggregation-enabled-boundary-regression-for-biomedical-i/18443174)

+ **Regression of Instance Boundary by Aggregated CNN and GCN**  
**Yanda Meng**, Meng wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
European Conference on Computer Vision. **ECCV2020**. [paper](https://link.springer.com/chapter/10.1007/978-3-030-58598-3_12).









