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

I am currently pursuing an M.S. in Biomedical Engineering at ShanghaiTech University under the guidance of Prof. [Qian Wang (王乾)](https://qianwang.space/). I also completed my Bachelor’s degree in Computer Science at ShanghaiTech University. I have published several papers about computer vision.

Below are my research interests:
- Visual object tracking.
- Human-object interaction.
- Sparse view reconstruction.


# 📖 Educations
<div style="display: flex; align-items:center; padding-top: 10px">
    <img style="margin-right: 30px" src="images/上科大校徽.png" alt="image" width="90" height="90">
    <p style="margin:0; flex: 1;">
        <font size="4"><b>ShanghaiTech University, Shanghai, China</b></font><br>
        <font size="3">Sept. 2023 - Present</font><br>
        <font size="3"><i>M.S.</i> in Biomedical Engineering</font><br>
        <font size="3">Supervisor: Prof. <a href="https://qianwang.space/">Qian Wang</a></font>
    </p>
</div>

<div style="display: flex; align-items:center; padding-top: 10px">
    <img style="margin-right: 30px" src="images/上科大校徽.png" alt="image" width="90" height="90">
    <p style="margin:0; flex: 1;">
        <font size="4"><b>ShanghaiTech University, Shanghai, China</b></font><br>
        <font size="3">Sept. 2019 - 2023</font><br>
        <font size="3"><i>B.E.</i> in Computer Science</font><br>
    </p>
</div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/mitracker.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MUC: Mixture of Uncalibrated Cameras for Robust 3D Human Body Reconstruction](https://arxiv.org/pdf/2403.05055v1.pdf)

Yitao Zhu\*, Sheng Wang*, **Mengjie Xu**, Zixu Zhuang, Zhixin Wang, Kaidong Wang, Han Zhang, Qian Wang<sup>+</sup><br>

- Introduces a technique for accurately reconstructing 3D human poses and shapes from images captured by uncalibrated cameras.
- Utilizes pre-trained monocular models to estimate camera positions and employs a distance ranking optimization strategy for precise joint fusion, addressing self-occlusion issues.
- Deploys a model to reweight human surfaces for accurate body shape estimation outputs.
</div>
</div>

# 🎖 Honors and Awards
- *2020.10*, Merit Student of ShanghaiTech University. 
- *2023.11*, Academic Scholarships, ShanghaiTech University.
- *2024.11*, Academic Scholarships, ShanghaiTech University.

