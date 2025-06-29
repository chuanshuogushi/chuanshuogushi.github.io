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

Hi, I'm Boyuan Wang, a Phd student at CASIA. My research focuses on artificial intelligence, computer vision, AIGC and Embodied AI. 

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.03*: &nbsp;🎉🎉 Two papers are accepted to CVPR2025. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/humandreamer_500x250.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HumanDreamer: Generating Controllable Human-Motion Videos via Decoupled Generation](https://arxiv.org/pdf/2503.24026)

**Boyuan Wang\***, Xiaofeng Wang*, Chaojun Ni, Guosheng Zhao, Zhiqin Yang, Zheng Zhu, Muyang Zhang, Yukun Zhou, Xinze Chen, Guan Huang, Lihong Liu, Xingang Wang

<!-- [**Project**](https://humandreamer.github.io/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
[**Project**](https://humandreamer.github.io)<strong> | [**Paper**](https://arxiv.org/abs/2503.24026) | [**Dataset**](https://huggingface.co/datasets/chuanshuogushi/MotionVid)

- HumanDreamer is a decoupled framework for human-motion video generation that first generates diverse poses from text using MotionDiT and then synthesizes high-quality videos with improved control and fidelity.
</div>
</div>

- [Drivedreamer4d: World models are effective data machines for 4d driving scene representation.](https://github.com), Zhao, G., Ni, C., Wang, X., Zhu, Z., Zhang, X., Wang, Y., Huang, G., Chen, X., **Wang, B.**, Zhang, Y., Mei, W. and Wang, X. **CVPR 2025**

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2022.06 - now*, Ph.D. student in Artificial Intelligence, CASIA 
- *2018.09 - 2022.06*, B.Sc. in Automation, BUAA

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.07 - now*, [GigaAI](https://github.com/GigaAI-research), China.