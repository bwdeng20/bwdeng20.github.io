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

I am currently a Ph.D student at Sun Yat-sen University. My research interest includes:
 - Open-world Graph Learning: unknown rejection, generalized catogroy discovery, etc.
 - Graph Contrasive Learning
 - Robust Graph Learning: adversarial robustness, anomaly detection, etc.
 - Graph Signal Processing: filter design, signal sampling, etc.
 - (Test-time) Domain Adaptation (on Graphs)

I am always open for collaborations and if you are interested in my research feel free to contact me via email.

# 🔥 News
- *2024.08*: &nbsp; We propose a graph contrasive learning framework [THESAURUS](/papers/Thesaurus4AAAI2025-v04.pdf) for node clustering.
- *2024.08*: &nbsp; A [paper](/papers/prospect_full.pdf) presenting theorems on the robustness and heterophily adaptability of PROSPECT has been submitted to a renowned journal.
- *2024.07*: &nbsp;🎉🎉 One full research paper is accepted by [CIKM 2024](https://cikm2024.org/). 


# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/THESAURUS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[THESAURUS: Contrastive Graph Clustering by Swapping Fused Gromov-Wasserstein Couplings](/papers/Thesaurus4v04.pdf)

**Bowen Deng**, Tong Wang, Lele Fu, Sheng Huang, Chuan Chen, and Tao Zhang.

[**Project**](https://github.com/bwdeng20/THESAURUS)

TL;DR: We propose a novel graph contrastive learning framework based on Fused Gromov-Wasserstein optimal transport on graphs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2024</div><img src='images/PROSPECT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PROSPECT: Learn MLPs on Graphs Robust against Adversarial Structure Attacks](/papers/prospect-cikm24-sigconf.pdf)

**Bowen Deng**, Jialong Chen, Yanming Hu, Zhiyong Xu, Chuan Chen, Tao Zhang

[**Project**](https://github.com/bwdeng20/PROSPECT)

TL;DR: Tackle heteropihly, robustness, and inference scalability challenges with GNN-to-MLP knowledge distillation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLSP 2021</div><img src='images/dygcn-mlsp2021.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Graph Convolutional Network: A Topology Optimization Perspective](https://ieeexplore.ieee.org/document/9596206)

**Bowen Deng**, Aimin Jiang

[**Project**]()

TL;DR: Refine the graph structure with pseudo labels for graph convolution networks.
</div>
</div>

- [ADMM-Based TDOA Estimation](https://ieeexplore.ieee.org/document/8355251), Yanping Zhu , Bowen Deng, Aimin Jiang, Xiaofeng Liu, **IEEE Communications Letters**, 2018

# 🎖 Honors and Awards
<!-- - *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2022.09 - present*, Ph.D, Sun Yat-sen University.
- *2019.06 - 2022.06*, Master, Hohai University.
- *2015.09 - 2019.06*, Undergraduate, Hohai University.

# 💬 Invited Talks
<!-- - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
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