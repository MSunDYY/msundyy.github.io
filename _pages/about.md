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
# 🙋 About Me
I am currently a second-year master's student at the School of Artificial Intelligeence and Automation (AIA), Huazhong 
Univerversity of Science and Technology (HUST). I was conferred the Bachelor's degree by AIA in June 2024. 

Since March 2025, I have been a research intern at the Institute for AI Industry Research (AIR), Tsinghua University, under the supervision of [Yan Wang](https://scholar.google.com/citations?user=QOZnsYYAAAAJ&hl=zh-CN).
Since July 2025, I have been an intern at the Autonomous Driving and Robotics Department of Xiaomi EV, supervised by [Long Chen](https://scholar.google.com/citations?user=c-sthYIAAAAJ&hl=zh-CN) and [Yan Wang](https://scholar.google.com/citations?user=QOZnsYYAAAAJ&hl=zh-CN).

My research interests include multimodal large language models (MLLM), reinforcement learning, world models, and their applications in end-to-end autonomous driving. Looking ahead, I plan to shift toward general multimodal understanding and generation. I welcome discussions and potential collaborations.

# 💖 Research Interests
- Multi-Modal Large Language Model
- Reinforcement Learning
- E2E Autonomous Driving

# 🔥 News
- *2026.02*  &nbsp; We release the [paper](https://arxiv.org/abs/2602.14577) of **DriveFine** that investigates dLLM+RL with refinement for AD. 
- *2026.01*  &nbsp; We release the [paper](https://arxiv.org/abs/2601.06474) and [code](https://github.com/MSunDYY/SparseOccVLA) of **SparseOccVLA** that effectively integrates occupancy with VLMs via sparse queries.
- *2025.10*  &nbsp; We release the [paper](https://arxiv.org/abs/2510.17482) and [code](https://github.com/MSunDYY/SparseWorld) of **SparseWorld**, an efficient occupancy world model powered by sparse queries. 
- *2025.11*: &nbsp;🎉🎉 One paper accepted by **AAAI2026**!
- *2025.02*: &nbsp;🎉🎉 Two of our papers are accepted by **CVPR2025**! 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/drivefine.png' 
alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
DriveFine: Refining-Augmented Masked Diffusion VLA for Precise and Robust Driving

**Chenxu Dang**, Sining Ang, Yongkang Li, Haochen Tian, Jie Wang, Guang Li, Hangjun Ye, Jie Ma, Long Chen*, Yan Wang*

[**Paper**](https://arxiv.org/abs/2602.14577)  [**Code**](https://github.com/MSunDYY/DriveFine) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/sparseoccvla.png' 
alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
SparseOccVLA: Bridging Occupancy and Vision-Language Models via Sparse Queries for Unified 4D Scene Understanding and Planning

**Chenxu Dang**, Jie Wang, Guang Li, Zhiwen Hou, Zihan You, Hangjun Ye, Jie Ma, Long Chen*, Yan Wang*

[**Paper**](https://arxiv.org/abs/2601.06474)  [**Code**](https://github.com/MSunDYY/SparseOccVLA)  [**Project**](https://msundyy.github.io/SparseOccVLA/)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/sparseworld.png' 
alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
SparseWorld: A Flexible, Adaptive, and Efficient 4D Occupancy World Model
Powered by Sparse and Dynamic Queries

**Chenxu Dang**, Haiyan Liu, Jason Bao, Pei An, Xinyue Tang, PanAn, Jie Ma*, Bingchuan Sun*, Yan Wang*

[**Paper**](https://arxiv.org/abs/2510.17482)  [**Code**](https://github.com/MSunDYY/SparseWorld) 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/faster.png' 
alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
FASTer: Focal Token Acquiring-and-Scaling Transformer for Long-term 3D Object Detection

**Chenxu Dang**, Zaipeng Duan, Pei An, Xinmin Zhang, Xuzhong Hu, Jie Ma*

[**Paper**](https://arxiv.org/abs/2503.01899)  [**Code**](https://github.com/MSunDYY/FASTer) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/sgdocc.png' 
alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
SDGOCC: Semantic and Depth-Guided Bird’s-Eye View Transformation for 3D Multimodal Occupancy Prediction

Zaipeng Duan, **Chenxu Dang**, Pei An, Xuzhong Hu, Jie Zhan, Jie Ma*

[**Paper**](https://openaccess.thecvf.com/content/CVPR2025/papers/Duan_SDGOCC_Semantic_and_Depth-Guided_Birds-Eye_View_Transformation_for_3D_Multimodal_CVPR_2025_paper.pdf)  [**Code**](https://github.com/DzpLab/SDGOCC) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/hybriddrivevla.png' 
alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
From Representational Complementarity to Dual Systems: Synergizing VLM and Vision-Only Backbones for End-to-End Driving

Sining Ang, Yuguang Yang, **Chenxu Dang**, Canyu Chen, Cheng Chi, Haiyan Liu, Xuanyao Mao, Jason Bao, Xuliang, Bingchuan Sun, Yan Wang*

[**Paper**](https://arxiv.org/abs/2602.10719)
</div>
</div>


# 🎖 Honors and Awards
- *2024.10* First Class Scholarship
- *2022.11* FiberHome Scholarship
- *2022.10* Merit Student Scholarship.


# 📖 Educations
- *2024.09 - Present*, Huazhong University of Science and Technology (Master Student).
- *2020.09 - 2024.06*, Huazhong University of Science and Technology (Undergraduate Student).

# 🚀 Internships
- *2025.07 - Present*, Autonomous Driving and Robotics Department of Xiaomi EV (Beijing).
- *2025.03 - Present*, Institute for AI Industry Research (AIR), Tsinghua University.



