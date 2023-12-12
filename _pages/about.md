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

- **Development of a Flexible-Receptor Molecular Docking Method** *11/2022-present*

  Undergraduate Research, Instructed by Prof. Yi Qin Gao
  
  - Developed DSDPflex, a GPU-accelerated flexible-receptor docking program derived from DSDP; implemented receptor side-chain sampling, scoring, and gradient optimization on GPU (CUDA).
  - Designed and implemented specific optimizations for flexible-receptor tasks that help address some observed issues in current methods, improving the docking accuracy significantly.
  - Constructed a new cross-docking dataset for comprehensive evaluations of flexible-receptor docking methods, more diverse and challenging than commonly used sets, and tested DSDPFlex with mainstream methods.
  - Validated that DSDPFlex outperformed AutoDock Vina in flexible-receptor docking accuracies while presenting ∼250-fold acceleration (∼1 second per task on 1 GPU).
  - Authored a paper on this project. (preparing for submission)


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
