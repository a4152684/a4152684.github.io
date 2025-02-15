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

I am a frist-year PhD student in the [LIESMARS](https://liesmars.whu.edu.cn/), [Wuhan University](https://www.whu.edu.cn/). My advisors are Prof. [Zhen Dong](https://dongzhenwhu.github.io/index.html) and Prof. [Bisheng Yang](https://3s.whu.edu.cn/info/1025/1415.htm).  Previously, I obtained my B.Eng degree at [SGG](http://main.sgg.whu.edu.cn/) of Wuhan University.

My research interest lies in the field of 3D Computer Vision, particularly including point cloud completion, scene understanding. Besides, I am conducting some researches related to intelligent transportation systems (ITS). If you are interested in my research, feel free to contact me at <zhen.cao@whu.edu.cn>!

I am a member of [WHU-USI3DV](https://github.com/WHU-USI3DV), please check advancements on point cloud processing including enhancement, registration, localization, segmentation, detection, etc.

# 🔥 News
- *2025.02*: &nbsp;🎉🎉 Our paper [Cross-modal semantic transfer for point cloud semantic segmentation](https://www.sciencedirect.com/science/article/pii/S0924271625000243) is accepted by ISPRS J!
- *2024.09*: &nbsp;🎉🎉 Our paper [LaneMapping: A benchmark approach and dataset for large-scale lane mapping from MLS point clouds](https://www.sciencedirect.com/science/article/pii/S156984322400493X) is accepted by JAG 2024!
- *2024.07*: &nbsp;🎉🎉 Our paper [EGIINet: Explicitly Guided Information Interaction Network for Cross-modal Point Cloud Completion](https://arxiv.org/pdf/2407.02887) is accepted by ECCV 2024!
- *2024.05*: &nbsp;🎉🎉 Our paper [SparseDC: Depth Completion From Sparse and Non-uniform Inputs](https://doi.org/10.1016/j.inffus.2024.102470) is accepted by Informarion Fusion!
- *2022.11*: &nbsp;🎉🎉 Our paper [KT-Net: Knowledge Transfer for Unpaired 3D Shape Completion](https://ojs.aaai.org/index.php/AAAI/article/view/25101) is accepted by AAAI 2023!

# 📝 Publications
\* denotes equal contributions and † denotes the corresponding author.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS J</div><img src='publication/freeseg.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Cross-modal semantic transfer for point cloud semantic segmentation

**Zhen Cao<sup>*</sup>**, Xiaoxin Mi<sup>*</sup>, Bo Qiu, Zhipeng Cao, Chen Long, Xinrui Yan, Chao Zheng, Zhen Dong<sup>&dagger;</sup>, Bisheng Yang

<span style="color:red">**ISPRS J (IF: 10.6)**</span>

[[Paper]](https://www.sciencedirect.com/science/article/pii/S0924271625000243), [[Code]](https://github.com/a4152684/StreetSeg)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JAG 2024</div><img src='publication/LaneMapping.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

LaneMapping: A benchmark approach and dataset for large-scale lane mapping from MLS point clouds

Xiaoxin Mi, Zhen Dong, Zhipeng Cao, Bisheng Yang<sup>&dagger;</sup>, **Zhen Cao**, Chao Zheng, Jantien Stoter, Lianglinag Nan

<span style="color:red">**JAG 2024 (IF: 7.6)**</span>

[[Paper]](https://www.sciencedirect.com/science/article/pii/S156984322400493X), [[Code]](https://github.com/MIXIAOXIN/LaneMapping)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='publication/Explicitly_Guided.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Explicitly Guided Information Interaction Network for Cross-modal Point Cloud Completion

Hang Xu<sup>*</sup>, Chen Long<sup>*</sup>, Wenxiao Zhang<sup>&dagger;</sup>, Yuan Liu, **Zhen Cao**, Zhen Dong, Bisheng Yang

<span style="color:red">**ECCV 2024 (CCF-B)**</span>

[[Paper]](https://arxiv.org/pdf/2407.02887), [[Code]](https://github.com/WHU-USI3DV/EGIInet)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Information Fusion</div><img src='publication/sparseDC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SparseDC: Depth Completion From Sparse and Non-uniform Inputs

Chen Long, Wenxiao Zhang, Zhe Chen, Haiping Wang, Yuan Liu, Peiling Tong, **Zhen Cao**, Zhen Dong<sup>&dagger;</sup>, Bisheng Yang

<span style="color:red">**Information Fusion (IF: 18.6)**</span>

[[Paper]](https://doi.org/10.1016/j.inffus.2024.102470), [[Code]](https://github.com/WHU-USI3DV/SparseDC)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='publication/KT-Net.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

KT-Net: Knowledge Transfer for Unpaired 3D Shape Completion

**Zhen Cao<sup>*</sup>**, WenXiao Zhang<sup>*</sup>, Xin Wen<sup>&dagger;</sup>, Zhen Dong, Yu-Shen Liu, Xiongwu Xiao, Bisheng Yang

<span style="color:red">**AAAI 2023 (CCF-A)**</span>

[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25101), [[Code]](https://github.com/a4152684/KT-Net)
</div>
</div>

# 🎖 Honors and Awards
- *2021*, Outstanding Graduate of Wuhan University (Top 5%)
- *2020*, Yong-Ling Chen Innovation & Learning Scholarship - First Class (Top 5%)
- *2018 $\&$ 2019*, National Scholarship for Postgraduates (Top 3%)

# 📖 Education
- *2024 - Now*, LIESMARS, Wuhan University, Ph.D. in Photogrammetry and Remote Sensing
- *2021 - 2024*, LIESMARS, Wuhan University, M.S.(Trans. to Ph.D.) in Photogrammetry and Remote Sensing
- *2017 - 2021*, SGG, Wuhan University, B.S. in Photogrammetry and Remote Sensing 
