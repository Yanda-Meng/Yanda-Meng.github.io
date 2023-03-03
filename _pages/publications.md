---
layout: archive
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
# Selected publications (* means equal contribution, <sup>†</sup> means corresponding author)  

### Journals  
+ Bilateral Adaptive Graph Convolutional Network on CT based COVID-19 Diagnosis with Uncertainty-Aware Consensus-Assisted Multiple Instance Learning   
**Yanda Meng**, Joshua Bridge, Cliff Addison, Manhui Wang, Cristin Merritt, Stu Franks, Maria Mackey, Steve Messenger, Renrong Sun, Qiang Li, Yitian Zhao, Yalin Zheng.  
**Medical Image Analysis (2023 IF:~ 13.828)** [paper](https://www.sciencedirect.com/science/article/pii/S1361841522003504?dgcid=rss_sd_all), [code](https://github.com/smallmax00/BAGCN-Covid19).  

+ Transportation Object Counting with Graph-Based Adaptive Auxiliary Learning  
**Yanda Meng**, Joshua Bridge, Yitian Zhao, Joddrell Martha, Yihong Qiao, Xiaoyun Yang, Xiaowei Huang, Yalin Zheng.  
**IEEE Transactions on Intelligent Transportation System (2022 IF: ~9.551)**  [paper](https://ieeexplore.ieee.org/abstract/document/9990574), [code](https://github.com/smallmax00/Counting_With_Adaptive_Auxiliary_Learning).

+ Dual Consistency Enabled Weakly and Semi-Supervised Optic Disc and Cup Segmentation with Dual Adaptive Graph Convolutional Networks  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Dongxu Gao, Barbra Hamill, Godhuli Patri, Tunde Peto, Savita Madhusudhan, and Yalin Zheng.  
**IEEE Transactions on Medical Imaging (2022 IF: ~11.037)** [paper](https://ieeexplore.ieee.org/document/9870838), [code](https://github.com/smallmax00/Dual_Adaptive_Graph_Reasoning).  

+ Graph-based Region and Boundary Aggregation for Biomedical Image Segmentation  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Xiaoyun Yang, Yihong Qiao, Ian J. C. MacCormick, Xiaowei Huang, and Yalin Zheng.  
**IEEE Transactions on Medical Imaging (2021 IF: ~10.048)** [paper](https://ieeexplore.ieee.org/document/9594842), [code](https://github.com/smallmax00/Graph_Region_Boudnary).  

+ Artificial Intelligence Based Analysis of Corneal Confocal Microscopy Images for Diagnosing Peripheral Neuropathy: A Binary Classification Model  
***Yanda Meng**, *Frank G Preston, Maryam Ferdousi, Shazli Azmi, Ioannis Nikolaos Petropoulos, Stephen Kaye, Rayaz Ahmed Malik, Uazman Alam, Yalin Zheng.  
**Journal of Clinical Medicine (2023 IF: ~4.964)** [paper](https://www.mdpi.com/2077-0383/12/4/1284).  

+ Artificial intelligence utilising corneal confocal microscopy for the diagnosis of peripheral neuropathy in diabetes mellitus and prediabetes  
*Frank G Preston, ***Yanda Meng**, Jamie Burgess, Maryam Ferdousi, Shazli Azmi, Ioannis N Petropoulos, Stephen Kaye, Rayaz A Malik, Yalin Zheng, Uazman Alam.  
**Diabetologia (2021 IF: ~10.122)** [paper](https://link.springer.com/content/pdf/10.1007/s00125-021-05617-x.pdf). <font color="#dd0000">(Front Cover of Mar 2022 Issue).</font><br />    

### Conferences  
+ Shape-Aware Weakly/Semi-Supervised Optic Disc and Cup Segmentation with Regional/Marginal Consistency  
**Yanda Meng**, Xu Chen, Hongrun Zhang, Yitian Zhao, Dongxu Gao, Barbra Hamill, Godhuli Patri, Tunde Peto, Savita Madhusudhan, Yalin Zheng  
International Conference on Medical Image Computing and Computer-Assisted Intervention.  
**MICCAI 2022** (early accept rate: 13.0%, 1825 submissions) [paper](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_50), [code](https://github.com/smallmax00/Shape_aware_Weakly-Semi_ODOC_seg). <font color="#dd0000">(Early Accept).</font><br />  

+ Diagnosis of Diabetic Neuropathy by Artificial Intelligence using Corneal Confocal Microscopy  
**Yanda Meng**, Maryam Ferdousi, Ioannis N Petropoulos, Rayaz A Malik, Yitian Zhao, Uazman Alam, Yalin Zheng  
32nd Meeting of the European Association for Diabetic Eye Complications  
**EAsDEC2022** [paper](https://journals.sagepub.com/doi/pdf/10.1177/11206721221092575)  

+ BI-GCN: Boundary-Aware Input-Dependent Graph Convolution Network for Biomedical Image Segmentation  
**Yanda Meng**, Hongrun Zhang, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xuesheng Qian, Xiaowei Huang, and Yalin Zheng.  
The British Machine Vision Conference.  
**BMVC 2021 Oral** (Oral accept rate: 3.3%, 1206 submissions) [paper](https://www.bmvc2021-virtualconference.com/assets/papers/0097.pdf), [code](https://github.com/smallmax00/BI-GConv). <font color="#dd0000">(Oral).</font><br />  

+ Spatial Uncertainty-Aware Semi-Supervised Crowd Counting  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Xiaoyun Yang, Xuesheng Qian, Xiaowei Huang, and Yalin Zheng.      
IEEE International Conference on Computer Vision.  
**ICCV 2021** (accept rate: 25.9%, 6236 submissions) [paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Meng_Spatial_Uncertainty-Aware_Semi-Supervised_Crowd_Counting_ICCV_2021_paper.pdf), [code](https://github.com/smallmax00/SUA_crowd_counting).   

+ Regression of Instance Boundary by Aggregated CNN and GCN  
**Yanda Meng**, Meng wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
European Conference on Computer Vision.  
**ECCV 2020** (accept rate: 26.0%, 5150 submissions) [paper](https://link.springer.com/chapter/10.1007/978-3-030-58598-3_12).   

+ CNN-GCN Aggregation Enabled Boundary Regression for Biomedical Image Segmentation  
**Yanda Meng**, Meng Wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
International Conference on Medical Image Computing and Computer-Assisted Intervention.  
**MICCAI 2020** (early accept rate: 13.3%, 1809 submissions) [paper](https://link.springer.com/chapter/10.1007/978-3-030-59719-1_35) <font color="#dd0000">(Early Accept).</font><br />  


### Scientific Report: 
   
+ 3D Dense Face Alignment with Fused Features by Aggregating CNNs and GCNs    
**Yanda Meng**, Xu Chen, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Yihong Qiao, Xiaowei Huang, Yalin Zheng  
Arxiv [paper](https://arxiv.org/abs/2203.04643).  

  
  
***
***
***
***

# All publications  

2023    
+ Weakly supervised segmentation with point annotations for histopathology images via contrast-based variational model  
Hongrun Zhang, Liam Burrows, **Yanda Meng**, Declan Sclthorpe, Abhik Mukherjee, Sarah E Coupland, Ke Chen, Yalin Zheng.  
IEEE Conference on Computer Vision and Pattern Recognition.   
**CVPR 2023** (accept rate: 25.8%, 9155 submissions) [paper](), [code]().  

+ Artificial Intelligence Based Analysis of Corneal Confocal Microscopy Images for Diagnosing Peripheral Neuropathy: A Binary Classification Model  
***Yanda Meng**, *Frank G Preston, Maryam Ferdousi, Shazli Azmi, Ioannis Nikolaos Petropoulos, Stephen Kaye, Rayaz Ahmed Malik, Uazman Alam, Yalin Zheng.  
**Journal of Clinical Medicine (IF: ~4.964)** [paper]().  

+ Bilateral Adaptive Graph Convolutional Network on CT based COVID-19 Diagnosis with Uncertainty-Aware Consensus-Assisted Multiple Instance Learning Medical Image Analysis  
**Yanda Meng**, Joshua Bridge, Cliff Addison, Manhui Wang, Cristin Merritt, Stu Franks, Maria Mackey, Steve Messenger, Renrong Sun, Qiang Li, Yitian Zhao, Yalin Zheng.  
**Medical Image Analysis (IF:~ 13.828)** [paper](https://www.sciencedirect.com/science/article/pii/S1361841522003504?dgcid=rss_sd_all), [code](https://github.com/smallmax00/BAGCN-Covid19).  

2022
+ Transportation Object Counting with Graph-Based Adaptive Auxiliary Learning  
**Yanda Meng**, Joshua Bridge, Yitian Zhao, Joddrell Martha, Yihong Qiao, Xiaoyun Yang, Xiaowei Huang, Yalin Zheng.  
**IEEE Transactions on Intelligent Transportation System (IF: ~9.551)**  [paper](), [code](https://github.com/smallmax00/Counting_With_Adaptive_Auxiliary_Learning).  

+ Artificial Intelligence and Corneal Confocal Microscopy: the start of a beautiful relationship  
Uazman Alam, Matthew Anson, **Yanda Meng**, Frank Preston, Varo Kirthi, Timothy L. Jackson, Paul Nderitu, Daniel J. Cuthbertson, Rayaz Malik, Yalin Zheng, Ioannis N. Petropoulos.  
**Journal of Clinical Medicine (IF: ~4.964)** [paper](https://www.mdpi.com/2077-0383/11/20/6199).  


+ Dual Consistency Enabled Weakly and Semi-Supervised Optic Disc and Cup Segmentation with Dual Adaptive Graph Convolutional Networks  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Dongxu Gao, Barbra Hamill, Godhuli Patri, Tunde Peto, Savita Madhusudhan, and Yalin Zheng.  
**IEEE Transactions on Medical Imaging (IF: ~11.037)** [paper](https://ieeexplore.ieee.org/document/9870838), [code](https://github.com/smallmax00/Dual_Adaptive_Graph_Reasoning).  

+ Automatically Segment the Left Atrium and Scars from LGE-MRIs Using a Boundary-focused nnU-Net  
Yuchen Zhang, **Yanda Meng**, Yalin Zheng   
In The Left Atrial and Scar Quantification & Segmentation Challenge. LAScarQS 2022 (MICCAI 2022 Workshop) [paper](), [code](). <font color="#dd0000">(Best Paper Runner-Up).</font><br />  

+ Shape-Aware Weakly/Semi-Supervised Optic Disc and Cup Segmentation with Regional/Marginal Consistency  
**Yanda Meng**, Xu Chen, Hongrun Zhang, Yitian Zhao, Dongxu Gao, Barbra Hamill, Godhuli Patri, Tunde Peto, Savita Madhusudhan, Yalin Zheng  
International Conference on Medical Image Computing and Computer-Assisted Intervention.  
**MICCAI 2022** (early accept rate: 13.0%, 1825 submissions) [paper](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_50), [code](https://github.com/smallmax00/Shape_aware_Weakly-Semi_ODOC_seg). <font color="#dd0000">(Early Accept).</font><br />  

+ Diagnosis of Diabetic Neuropathy by Artificial Intelligence using Corneal Confocal Microscopy  
**Yanda Meng**, Maryam Ferdousi, Ioannis N Petropoulos, Rayaz A Malik, Yitian Zhao, Uazman Alam, Yalin Zheng  
32nd Meeting of the European Association for Diabetic Eye Complications  
**EAsDEC2022** [paper](https://journals.sagepub.com/doi/pdf/10.1177/11206721221092575)  

+ 3D Human Pose and Shape Reconstruction from Videos via Confidence-Aware Temporal Feature Aggregation  
Hongrun Zhang, **Yanda Meng**, Yitian Zhao, Xuesheng Qian, Yihong Qiao, Xiaoyun Yang, and Yalin Zheng  
IEEE Transaction on Multimedia (IF:~8.182). [paper](https://ieeexplore.ieee.org/document/9759982), [code](https://github.com/hrzhang1123/Confidence-Aware-Video-Pose-Estimation)

+ DTFD-MIL: Double-Tier Feature Distillation Multiple Instance Learning for Histopathology Whole Slide Image Classification  
Hongrun Zhang, **Yanda Meng**, Yitian Zhao, Yihong Qiao, Xiaoyun Yang, Sarah Coupland, and Yalin Zheng  
IEEE Conference on Computer Vision and Pattern Recognition.   
CVPR 2022 Oral. (oral accept rate: 4%, 8161 submissions) [paper](https://arxiv.org/abs/2203.12081), [code](https://github.com/hrzhang1123/DTFD-MIL). <font color="#dd0000">(Oral).</font><br />

+ Informed Consent In Facial Photograph Publishing: A Cross-sectional Pilot Study To Determine The Effectiveness Of Deidentification Methods  
Frank G Preston, **Yanda Meng**, Yalin Zheng, James Hsuan, Kevin J Hamill, and Austin G McCormick.    
Journal of Empirical Research on Human Research Ethics (IF: ~1.742). [paper](https://journals.sagepub.com/doi/10.1177/15562646221075459).  

2021
+ BI-GCN: Boundary-Aware Input-Dependent Graph Convolution Network for Biomedical Image Segmentation  
**Yanda Meng**, Hongrun Zhang, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xuesheng Qian, Xiaowei Huang, and Yalin Zheng.  
The British Machine Vision Conference.  
**BMVC 2021 Oral** (Oral accept rate: 3.3%, 1206 submissions) [paper](https://arxiv.org/abs/2110.14775#), [code](https://github.com/smallmax00/BI-GConv).

+ Graph-based Region and Boundary Aggregation for Biomedical Image Segmentation  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Xiaoyun Yang, Yihong Qiao, Ian J. C. MacCormick, Xiaowei Huang, and Yalin Zheng.  
**IEEE Transcations on Medical Imaging (IF: ~10.048)** [paper](https://ieeexplore.ieee.org/document/9594842), [code](https://github.com/smallmax00/Graph_Region_Boudnary).


+ Artificial intelligence utilising corneal confocal microscopy for the diagnosis of peripheral neuropathy in diabetes mellitus and prediabetes  
*Frank G Preston, ***Yanda Meng**, Jamie Burgess, Maryam Ferdousi, Shazli Azmi, Ioannis N Petropoulos, Stephen Kaye, Rayaz A Malik, Yalin Zheng, Uazman Alam. **Diabetologia (IF: ~10.122)** [paper](https://link.springer.com/content/pdf/10.1007/s00125-021-05617-x.pdf).


+ Spatial Uncertainty-Aware Semi-Supervised Crowd Counting  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Xiaoyun Yang, Xuesheng Qian, Xiaowei Huang, and Yalin Zheng.      
IEEE International Conference on Computer Vision.
**ICCV 2021** (accept rate: 25.9%, 6236 submissions). [paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Meng_Spatial_Uncertainty-Aware_Semi-Supervised_Crowd_Counting_ICCV_2021_paper.pdf), [code](https://github.com/smallmax00/SUA_crowd_counting).  

+ TransBridge: A lightweight transformer for left ventricle segmentation in echocardiography  
Kaizhong Deng, **Yanda Meng**, Dongxu Gao, Joshua Bridge, Yaochun Shen, Gregory Lip, Yitian Zhao, Yalin Zheng.  
In The 2nd International Workshop of Advances in Simplifying Medical UltraSound. ASMUS 2021 (MICCAI 2021 Workshop) [paper](https://link.springer.com/chapter/10.1007/978-3-030-87583-1_7).  

+ Learning Parameter-specific Affine Transformation for Medical Images Registration  
Xu Chen, **Yanda Meng**, Yitian Zhao, Rachel Williams, Srinivasa Vallabhaneni, Yalin Zheng.  
In International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI 2021). [paper](https://link.springer.com/chapter/10.1007/978-3-030-87202-1_3), [code](https://github.com/xuuuuuuchen/PASTA).  

+ A regularization term for slide correlation reduction in whole slide image analysis with deep learning  
Hongrun Zhang, **Yanda Meng**, Xuesheng Qian, Xiaoyun Yang, Sarah E.Coupland, and Yalin Zheng.  
In Medical Imaging with Deep Learning (MIDL), 2021. (MIDL 2021) [paper](https://openreview.net/forum?id=2vCFIoWDS6E),  [code](https://github.com/hrzhang1123/SlideCorrelationReduction).  





2020  
+ Regression of Instance Boundary by Aggregated CNN and GCN  
**Yanda Meng**, Meng wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
European Conference on Computer Vision.  
**ECCV2020** (accept rate: 26.0%, 5150 submissions). [paper](https://link.springer.com/chapter/10.1007/978-3-030-58598-3_12).  

+ CNN-GCN Aggregation Enabled Boundary Regression for Biomedical Image Segmentation  
**Yanda Meng**, Meng Wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
International Conference on Medical Image Computing and Computer-Assisted Intervention.  
**MICCAI 2020** (early accept rate: 13.3%, 1809 submissions). [paper](https://link.springer.com/chapter/10.1007/978-3-030-59719-1_35)

+ Introducing the GEV Activation Function for Highly Unbalanced Data to Develop COVID-19 Diagnostic Models.  
Bridge, Joshua, **Yanda Meng**, Yitian Zhao, Yong Du, Mingfeng Zhao, Renrong Sun, and Yalin Zheng.  
IEEE Journal of Biomedical and Health Informatics 24, no. 10 (IEEE-JBHI, IF: 5.772) 2020: 2776-2786. [paper](https://ieeexplore.ieee.org/document/9151288), [code](https://github.com/JTBridge/GEV).  











