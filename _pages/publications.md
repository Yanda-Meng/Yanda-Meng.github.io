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



  
***
***
***
***

# All publications  

2025  
+ Are Spatial-Temporal Graph Convolution Networks for Human Action Recognition Over-Parameterized ?  
Jianyang Xie, Yitian Zhao, **Yanda Meng**, He Zhao, Anh Nguyen, Yalin Zheng.  
IEEE Conference on Computer Vision and Pattern Recognition.   
CVPR 2025 (accept rate: 22.1%, 13,008 submissions) [paper](), [code]().  

+ Incomplete Modality Disentangled Representation for Ophthalmic Disease Grading and Diagnosis  
Chengzhi Liu, Zile Huang, Zhe Chen, Feilong Tang, Yu Tian, Zhongxing Xu, Zihong Luo, Yalin Zheng, **Yanda Meng<sup>†</sup>**  
39th AAAI Conference on Artificial Intelligence.  
**AAAI 2025** (CCF-A) [paper](), [code](), [project link](https://imdr-aaai.github.io/) <font color="#dd0000">(Oral).</font><br />  

+ Exploring Concept Depth: How Large Language Models Acquire Knowledge at Different Layers.
Mingyu Jin, Qinkai Yu, Jingyuan Huang, Qingcheng Zeng, Zhenting Wang, Wenyue Hua, Haiyan Zhao, Kai Mei, **Yanda Meng**, Kaize Ding, Fan Yang, Mengnan Du, Yongfeng, Zhang.  
International Conference on Computational Linguistics  
COLING 2025 (CCF B)  

2024  


+ Dynamic Semantic-based Spatial-Temporal Graph Convolution Network for Skeleton-based Human Action Recognition  
Jianyang Xie, **Yanda Meng**, Yitian Zhao, Anh Nguyen, Xiaoyun Yang, Yalin Zheng  
IEEE Transactions on Image Processing (IEEE-TIP, 2024 IF: 10.8, SCI 1 区)

+ Randomness-restricted Diffusion Model for Ocular Surface Structure Segmentation
Xinyu Guo, Han Wen, Huaying Hao, Yifan Zhao, **Yanda Meng**, Jiang Liu, Yalin Zheng, Wei Chen and Yitian Zhao
IEEE Transactions on Medical Imaging （IEEE-TMI, 2024 IF: 8.9, SCI 1 区）

+ Clinical Insight-Augmented Multi-View Learning for Alzheimer’s Detection in Retinal OCTA Images.  
Yuandi Zhang, Jinkui Hao, Yonghuai Liu, **Yanda Meng**, Jiong Zhang, Yang Chen, and Yitian Zhao.  
IEEE International Conference on Bioinformatics and Biomedicine (IEEE BIBM 2024, CCF B).  

+ MR2 -Net: Retinal OCTA Image Stitching via Multi-Scale Representation Learning and Dynamic Location Guidance  
Haiting Mao, Yuhui Ma, Dan Zhang, **Yanda Meng**, Shaodong Ma, Yuchuan Qiao, Huazhu Fu, Caifeng Shan, Da Chen, Yitian Zhao, Jiong Zhang.  
IEEE Journal of Biomedical and Health Informatics. (IEEE-JBHI，2024 IF: 7.1，SCI 1区).  

+ Artificial intelligence-based classification of cardiac autonomic neuropathy from retinal fundus images in patients with diabetes - The Silesia Diabetes Heart Study  
*Katarzyna Nabrdalik, *Krzysztof Irlik, ***Yanda Meng**, Hanna Kwiendacz, Julia Piaśnik, Mirela Hendel, Paweł Ignacy, Justyna Kulpa, Kamil Kegler, Mikołaj Herba, Sylwia Boczek, Effendy Bin Hashim, Zhuangzhi Gao, Janusz Gumprecht, Yalin Zheng, Gregory Y.H. Lip, Uazman Alam.    
**Cardiovascular Diabetology (2024 IF: ~8.5, SCI 1 区)** [paper]().  

+ Self-Guided Adversarial Network for Domain Adaptive Retinal Layer Segmentation  
Jiong Zhang, Chenggang Lu, Ran Song, Yalin Zheng, Huaying Hao, **Yanda Meng<sup>†</sup>**, Yitian Zhao<sup>†</sup>.   
**IEEE Transactions on Instrumentation & Measurement. (2024 IF: ~5.6, SCI 2 区 )** [paper]()    

+ AI-Driven Generalised Polynomial Transformation Models for Unsupervised Fundus Image Registration   
Xu Chen, Xiaochen Fan, **Yanda Meng**, Yalin Zheng  
Frontiers in Medicine, Ophthalmology (2024, IF: 3.1) [paper]()  

+ CLIP-DR: Textual Knowledge-Guided Diabetic Retinopathy Grading with Ranking-aware Prompting  
Qinkai Yu, Jianyang Xie, Anh Nguyen, He Zhao, Jiong Zhang, Huazhu Fu, Yitian Zhao, Yalin Zheng, **Yanda Meng<sup>†</sup>**    
International Conference on Medical Image Computing and Computer-Assisted Intervention.  
**MICCAI 2024** (CCF-B) [paper](), [code]()  

+ Multi-disease Detection in Retinal Images Guided by Disease Causal Estimation  
Jianyang xie, Xiuju Chen, Yitian Zhao, **Yanda Meng**, He Zhao, Anh Nguyen, Xiaoxin Lin, Yalin Zheng  
International Conference on Medical Image Computing and Computer-Assisted Intervention.  
MICCAI 2024 (CCF-B) [paper](), [code]()  
  
+ The Impact of Reasoning Step Length on Large Language Models.  
Mingyu Jin, Qingkai Yu, Dong Shu, Haiyan Zhao, Wenyue Hua, **Yanda Meng**, Yongfeng Zhang, Mengnan Du.  
ACL 2024 (CCF A) [paper](https://arxiv.org/abs/2401.04925), [code](https://github.com/MingyuJ666/The-Impact-of-Reasoning-Step-Length-on-Large-Language-Models).  

+ Multi-Granularity Learning of Explicit Geometric Constraint and Contrast for Label-Efficient Medical Image Segmentation and Differentiable Clinical Function Assessment  
**Yanda Meng**, Yuchen Zhang, Jianyang Xie, Jinming Duan, Martha Joddrell, Savita Madhusudhan, Tunde Peto, Yitian Zhao, Yalin Zheng.  
**Medical Image Analysis (2024, IF:~ 10.9, SCI 1 区)** [paper](https://www.sciencedirect.com/science/article/pii/S1361841524001087), [code](https://github.com/smallmax00/Multi_Granularity_Segmentation_Clinical_Function_Assessment)
  
+ Dynamic Semantic-based Graph Convolution Network for Skeleton-based Human Action Recognition  
Jianyang Xie, **Yanda Meng<sup>†</sup>**, Yitian Zhao, Anh Nguyen, Xiaoyun Yang, Yalin Zheng<sup>†</sup>  
Thirty-Eighth AAAI Conference on Artificial Intelligence  
**AAAI 2024** (CCF-A) [paper](),  [code](https://github.com/davelailai/DS-GCN).
  
2023    

+ Weakly/Semi-supervised Left Ventricle Segmentation in 2D Echocardiography with Uncertain Region-aware Contrastive Learning  
***Yanda Meng**, *Yuchen Zhang, Jianyang Xie, Jinming Duan, Yitian Zhao, Yalin Zheng  
Chinese Conference on Pattern Recognition and Computer Vision.  
**PRCV 2023** (CCF-C) [paper](), [code]().
  
+ Development and External Validation of a Mixed-Effects Deep Learning Model to Diagnose COVID-19 from CT Imaging  
Joshua Beidge, **Yanda Meng**, Wenyue Zhu, Thomas Fitzmaurice, Caroline McCann, Cliff Addison, Manhui Wang, Cristin Merritt, Stu Franks, Maria Mackey, Steve Messenger, Renrong Sun, Yitian Zhao, Yalin Zheng  
Frontiers in Medicine, section Nuclear Medicine (2023 IF: 5.058) [paper](https://www.frontiersin.org/articles/10.3389/fmed.2023.1113030/full), [code](https://github.com/JTBridge/ME-COVID19)    

+ Deep-learning using preoperative AS-OCT predicts graft detachment in DMEK  
*Alastair Patefield, ***Yanda Meng**, Matteo Airaldi, Giulia Coco, Sabrina Vaccaro, Mohit Parekh, Francesco Semeraro, Kunal A Gadhvi, Stephen B Kaye, Yalin Zheng, Vito Romano  
**Translational Vision Science and Technology (2023 IF: ~3.048)** [paper](https://pubmed.ncbi.nlm.nih.gov/37184500/)  

+ Retinal Imaging Technologies in Cerebral Malaria: A Systematic Review  
Kyle J. Wilson, Amit Dhalla, **Yanda Meng**, Zhanhan Tu, Yalin Zheng, Priscilla P. Mhango, Karl B. Seydel, Nicholas A. V. Beare  
Malaria Journal (IF: ~3.369) [paper](https://malariajournal.biomedcentral.com/articles/10.1186/s12936-023-04566-7)   

+ Weakly supervised segmentation with point annotations for histopathology images via contrast-based variational model  
Hongrun Zhang, Liam Burrows, **Yanda Meng**, Declan Sclthorpe, Abhik Mukherjee, Sarah E Coupland, Ke Chen, Yalin Zheng.  
IEEE Conference on Computer Vision and Pattern Recognition.   
CVPR 2023 (accept rate: 25.8%, 9155 submissions) [paper](https://arxiv.org/pdf/2304.03572.pdf), [code]().  

+ Artificial Intelligence Based Analysis of Corneal Confocal Microscopy Images for Diagnosing Peripheral Neuropathy: A Binary Classification Model  
***Yanda Meng**, *Frank G Preston, Maryam Ferdousi, Shazli Azmi, Ioannis Nikolaos Petropoulos, Stephen Kaye, Rayaz Ahmed Malik, Uazman Alam, Yalin Zheng.  
**Journal of Clinical Medicine (IF: ~4.964)** [paper](https://www.mdpi.com/2077-0383/12/4/1284).  

+ Bilateral Adaptive Graph Convolutional Network on CT based COVID-19 Diagnosis with Uncertainty-Aware Consensus-Assisted Multiple Instance Learning Medical Image Analysis  
**Yanda Meng**, Joshua Bridge, Cliff Addison, Manhui Wang, Cristin Merritt, Stu Franks, Maria Mackey, Steve Messenger, Renrong Sun, Thomas Fitzmaurice, Caroline McCann, Qiang Li, Yitian Zhao, Yalin Zheng.  
**Medical Image Analysis (IF:~ 13.828)** [paper](https://www.sciencedirect.com/science/article/pii/S1361841522003504?dgcid=rss_sd_all), [code](https://github.com/smallmax00/BAGCN-Covid19).  

2022
+ Transportation Object Counting with Graph-Based Adaptive Auxiliary Learning  
**Yanda Meng**, Joshua Bridge, Yitian Zhao, Joddrell Martha, Yihong Qiao, Xiaoyun Yang, Xiaowei Huang, Yalin Zheng.  
**IEEE Transactions on Intelligent Transportation System (IF: ~9.551)**  [paper](https://ieeexplore.ieee.org/document/9990574), [code](https://github.com/smallmax00/Counting_With_Adaptive_Auxiliary_Learning).  

+ Artificial Intelligence and Corneal Confocal Microscopy: the start of a beautiful relationship  
Uazman Alam, Matthew Anson, **Yanda Meng**, Frank Preston, Varo Kirthi, Timothy L. Jackson, Paul Nderitu, Daniel J. Cuthbertson, Rayaz Malik, Yalin Zheng, Ioannis N. Petropoulos.  
Journal of Clinical Medicine (IF: ~4.964) [paper](https://www.mdpi.com/2077-0383/11/20/6199).  


+ Dual Consistency Enabled Weakly and Semi-Supervised Optic Disc and Cup Segmentation with Dual Adaptive Graph Convolutional Networks  
**Yanda Meng**, Hongrun Zhang, Yitian Zhao, Dongxu Gao, Barbra Hamill, Godhuli Patri, Tunde Peto, Savita Madhusudhan, and Yalin Zheng.  
**IEEE Transactions on Medical Imaging (IF: ~11.037)** [paper](https://ieeexplore.ieee.org/document/9870838), [code](https://github.com/smallmax00/Dual_Adaptive_Graph_Reasoning).  

+ Automatically Segment the Left Atrium and Scars from LGE-MRIs Using a Boundary-focused nnU-Net  
Yuchen Zhang, **Yanda Meng**, Yalin Zheng   
In The Left Atrial and Scar Quantification & Segmentation Challenge. LAScarQS 2022 (MICCAI 2022 Workshop) [paper](https://link.springer.com/chapter/10.1007/978-3-031-31778-1_5), [code](https://github.com/level6626/Boundary-focused-nnU-Net). <font color="#dd0000">(Best Paper Runner-Up).</font><br />  

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
*Frank G Preston, ***Yanda Meng**, Jamie Burgess, Maryam Ferdousi, Shazli Azmi, Ioannis N Petropoulos, Stephen Kaye, Rayaz A Malik, Yalin Zheng, Uazman Alam.  
**Diabetologia (IF: ~10.122)** [paper](https://link.springer.com/content/pdf/10.1007/s00125-021-05617-x.pdf).


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











