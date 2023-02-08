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

### 2023

1. **Multi-organ segmentation: a progressive exploration of learning paradigms under scarce annotation**
Shiman Li, **Haoran Wang**, Yucong Meng, Chenxi Zhang, Zhijian Song
*arXiv preprint*, 2023


### 2022
4. **EndoBoost: a plug-and-play module for false positive suppression during computer-aided polyp detection in real-world colonoscopy (with dataset)**  
**Haoran Wang<sup>\*</sup>**, Yan Zhu<sup>\*</sup>, Wenzheng Qin<sup>\*</sup>, Yizhe Zhang, Pinghong Zhou, Quanlin Li, [Shuo Wang](https://swang.miccai.cloud/), Zhijian Song 
*arXiv preprint*, 2022

3. **The Extreme Cardiac MRI Analysis Challenge under Respiratory Motion (CMRxMotion)**  
Shuo Wang, Chen Qin, Chengyan Wang, Kang Wang, **Haoran Wang**, Chen Chen, Cheng Ouyang, Xutong Kuang, Chengliang Dai, Yuanhan Mo, Zhang Shi, Chenchen Dai, Xinrong Chen, He Wang, Wenjia Bai
*arXiv preprint*, 2022      

2. **Quality-Aware Model Ensemble for Brain Tumor Segmentation**
Kang Wang<sup>\*</sup>, **Haoran Wang<sup>\*</sup>**, Zeyang Li, Mingyuan Pan, Manning Wang, Shuo Wang, Zhijian Song
*MICCAI BrainLes*, 2022

1. **Prediction model of hemorrhage transformation in patient with acute ischemic stroke based on multiparametric MRI radiomics and machine learning**
Yucong Meng<sup>\*</sup>, **Haoran Wang<sup>\*</sup>**, Chuanfu Wu<sup>\*</sup>, Xiaoyu Liu, Linhao Qu, Yonghong Shi
*Brain Sciences* (IF = 3.333), 2022