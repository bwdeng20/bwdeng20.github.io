---
permalink: /
title: ""
# excerpt: ""
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

I am currently a Ph.D. student at Sun Yat-sen University. My research interests include:
 - Open-world Graph Learning: open-set recognition(OSR), generalized category discovery (GCD), etc.
 - (Graph) Contrastive Learning
 - Robust Graph Learning: adversarial robustness, anomaly detection, etc.
 - Graph Signal Processing: filter design, signal sampling, etc.
 - (Test-time) Domain Adaptation (on Graphs)

I am always open to collaborations, and if you are interested in my research, feel free to contact me via email.
# 🔥 News
- *2025.01*: &nbsp; 🎉🎉 One paper is accepted by ICLR 2025.
- *2024.12*: &nbsp; Invited to be a reviewer for ICML 2025.
- *2024.12*: &nbsp;🎉🎉 The graph contrastive learning framework [THESAURUS](https://arxiv.org/abs/2412.11550) is accepted by [AAAI 2025 (CCF A, Core A*)](https://aaai.org/conference/aaai/aaai-25/).
- *2024.07*: &nbsp;🎉🎉 The mutual GNN-MLP distillation framework [PROSPECT](/papers/prospect-cikm24-sigconf.pdf) is accepted by [CIKM 2024 (CCF B, Core A)](https://cikm2024.org/). 


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review at ICML 2025 (CCF A, Core A*)</div><img src='images/GraphGCD_EmbeddingSpace.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Understanding Parametric Generalized Category Discovery on Graphs](https:TODO) 

**Bowen Deng**, Lele Fu, Jialong Chen, Sheng Huang, Tianchi Liao, Tao Zhang, Chuan Chen.

*Under review at ICML*, 2025

[**Project**](https://github.com/bwdeng20/TODO)

TL;DR: We provide the first rigorous theoretical answer to the core GCD question: "When and how do old classes help (parametric) generalized category discovery (on graphs)?"
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025 (CCF A, Core A*)</div><img src='images/THESAURUS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[THESAURUS: Contrastive Graph Clustering by Swapping Fused Gromov-Wasserstein Couplings](https://arxiv.org/abs/2412.11550) 

**Bowen Deng**, Tong Wang, Lele Fu, Sheng Huang, Chuan Chen, and Tao Zhang.

*Proceedings of the AAAI Conference on Artificial Intelligence (AAAI ’25)*, February 25 – March 4, 2025, Philadelphia, Pennsylvania, USA.



[**Project**](https://github.com/bwdeng20/THESAURUS)

TL;DR: We propose a novel graph contrastive learning framework based on Fused Gromov-Wasserstein optimal transport on graphs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/MGMD-Illustration.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mutual GNN-MLP Distillation for Robust Graph Adversarial Defense](/papers/mgmd.pdf)

**Bowen Deng**, Jialong Chen, Yanming Hu, Chuan Chen, Tao Zhang

*Under review*, 2024

[**Project**](https://github.com/bwdeng20/PROSPECT)

TL;DR: We prove the robustness and heterophily adaptability of Mutual GNN-MLP Distillation (MGMD) and further discuss its robustness against adaptive attacks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2024 (CCF B, Core A)</div><img src='images/PROSPECT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PROSPECT: Learn MLPs on Graphs Robust against Adversarial Structure Attacks](/papers/prospect-cikm24-sigconf.pdf)

**Bowen Deng**, Jialong Chen, Yanming Hu, Zhiyong Xu, Chuan Chen, Tao Zhang

*Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM ’24)*, October 21–25, 2024, Boise, ID, USA.

[**Project**](https://github.com/bwdeng20/PROSPECT)

TL;DR: Tackle heteropihly, robustness, and inference scalability challenges with GNN-to-MLP knowledge distillation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLSP 2021</div><img src='images/dygcn-mlsp2021.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Graph Convolutional Network: A Topology Optimization Perspective](/papers/mlsp_template_camera_ready.pdf)
<!-- - [Dynamic Graph Convolutional Network: A Topology Optimization Perspective](https://ieeexplore.ieee.org/document/9596206)>
-->

**Bowen Deng**, Aimin Jiang

*IEEE 31st International Workshop on Machine Learning for Signal Processing (MLSP)*, Gold Coast, Australia, 2021.

[**Project**]()

TL;DR: Refine the graph structure with pseudo labels with learnable edge scores.
</div>
</div>

- [Graph Neural Ricci Flow: Evolving Feature from a Curvature Perspective](https://openreview.net/forum?id=7b2JrzdLhA), Jialong Chen, **Bowen Deng**, Zhen WANG, Chuan Chen, Zibin Zheng, ***ICLR 2025***, 2025
  
- [******_for_Relieving_Distribution_Shift_on_Graphs](), Jialong Chen, **Bowen Deng**, Yuecheng Li, Chuan Chen, Zibing Zheng, ***Under review***, 2024

- [Decoupling anomaly discrimination and representation learning: self-supervised learning for anomaly detection on attributed graph](https://link.springer.com/article/10.1007/s41019-024-00249-8), Yanming Hu, Chuan Chen, **Bowen Deng**, Yujing Lai, Hao Lin, Zibin Zheng, Jing Bian, ***Data Science and Engineering***, 2024

- [ADMM-Based TDOA Estimation](https://ieeexplore.ieee.org/document/8355251), Yanping Zhu , **Bowen Deng**, Aimin Jiang, Xiaofeng Liu, ***IEEE Communications Letters***, 2018


# 🎖 Honors and Awards
- *2024* First Prize Scholarship of Graduate Student, Sun Yat-sen University
- *2019* First Prize Scholarship of Graduate Student, Hoahai University
- *2017* Scholarship of Academic Excellence, Hohai University
- *2016* Academic Progress Award, Hohai University

# 📖 Educations
- *2022.09 - present*, Ph.D, Sun Yat-sen University. (Average: 88.95/100)
- *2019.06 - 2022.06*, Master, Hohai University (Postgraduate Recommendation). (Average: 83.67/100)
- *2015.09 - 2019.06*, Undergraduate, Hohai University. (Average: 87.74/100, Transcript [En](official_files/DengBowen-Transcript-BS-Eng.pdf)/[Zh](official_files/DengBowen-Transcript-BS-CN.pdf))

<!-- -
# 💬 Invited Talks
 *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Research</div><img src='images/qmf_recons.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Efficient Graph Signal Sampling and Reconstruction](https://github.com/bwdeng20/thgsp)

**Mentor**: Prof. [Antonio Ortega](https://viterbi.usc.edu/directory/faculty/Ortega/Antonio) (University of Southern California)

**When and where**: *2021.07 - 2021.09*, remote

- Developed a [PyTorch-based package](https://github.com/bwdeng20/thgsp/tree/main/thgsp/sampling) for graph signal sampling and reconstruction.
- Surveyed and implemented the most efficient existing algorithms for graph signal sampling and reconstruction.
- Proposed a data-driven graph signal sampling algorithm for complex signals mixup by low- and high-frequency signals.


</div>
</div>
