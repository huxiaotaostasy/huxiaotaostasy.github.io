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

I am currently a second-year PhD student in the 3DVLab at the [Hong Kong University of Science and Technology (HKUST)](https://hkust.edu.hk/), under the supervision of [Prof. Ping Tan](https://scholar.google.com/citations?user=XhyKVFMAAAAJ). Additionally, I am an intern at [Horizon Robotics Technology R&D Co., Ltd.](https://horizon.cc/), where I work closely with [Wei Yin](https://yvanyin.xyz/). Previously, I earned my M.S. degree from the College of Computer Science at [Nankai University](https://en.nankai.edu.cn/) in 2024, under the supervision of [Prof. Ming-Ming Cheng](https://scholar.google.com/citations?user=huWpVyEAAAAJ) and [Prof. Jun Xu](https://csjunxu.github.io/). I received my B.E. degree from the [Dalian University of Technology (DLUT)](https://www.dlut.edu.cn/) in 2021. My research interests include computer vision and computer graphics. I am also a member of [AnySyn3D](https://anysyn3d.github.io/index.html), a research interest group focusing on various topics related to 3D.

 <!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Two papers are accepted by ICCV 2025. 
- *2024.11*: &nbsp;🎉🎉 One paper is accepted by 3DV 2025. 
- *2023.02*: &nbsp;🎉🎉 One paper is accepted by CVPR 2023 (Highlight). 
- *2023.01*: &nbsp;🎉🎉 One paper is accepted by TIP. 
- *2022.07*: &nbsp;🎉🎉 One paper is accepted by ECCV 2022 (Oral). 

# 📝 Publications 

<!-- ######################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='collections/2025/drivingworld.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**DrivingWorld: Constructing World Model for Autonomous Driving via Video GPT**

arxiv, 2024

**Xiaotao Hu**, Wei Yin, Mingkai Jia, Junyuan Deng, Xiaoyang Guo, Qian Zhang, Xiaoxiao Long, Ping Tan

[Paper](https://arxiv.org/abs/2412.19505) \| [Code](https://github.com/YvanYin/DrivingWorld) \| [Project page](https://huxiaotaostasy.github.io/DrivingWorld/index.html)
</div>
</div>

<!-- ######################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='collections/2025/epona.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Epona: Autoregressive DiffusionWorld Model for Autonomous Driving**

*International Conference on Computer Vision (**ICCV**), 2025*

Kaiwen Zhang, Zhenyu Tang, **Xiaotao Hu**, Xingang Pan, Xiaoyang Guo, Yuan Liu, Jingwei Huang, Li Yuan, Qian Zhang, Xiao-Xiao Long, Xun Cao, Wei Yin

[Paper](https://arxiv.org/abs/2506.24113)
</div>
</div>

<!-- ######################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='collections/2025/boost3d.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Boost 3D Reconstruction using Diffusion-based Monocular Camera Calibration**

*International Conference on Computer Vision (**ICCV**), 2025*

Junyuan Deng, Wei Yin, Xiaoyang Guo, Qian Zhang, **Xiaotao Hu**, Weiqiang Ren, Xiaoxiao Long, Ping Tan

[Paper](https://arxiv.org/abs/2411.17240)
</div>
</div>

<!-- ######################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='collections/2024/Ctrl-Room.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Ctrl-Room: controllable text-to-3D room meshes generation with layout constraints**

*International Conference on 3D Vision (**3DV**), 2025*

Chuan Fang, Yuan Dong, Kunming Luo, **Xiaotao Hu**, Rakesh Shrestha, Ping Tan

[Paper](https://arxiv.org/abs/2310.03602)
</div>
</div>

<!-- ######################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='collections/2023/SAFA.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Scale-Adaptive Feature Aggregation for Efficient Space-Time Video Super-Resolution**

*Winter Conference on Applications of Computer Vision (**WACV**), 2024*

Zhewei Huang, Ailin Huang, **Xiaotao Hu**, Chen Hu, Jun Xu, Shuchang Zhou

[Paper](collections/2023/SAFA.pdf) \| [Code](https://github.com/hzwer/WACV2024-SAFA) \| [BibTex](collections/2023/SAFA.md)
</div>
</div>

<!-- ######################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='collections/2023/dmvfn.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**A Dynamic Multi-Scale Voxel Flow Network for Video Prediction**

*Computer Vision and Pattern Recognition (**CVPR Highlight**), 2023*

**Xiaotao Hu**, Zhewei Huang, Ailin Huang, Jun Xu, Shuchang Zhou

[Paper](collections/2023/dmvfn.pdf) \| [Code](https://github.com/megvii-research/CVPR2023-DMVFN) \| [BibTex](collections/2023/dmvfn.md)
</div>
</div>

<!-- ######################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='collections/2023/facesr.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Semi-cycled generative adversarial networks for real-world face super-resolution**

*IEEE Transactions on Image Processing (**TIP**), 2023*

Hao Hou, Jun Xu, Yingkun Hou, **Xiaotao Hu**, Benzheng Wei, Dinggang Shen

[Paper](collections/2023/facesr.pdf) \| [Code](https://github.com/HaoHou-98/SCGAN) \| [BibTex](collections/2023/facesr.md)
</div>
</div>

<!-- ######################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='collections/2022/mga.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Restore globally, refine locally: A mask-guided scheme to accelerate super-resolution networks**

*European Conference on Computer Vision (**ECCV Oral**), 2022*

**Xiaotao Hu**, Jun Xu, Shuhang Gu, Ming-Ming Cheng, Li Liu

[Paper](collections/2022/mga.pdf) \| [Code](https://github.com/huxiaotaostasy/MGA-scheme) \| [BibTex](collections/2022/mga.md)
</div>
</div>


# 🎖 Honors and Awards
- *2022.09*: &nbsp;The Third Prize Scholarship, Nankai University.
- *2019.11*: &nbsp;Silver Medal, The 44th ACM International Collegiate Programming Contest (ICPC), Nanchang.
- *2019.09*: &nbsp;The First Prize Scholarship, Dalian University of Technology.

# 📖 Educations
- *2024.09 - now*, PhD student in Electronic & Computer Engineering, Hong Kong University of Science and Technology (HKUST), Hong Kong.
- *2021.09 - 2024.06*, M.S. in Computer Science, Nankai University (NKU), Tianjin, China.
- *2017.09 - 2021.06*, B.S. in Software Engineering (ranking 4%), Dalian University of Technology (DLUT), Dalian, China.

# 💬 Invited Talks
not yet

# 💻 Internships
- *2024.03 - now*, [Horizon Robotics Technology R&D Co., Ltd.](https://horizon.cc/), Beijing & Shanghai.
- *2023.08 - 2024.03*, Light Illusions, Beijing.
- *2022.08 - 2023.08*, [Megvii](https://en.megvii.com/), Beijing.