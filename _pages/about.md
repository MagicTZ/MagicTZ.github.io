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

Hi! I'm **Zhen Tan (谭臻)**. I am currently a Ph.D. candidate at the National University of Defense Technology (NUDT), supervised by <a href='https://ieeexplore.ieee.org/author/37271079500'>Prof. Dewen Hu (CAS Academician)<strong><span id='total_cit'></span></strong></a> and <a href='https://scholar.google.com/citations?user=DvrngV4AAAAJ&hl'>Assoc. Prof. Xieyuanli Chen<strong><span id='total_cit'></span></strong></a>. Prior to this, I obtained my Master's degree from the Technical University of Munich (TUM), guided by <a href='https://scholar.google.com/citations?user=U1xaKegAAAAJ&hl=en'>Prof. Yusheng Xu<strong><span id='total_cit'></span></strong></a>, and my Bachelor's degree from Wuhan University (WHU).

My research vision aims to bridge the gap between **High-Fidelity 3D Vision** (NeRF/3DGS) and **Embodied Intelligence**. I focus on building robust **Spatial Representations** and **World Models** that enable robots to understand and interact with dynamic environments.

I value the intersection of academic research and industrial deployment. 
* **Engineering Foundation**: Before my PhD, I worked as a **Sensor Fusion Engineer** at **LiangDao Intelligence**, leading the development of LiDAR-Camera fusion systems for highway autonomous driving.
* **Research Collaboration**: Recently, I have maintained close research collaborations with teams at **4DV.ai** and **CVLife**. Together, we explored **Monocular 4D Gaussian Splatting** on mobile devices and optimized **Fast differentiable rendering**, pushing the boundaries of efficient spatial perception.

# 🔥 News
- *2025.12*: &nbsp;🎉🎉 One Paper is accepted to RA-L 2025!
- *2025.10*: &nbsp;🏆🏆 We won the **Champion** of the **IROS 2025 EvSLAM Challenge**!
- *2025.06*: &nbsp;🎉🎉 One Paper is accepted to IROS 2025!
- *2025.01*: &nbsp;🎉🎉 One Paper is accepted to ICRA 2025!
- *2024.06*: &nbsp;🎉🎉 One Paper is accepted to IROS 2024!

# 📝 Publications 
**\* denotes equal contribution.**
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2025</div><img src='images/tan2025ral.png' alt="TVG-SLAM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TVG-SLAM: Robust Gaussian Splatting SLAM with Tri-view Geometric Constraints](https://arxiv.org/abs/2506.23207)

**Zhen Tan**, Xieyuanli Chen, L. Feng, Y. Ge, S. Zhi, J. Liu, Dewen Hu

[**Project**](https://github.com/MagicTZ/TVG-SLAM) 
<!-- <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID:PAPER_ID'></span></strong> -->
- Proposed a tri-view geometric constraint to address the instability of 3D Gaussian Splatting in texture-less or repetitive regions.
- Achieved tightly-coupled optimization of camera tracking and high-fidelity mapping, ensuring robustness in challenging outdoor environments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2025</div><img src='images/liu2025iros.png' alt="Event Tracking" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Tracking Any Point with Frame-Event Fusion Network at High Frame Rate](https://arxiv.org/abs/2409.11953)

J. Liu, B. Wang, **Zhen Tan**, J. Zhang, H. Shen, Dewen Hu

[**PDF**](https://arxiv.org/abs/2409.11953) <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID:PAPER_ID'></span></strong>
- Explored multi-modal fusion of RGB frames and Event cameras for robust point tracking in high-dynamic scenarios.
- Leveraged the high temporal resolution of event data to maintain tracking stability under rapid motion, providing a reliable perception front-end for dynamic robotic tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2025</div><img src='images/niu2025icra.png' alt="HGSLoc" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HGSLoc: 3DGS-based Heuristic Camera Pose Refinement](https://arxiv.org/abs/2409.10925)

Z. Niu, **Zhen Tan**, J. Zhang, X. Yang, Dewen Hu

[**PDF**](https://arxiv.org/abs/2409.10925) <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID:PAPER_ID'></span></strong>
- Developed a heuristic camera pose refinement framework leveraging 3D Gaussian Splatting as a dense map prior.
- Significantly improved visual relocalization accuracy by aligning query images with rendered views, facilitating long-term autonomy in persistent environments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2024</div><img src='images/tan2024iros.png' alt="TD-NeRF" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TD-NeRF: Novel Truncated Depth Prior for Joint Camera Pose and Neural Radiance Field Optimization](https://arxiv.org/abs/2405.07027)

**Zhen Tan**, Z. Zhou, Y. Ge, Z. Wang, Xieyuanli Chen, Dewen Hu

[**PDF**](https://arxiv.org/abs/2405.07027) <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID:PAPER_ID'></span></strong>
- Address the dependency of NeRF on pre-computed COLMAP poses by introducing a truncated depth prior.
- Enabled joint optimization of neural radiance fields and camera poses, allowing for high-quality reconstruction without accurate initial pose priors.
</div>
</div>

# 🎖 Honors and Awards
- *2025*, IROS 2025 EvSLAM Challenge, Champion.
- *2025*, Second-class scholarship for outstanding students
- *2022*, Freshman Scholarship of NUDT, First Prize.
- *2021*, Munich Innovation Challenge (Tech Innovation Award), 1st Place.
- *2017*, Remote Sensing Star in Wuhan University, Top 10 Students.

# 📖 Educations
- *2022.09 - Present*, Ph.D. in Control Science and Engineering, National University of Defense Technology (NUDT). 
- *2018.09 - 2022.01*, M.Sc. in Geodesy and Geoinformation, Technical University of Munich (TUM) (QS Top 30).
- *2014.09 - 2018.06*, B.Eng. in Photogrammetry and Remote Sensing, Wuhan University (WHU).

# 💬 Hobbies
- **Sports**: Football (University Team Captain), Skiing, Basketball, Taekwondo.
- **Arts**: Dancing, Movies.
- **Travel**: Exploring different cultures.


<div style="text-align: center; margin-top: 20px;">
  <span id="busuanzi_container_site_pv" style="display: inline;">
    👀 Total Views: <span id="busuanzi_value_site_pv"></span>
  </span>
  &nbsp;&nbsp;
  <span id="busuanzi_container_site_uv" style="display: inline;">
    🧍 Visitors: <span id="busuanzi_value_site_uv"></span>
  </span>
</div>

<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

