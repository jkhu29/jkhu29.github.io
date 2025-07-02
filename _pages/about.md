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

I am a PhD student under the supervision of Dr. [Yanye Lu](https://nbic.pku.edu.cn/en/Faculty/Researchers/0a96455fce164e508fbe96162ef92f79.htm) at [Peking University](https://www.pku.edu.cn/). I also closely collaborate with Dr. [Guoqi Li](https://casialiguoqi.github.io/) and Dr. [Man Yao](https://scholar.google.com/citations?user=eE4vvp0AAAAJ&hl=en) from the Institute of Automation at the Chinese Academy of Sciences. My research interests primarily include **Vision Generation**, **Computational Imaging**, and **Brain-inspired deep learning**.

My recent work primarily focuses on discovering potential inductive biases in visual generation and restoration tasks, while enhancing vision generation and restoration systems through the lenses of pre-training, training based on these biases.

# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Two first author papers are accepted by International Conference on Computer Vision (**ICCV 2025**).
- *2025.02*: &nbsp;🎉🎉 Two paper are accepted by IEEE / CVF Computer Vision and Pattern Recognition Conference (**CVPR 2025**).
- *2025.01*: &nbsp;🎉🎉 One first author paper is accepted by International Conference on Learning Representations (**ICLR 2025**).
- *2024.12*: &nbsp;🎉🎉 One co-first author paper is accepted as **oral** by AAAI Conference on Artificial Intelligence (**AAAI 2025**).
- *2024.04*: &nbsp;🎉🎉 One first author paper is accepted as **spotlight** by International Conference on Machine Learning (**ICML 2024**).
- *2023.09*: &nbsp;🎉🎉 One co-first author paper is accepted as poster by Conference on Neural Information Processing Systems (**NeurIPS 2023**).
- *2023.06*: &nbsp;🎉🎉 One co-first author paper is accepted as poster by International Conference on Computer Vision (**ICCV 2023**).


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><img src='images/MVAR_overview.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Auto-Regressively Generating Multi-View Consistent Images**  
JiaKui Hu$^\*$, Yuxiao Yang$^\*$, Jialun Liu$^+$, Jinbo Wu, Chen Zhao, Yanye Lu$^+$

**<font color = "#224B8D">ICCV 2025</font>** \| [Paper](https://arxiv.org/abs/2506.18527) \| [Code](https://github.com/MILab-PKU/MVAR) \| [blog (Chinese)](https://blog.jongkhu.com/article/mvar)

In this paper, we product the first AutoRegressive-based multi-view image generation model. It's motivation is:

Diffusion-based multi-view image generation methods use a specific reference view for predicting subsequent views, which becomes problematic when overlap between the reference view and the predicted view is minimal, affecting image quality and multi-view consistency. Our MV-AR addresses this by using the preceding view with significant overlap for conditioning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/DCPT.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Universal Image Restoration Pre-training via Degradation Classification**  
JiaKui Hu, Lujia Jin, Zhengjian Yao, Yanye Lu$^+$

**<font color = "#224B8D">ICLR 2025</font>** \| [Paper](https://openreview.net/forum?id=PacBhLzeGO) \| [Code](https://github.com/MILab-PKU/dcpt) \| [blog (Chinese)](https://blog.jongkhu.com/article/dcpt)

In this paper, we report three interesting findings:
- Randomly initialized models demonstrate an inherent capability to classify degradation.
- Models trained on the all-in-one task exhibit the ability to discern unkown degradation.
- There is a degradation understanding step in the early training of the restoration model.

Based on these findings, *to ensure superior restoration performance, it is imperative
that the restoration model attains sufficient degradation classification capabilities before training.*
</div>
</div>

<!-- ###################################################### -->

<!-- $^\dagger$ -->

# 🎖 Honors and Awards

- *2021* **National Scholarship**, China, Xidian University.
- *2020* **National Scholarship**, China, Xidian University.


# 📖 Educations
- *2022.09 - present*, PhD student, Peking University. 
- *2019.09 - 2023.06*, Undergraduate, Xidian University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 📫 Academic Services

### Reviewer

Conference:

- IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2024, 2025
- Neural Information Processing Systems (NeurIPS) 2024
- International Conference on Learning Representations (ICLR) 2025
- International Conference on Machine Learning (ICML) 2025

Journals:

TNNLS, TCSVT, NN

# 💻 Experience
- *2025.04 - present*, Internship, at [AIDC](https://github.com/AIDC-AI), China.
- *2024.10 - 2025.03*, Internship, at [Baidu Vis](https://vis.baidu.com/#/), China.
- *2023.09 - present*, PhD student, at [Peking University](https://www.pku.edu.cn/), China.
- *2021.09 - 2022.01*, Internship, at [OneFlow](https://github.com/Oneflow-Inc/oneflow), China.