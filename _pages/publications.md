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
+ StealthMark: Harmless and Stealthy Ownership Verification for Medical Segmentation via Uncertainty-Guided Backdoors  
Qinkai Yu, Chong Zhang,  Gaojie Jin, Tianjin Huang, Wei Zhou, Wenhui Li, Xiaobo Jin, Bo Huang, Yitian Zhao, Guang Yang, Gregory Y.H. Lip, Yalin Zheng, Aline Villavicencio, **Yanda Meng<sup>†</sup>**  
**IEEE Transactions on Image Processing (2026 IF: ~13.7, SCI 1区)** [paper](), [code]().  

+ Multi-Granularity Learning of Explicit Geometric Constraint and Contrast for Label-Efficient Medical Image Segmentation and Differentiable Clinical Function Assessment  
**Yanda Meng**, Yuchen Zhang, Jianyang Xie, Jinming Duan, Martha Joddrell, Savita Madhusudhan, Tunde Peto, Yitian Zhao, Yalin Zheng.  
**Medical Image Analysis (2024, IF:~ 10.9, SCI 1 区)** [paper](https://www.sciencedirect.com/science/article/pii/S1361841524001087), [code](https://github.com/smallmax00/Multi_Granularity_Segmentation_Clinical_Function_Assessment)  
+ Bilateral Adaptive Graph Convolutional Network on CT based COVID-19 Diagnosis with Uncertainty-Aware Consensus-Assisted Multiple Instance Learning   
**Yanda Meng**, Joshua Bridge, Cliff Addison, Manhui Wang, Cristin Merritt, Stu Franks, Maria Mackey, Steve Messenger, Renrong Sun, Thomas Fitzmaurice, Caroline McCann, Qiang Li, Yitian Zhao, Yalin Zheng.  
**Medical Image Analysis (2023 IF:~ 13.828, SCI 1区)** [paper](https://www.sciencedirect.com/science/article/pii/S1361841522003504?dgcid=rss_sd_all), [code](https://github.com/smallmax00/BAGCN-Covid19).
  
+ Dual Consistency Enabled Weakly and Semi-Supervised Optic Disc and Cup Segmentation with Dual Adaptive Graph Convolutional Networks  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Dongxu Gao, Barbra Hamill, Godhuli Patri, Tunde Peto, Savita Madhusudhan, and Yalin Zheng.  
**IEEE Transactions on Medical Imaging (2022 IF: ~11.037, SCI 1区)** [paper](https://ieeexplore.ieee.org/document/9870838), [code](https://github.com/smallmax00/Dual_Adaptive_Graph_Reasoning).  

+ Graph-based Region and Boundary Aggregation for Biomedical Image Segmentation  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Xiaoyun Yang, Yihong Qiao, Ian J. C. MacCormick, Xiaowei Huang, and Yalin Zheng.  
**IEEE Transactions on Medical Imaging (2021 IF: ~10.048, SCI 1区)** [paper](https://ieeexplore.ieee.org/document/9594842), [code](https://github.com/smallmax00/Graph_Region_Boudnary).  

+ Artificial intelligence utilising corneal confocal microscopy for the diagnosis of peripheral neuropathy in diabetes mellitus and prediabetes  
*Frank G Preston, ***Yanda Meng**, Jamie Burgess, Maryam Ferdousi, Shazli Azmi, Ioannis N Petropoulos, Stephen Kaye, Rayaz A Malik, Yalin Zheng, Uazman Alam.  
**Diabetologia (2021 IF: ~10.122, SCI 1区)** [paper](https://link.springer.com/content/pdf/10.1007/s00125-021-05617-x.pdf). <font color="#dd0000">(封面文章，Front Cover of Mar 2022 Issue).</font><br />  

+ Transportation Object Counting with Graph-Based Adaptive Auxiliary Learning  
**Yanda Meng**, Joshua Bridge, Yitian Zhao, Joddrell Martha, Yihong Qiao, Xiaoyun Yang, Xiaowei Huang, Yalin Zheng.  
**IEEE Transactions on Intelligent Transportation System (2022 IF: ~9.551, SCI 1区)**  [paper](https://ieeexplore.ieee.org/abstract/document/9990574), [code](https://github.com/smallmax00/Counting_With_Adaptive_Auxiliary_Learning).

+ Artificial intelligence – based classification of cardiac autonomic neuropathy from retinal fundus images in patients with diabetes - The Silesia Diabetes Heart Study  
*Katarzyna Nabrdalik, *Krzysztof Irlik, ***Yanda Meng**, Hanna Kwiendacz, Julia Piaśnik, Mirela Hendel, Paweł Ignacy, Justyna Kulpa, Kamil Kegler, Mikołaj Herba, Sylwia Boczek, Effendy Bin Hashim, Zhuangzhi Gao, Janusz Gumprecht, Yalin Zheng, Gregory Y.H. Lip, Uazman Alam.  
**Cardiovascular Diabetology (2024 IF: ~8.5, SCI 1 区)** [paper](https://cardiab.biomedcentral.com/articles/10.1186/s12933-024-02367-z).  

+ Self-Guided Adversarial Network for Domain Adaptive Retinal Layer Segmentation  
Jiong Zhang, Chenggang Lu, Ran Song, Yalin Zheng, Huaying Hao, **Yanda Meng<sup>†</sup>**, Yitian Zhao<sup>†</sup>.   
**IEEE Transactions on Instrumentation & Measurement. (2024 IF: ~5.6, SCI 2 区 )** [paper]()    

+ Artificial Intelligence Based Analysis of Corneal Confocal Microscopy Images for Diagnosing Peripheral Neuropathy: A Binary Classification Model  
***Yanda Meng**, *Frank G Preston, Maryam Ferdousi, Shazli Azmi, Ioannis Nikolaos Petropoulos, Stephen Kaye, Rayaz Ahmed Malik, Uazman Alam, Yalin Zheng.  
**Journal of Clinical Medicine (2023 IF: ~4.964, SCI 2区)** [paper](https://www.mdpi.com/2077-0383/12/4/1284).  

+ Deep-learning using preoperative AS-OCT predicts graft detachment in DMEK  
*Alastair Patefield, ***Yanda Meng**, Matteo Airaldi, Giulia Coco, Sabrina Vaccaro, Mohit Parekh, Francesco Semeraro, Kunal A Gadhvi, Stephen B Kaye, Yalin Zheng, Vito Romano  
**Translational Vision Science and Technology (2023 IF: ~3.048, SCI 3区)** [paper](https://tvst.arvojournals.org/article.aspx?articleid=2785617)  


### Conferences  
+ Fairness-Aware vCDR-Controlled Generation for Glaucoma Diagnosis  
Ziheng Wang, Shuran Yang, Wen Chen, Zhen Zhang, Mengyu Wang, Feixiang Zhou, Yu Tian, Meng Wang, Yitian Zhao, Yalin Zheng, **Yanda Meng<sup>†</sup>**  
International Conference on Medical Image Computing and Computer-Assisted Intervention  
**MICCAI 2025** (CCF-B) [paper](), [code]()  
  
+ Parameterized Diffusion Optimization enabled Autoregressive Ordinal Regression for Diabetic Retinopathy Grading  
Qinkai Yu, Wei Zhou, Hantao Liu, Yanyu Xu, Meng Wang, Yitian Zhao, Huazhu Fu, Xujiong Ye, Yalin Zheng, **Yanda Meng<sup>†</sup>**  
International Conference on Medical Image Computing and Computer-Assisted Intervention  
**MICCAI 2025** (CCF-B) [paper](), [code]() <font color="#dd0000">(Oral).</font><br />  

+ Robust Incomplete-Modality Alignment for Ophthalmic Disease Grading and Diagnosis via Labeled Optimal Transport  
Qinkai Yu, Jianyang Xie, Yitian Zhao, Cheng Chen, Lijun Zhang, Liming Chen, Jun Cheng, Lu Liu, Yalin Zheng, **Yanda Meng<sup>†</sup>**  
International Conference on Medical Image Computing and Computer-Assisted Intervention  
**MICCAI 2025** (CCF-B) [paper](), [code]()  

+ Self-adaptive Vision-Language Model for 3D Segmentation of Pulmonary Artery and Vein  
Deqian Yang, Xiaotong Guo, Ying Zhu, Dan Wang, Haochen Zhao, Yuan Li, Zhilin Sui, Tao Zhou, Hui Meng, Lijun Zhang, **Yanda Meng<sup>†</sup>**    
International Conference on Medical Image Computing and Computer-Assisted Intervention  
**MICCAI 2025** (CCF-B) [paper](), [code]()  

+ Incomplete Modality Disentangled Representation for Ophthalmic Disease Grading and Diagnosis  
Chengzhi Liu, Zile Huang, Zhe Chen, Feilong Tang, Yu Tian, Zhongxing Xu, Zihong Luo, Yalin Zheng, **Yanda Meng<sup>†</sup>**  
39th AAAI Conference on Artificial Intelligence.  
**AAAI 2025** (CCF-A) [paper](), [code](), [project link](https://imdr-aaai.github.io/) <font color="#dd0000">(Oral).</font><br />  
  
+ CLIP-DR: Textual Knowledge-Guided Diabetic Retinopathy Grading with Ranking-aware Prompting  
Qinkai Yu, Jianyang Xie, Anh Nguyen, He Zhao, Jiong Zhang, Huazhu Fu, Yitian Zhao, Yalin Zheng, **Yanda Meng<sup>†</sup>**  
International Conference on Medical Image Computing and Computer-Assisted Intervention.  
**MICCAI 2024** (CCF-B) [paper](), [code]()  

+ Dynamic Semantic-based Graph Convolution Network for Skeleton-based Human Action Recognition  
Jianyang Xie, **Yanda Meng<sup>†</sup>**, Yitian Zhao, Anh Nguyen, Xiaoyun Yang, Yalin Zheng<sup>†</sup>  
Thirty-Eighth AAAI Conference on Artificial Intelligence  
**AAAI 2024** (CCF-A) [paper](https://ojs.aaai.org/index.php/AAAI/article/view/28440),  [code](https://github.com/davelailai/DS-GCN).  

+ Weakly/Semi-supervised Left Ventricle Segmentation in 2D Echocardiography with Uncertain Region-aware Contrastive Learning  
***Yanda Meng**, *Yuchen Zhang, Jianyang Xie, Jinming Duan, Yitian Zhao, Yalin Zheng  
Chinese Conference on Pattern Recognition and Computer Vision.  
**PRCV 2023** (CCF-C) [paper](), [code]().  


+ Shape-Aware Weakly/Semi-Supervised Optic Disc and Cup Segmentation with Regional/Marginal Consistency  
**Yanda Meng**, Xu Chen, Hongrun Zhang, Yitian Zhao, Dongxu Gao, Barbra Hamill, Godhuli Patri, Tunde Peto, Savita Madhusudhan, Yalin Zheng  
International Conference on Medical Image Computing and Computer-Assisted Intervention.  
**MICCAI 2022** (CCF-B) [paper](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_50), [code](https://github.com/smallmax00/Shape_aware_Weakly-Semi_ODOC_seg). <font color="#dd0000">(Early Accept).</font><br />  

+ Diagnosis of Diabetic Neuropathy by Artificial Intelligence using Corneal Confocal Microscopy  
**Yanda Meng**, Maryam Ferdousi, Ioannis N Petropoulos, Rayaz A Malik, Yitian Zhao, Uazman Alam, Yalin Zheng  
32nd Meeting of the European Association for Diabetic Eye Complications  
**EAsDEC2022** [paper](https://journals.sagepub.com/doi/pdf/10.1177/11206721221092575)  

+ BI-GCN: Boundary-Aware Input-Dependent Graph Convolution Network for Biomedical Image Segmentation  
**Yanda Meng**, Hongrun Zhang, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xuesheng Qian, Xiaowei Huang, and Yalin Zheng.  
The British Machine Vision Conference.  
**BMVC 2021** (CCF-C) [paper](https://www.bmvc2021-virtualconference.com/assets/papers/0097.pdf), [code](https://github.com/smallmax00/BI-GConv). <font color="#dd0000">(Oral, selected as one of the best papers of BMVC2021 and invited to extend a journal version in Special Issue of IJCV).</font><br />  

+ Spatial Uncertainty-Aware Semi-Supervised Crowd Counting  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Xiaoyun Yang, Xuesheng Qian, Xiaowei Huang, and Yalin Zheng.      
IEEE International Conference on Computer Vision.  
**ICCV 2021** (CCF-A) [paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Meng_Spatial_Uncertainty-Aware_Semi-Supervised_Crowd_Counting_ICCV_2021_paper.pdf), [code](https://github.com/smallmax00/SUA_crowd_counting).   

+ Regression of Instance Boundary by Aggregated CNN and GCN  
**Yanda Meng**, Meng wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
European Conference on Computer Vision.  
**ECCV 2020** (CCF-B) [paper](https://link.springer.com/chapter/10.1007/978-3-030-58598-3_12).   

+ CNN-GCN Aggregation Enabled Boundary Regression for Biomedical Image Segmentation  
**Yanda Meng**, Meng Wei, Dongxu Gao, Yitian Zhao, Xiaoyun Yang, Xiaowei Huang, and Yalin Zheng.  
International Conference on Medical Image Computing and Computer-Assisted Intervention.  
**MICCAI 2020** (CCF-B) [paper](https://link.springer.com/chapter/10.1007/978-3-030-59719-1_35) <font color="#dd0000">(Early Accept).</font><br />  









