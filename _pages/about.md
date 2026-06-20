---
permalink: /
title: "Juncheng Ma (马俊程)"
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

I am a first-year Master’s student at the <a href='https://www.ece.pku.edu.cn/'>School of Electronic and Computer Engineering</a>, <a href='https://english.pku.edu.cn/'>Peking University </a>, advised by Prof. <a href='https://zhoudaquan.github.io/homepage.io/index.html'>Daquan Zhou</a> and Prof. <a href='https://scholar.google.com/citations?user=fn6hJx0AAAAJ&hl=en'>Yonghong Tian </a>. I received my B.E. degree from the <a href='https://www.ucas.ac.cn/index.htm'>University of Chinese Academy of Sciences</a> (UCAS) in 2025, where I was awarded as an Outstanding Graduate. 

My current research interest centers on **world-action models (WAM)** for embodied intelligence. I am actively seeking **collaboration and internship opportunities** — feel free to reach me at <a href="mailto:junchengma25@stu.pku.edu.cn">junchengma25@stu.pku.edu.cn</a>.

# News
- *2026.06*: &nbsp;🎉🎉 One paper on SyncCache is accepted by <a href='https://eccv.ecva.net/Conferences/2026'>ECCV 2026</a>.
- ​*2025.05*: &nbsp;🎉🎉 ​I am selected as an Outstanding Graduate of Beijing, with my undergraduate thesis named an Outstanding Graduation Paper of UCAS.​
- *2024.11*: &nbsp;🎉🎉 I win the China National Scholarship and First-Level Scholarship of UCAS!
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by <a href='https://eccv2024.ecva.net/'>ECCV 2024</a>.


# Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/humanscale.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[HumanScale: Egocentric Human Video Can Outperform Real-Robot Data for Embodied Pretraining](https://arxiv.org/abs/2606.20521)**

**Juncheng Ma**\*, Jianxin Bi\*, Yufan Deng, Xuanran Zhai, Kewei Zhang, Ye Huang, Bo Liang, Shukai Gong, Jiankai Tu, Xiaotian Tang, Jiaxin Li, Kaiqi Chen, Duomin Wang, Yuqi Wang, Bingyi Kang, Eric Huang, Zhiyang Dou, Zhen Dong, Enze Xie, Wojciech Matusik, Tat-Seng Chua, Daquan Zhou

<span style="font-size:0.85em">(\* Equal contribution)</span>

<span style="color:red">**Technical Report**</span> \| [**arXiv**](https://arxiv.org/abs/2606.20521) \| [**Code**](https://github.com/DAGroup-PKU/HumanNet/)

With a carefully designed filtering and labeling pipeline, we show that egocentric human video is a scalable pretraining source for embodied foundation models that <span style="color:red">surpasses real-robot data</span>, especially in out-of-distribution generalization.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/cache.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SyncCache: Exploiting Asymmetric Dynamics for Fast Audio-Driven Portrait Animation**

**Juncheng Ma**, Yuxuan Du, Yanan SUN, Zhening Xing, Changlin Li, Zhenyu Tang, Bo Li, Peng-Tao Jiang, Li Yuan, Daquan Zhou†, Yonghong Tian† 

<span style="color:red">**ECCV 2026**</span>

We propose <span style="color:red">SyncCache</span>, a training-free caching acceleration method tailored for DiT-based portrait animation that exploits spatial and modality asymmetries, delivering up to <span style="color:red">4.12×</span> acceleration on HunyuanVideo-Avatar and <span style="color:red">3.75×</span> on Wan-S2V with near-lossless visual fidelity and precise audio alignment.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/teaser.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Stepping Stones: A Progressive Training Strategy for Audio-Visual Semantic Segmentation](https://arxiv.org/abs/2407.11820)**

**Juncheng Ma**, Peiwen Sun, Yaoting Wang, Di Hu

<span style="color:red">**ECCV 2024**</span> \| [**arXiv**](https://arxiv.org/abs/2407.11820) \| [**Code**](https://github.com/GeWu-Lab/Stepping-Stones) \| [**Project**](https://gewu-lab.github.io/stepping_stones/) \| [**PDF**](pdfs/09290.pdf) \| [**Supplementary**](pdfs/09290-supp.pdf)

Rethink audio-visual semantic segmentatoin from a new perspective, with a progressive two-stage training strategy proposed to enhance the capability of <span style="color:red">audio-visual alignment</span> .
</div>
</div>

# Experiences
<div class='paper-box'><div class='paper-box-image' style="text-align: center;"><div><div class="badge"></div><img src='images/pjlab.png' alt="sym" style="display: inline-block; width: 80%;"></div></div>
<div class='paper-box-text' markdown="1">

**Research Intern, Shanghai AI Laboratory, Shanghai, China, 2024.7-2024.11**

Research on video generation especially audio-driven portrait animation.

Supervised by Dr. Yanan Sun and Dr. <a href='https://zengyh1900.github.io/'>Yanhong Zeng</a>

</div>
</div>
<div class='paper-box'><div class='paper-box-image' style="text-align: center;"><div><div class="badge"></div><img src='images/ruc.png' alt="sym" style="display: inline-block; width: 80%;"></div></div>
<div class='paper-box-text' markdown="1">

**Visiting Student, Renmin University of China, Beijing, China, 2023.10-2024.3**

Research on multimodal learning especially audio-visual segmentation, aiming to segment sound sources within a video according to its corresponding audio. 

One paper [*Stepping-Stones*](https://gewu-lab.github.io/stepping_stones/) is accepted by ECCV2024.

Supervised by Prof. <a href='https://dtaoo.github.io/'>Di Hu</a>

</div>
</div>

# Honors and Awards
- *2025*, Outstanding Graduation Paper of UCAS.
- *2025*, Outstanding Graduate of Beijing.
- *2024*, China National Scholarship.
- *2024*, First-Level Scholarship of UCAS.

# Educations
- *2025.09 - present*, Master, Peking University. 
- *2021.09 - 2025.6*, Undergraduate, University of Chinese Academy of Sciences. 
