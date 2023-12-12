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

I have an interdisciplinary background and the aspiration to develop machine learning-driven simulation methods to promote drug discovery and answer critical life chemistry problems.


# 💻 Experience

- **Development of a Flexible-Receptor Molecular Docking Method** *2/2023-present*

  Undergraduate Researcher, Instructed by Prof. Yi Qin Gao, Peking University
  
  - Developed DSDPflex, a GPU-accelerated flexible-receptor docking program derived from DSDP; implemented receptor side-chain sampling, scoring, and gradient optimization on GPU (CUDA).
  - Designed and implemented specific optimizations for flexible-receptor tasks that help address some observed issues in current methods, improving the docking accuracy significantly.
  - Constructed a new cross-docking dataset for comprehensive evaluations of flexible-receptor docking methods, more diverse and challenging than commonly used sets, and tested DSDPFlex with mainstream methods.
  - Validated that DSDPFlex outperformed AutoDock Vina in flexible-receptor docking accuracies while presenting ∼250-fold acceleration (∼1 second per task on 1 GPU).
  - Authored a paper on this project. (preparing for submission)


- **Comparison of the Electrostatic Fields of Chorismate Mutases** *08/2023-09/2023*

Summer Research Intern, Instructed by Prof. Anastassia N. Alexandrova, UCLA (remote)

  - Investigated the previous research on the catalytic mechanism of Chorismate Mutase (CM) and learned to use Amber.
  - Studied and retrieved representative enzyme structures from different CM families that were suitable for intra- and inter-class comparison.
  - Prepared TSA-binding protein structures for subsequent molecular dynamics simulations, with AlphaFold prediction, structure alignment, and molecular docking for various systems.

**Investigation on Deep Learning-Based Molecular Docking Models** *09/2022-01/2023*

Undergraduate Researcher, Instructed by Prof. Yi Qin Gao, Peking University

  - Learned the fundamentals of deep learning, graph neural networks, and generative models to under- stand the principles of the latest docking models.
  - Investigated and tested deep learning-based molecular docking methods, e.g., GNINA, EquiBind, DiffDock.
  - Presented an in-detail report about DiffDock at the group meeting, which was the state-of-the-art model.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ChemRxiv</div><img src='images/flex.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DSDPFlex: An Improved Flexible-Receptor Docking Method with GPU Acceleration](https://chemrxiv.org/engage/chemrxiv/article-details/656469905bc9fcb5c97a9fc0)

**Chengwei Dong**, YuPeng Huang, Xiaohan Lin, Hong Zhang\*, Yi Qin Gao\*

- Fast, Accurate, and Generalizable.
- Molecular Docking; GPU Acceleration; Virtual Screening
</div>
</div>

# 📖 Educations

- *09/2020 - 07/2024*, **B.S. in Chemisty**, Peking University, Beijing  


# 🔥 News

# 🎖 Honors and Awards
