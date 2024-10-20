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

I am a final-year Ph.D student at Renmin University of China, advised by Prof. [Qin Jin](https://www.jin-qin.com/). My research focuses on vision and language, involving cross-modal generation, multimodal understanding, and automatic evaluation.

Currently, I am working on book-level text evaluation and generation.


# 🔥 News
- *2024.09*: Our survey paper was released: [What Makes a Good Story and How Can We Measure It? A Comprehensive Survey of Story Evaluation](https://arxiv.org/pdf/2408.14622). Check our [GitHub page](https://github.com/DingyiYang/Awesome-Story-Evaluation) for a quick review.
- *2024.08*: [Synchronized Video Storytelling: Generating Video Narrations with Structured Storyline](aclanthology.org/2024.acl-long.513) was accepted by ACL 2024.
- *2024.06*: Finished my research internship at Alibaba Group. It's my pleasure to work with my mentor, [Tiezheng Ge].
- *2023.10*: [Visual captioning at will: Describing images and videos guided by a few stylized sentences](dl.acm.org/doi/10.1145/3581783.3612263) was accepted by ACM MM 2023.
- *2023.07*: [Attractive storyteller: Stylized visual storytelling with unpaired text](aclanthology.org/2023.acl-long.619/) was accepted by ACL 2023.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Synchronized Video Storytelling: Generating Video Narrations with Structured Storyline](https://aclanthology.org/2024.acl-long.513.pdf)

**Dingyi Yang**, Chunru Zhan, Ziheng Wang, Biao Wang, Tiezheng Ge, Bo Zheng, Qin Jin

[**Open Source**](https://github.com/alibaba/alimama-video-narrator) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose the task of Synchronized Video Storytelling, generating text to **narrate the ongoing video scenes** and **serve as useful voiceovers.** 
- We propose a new benchmark in the advertising domain, namely E-SyncVidStory.
- We propose an effective framework called VideoNarrator, which simultaneously supports storyline generation and controllable video story generation.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[What Makes a Good Story and How Can We Measure It? A Comprehensive Survey of Story Evaluation](https://arxiv.org/pdf/2408.14622)

**Dingyi Yang**, Qin Jin

[**Open Source**](https://github.com/DingyiYang/Awesome-Story-Evaluation) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We highlight the evaluation challenges in story generation, identify various human criteria to measure stories, and present existing benchmark datasets.
- We propose a taxonomy to organize evaluation metrics that have been developed or can be adapted for story evaluation, along with a discussion of their merits and limitations.
- We suggest potential future research directions, extending from story evaluation to general evaluations.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Visual captioning at will: Describing images and videos guided by a few stylized sentences](https://dl.acm.org/doi/pdf/10.1145/3581783.3612263)

**Dingyi Yang**, Hongyu Chen, Xinglin Hou, Tiezheng Ge, Yuning Jiang, Qin Jin

- We explore the task of few-shot visual captioning, aiming to generate stylized captions guided by a few sentences.
- We propose FS-StyleCap, a two-stage trained framework.


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Attractive storyteller: Stylized visual storytelling with unpaired text](https://aclanthology.org/2023.acl-long.619.pdf)

**Dingyi Yang**, Qin Jin

- We explore stylized visual storytelling, generating stories with complicated styles for image sequences.
- We propose StyleVSG, with style-specific parameters to control the text style, and a memory module to maintain context coherence.
- To achieve a trade-off between style accuracy and visual relevance, we apply multi-task training on our pseudo {images-stylized story} pairs and {images-factual story} pairs.


</div>
</div>

- [An experimental study of text representation methods for cross-site purchase preference prediction using the social text data](jcst.ict.ac.cn/en/article/doi/10.1007/s11390-017-1763-6), Ting Bai, Hong-Jian Dou, Wayne Xin Zhao, **Dingyi Yang**, Ji-Rong Wen. Journal of Computer Science and Technology, 32(4): 828-842, 2017.

# 🎖 Honors and Awards
- *2024.09* National Scholarship (Top 0.2%)
- *2022.09 and 2023.09* The First Prize Scholarship.
- *2020.09 and 2019.09* Model Student of Academic Records.
- *2017.09* Sa-Shixuan Elite Fund Scholarship.

# 📖 Educations
- *2021.09 - 2024.10 (now)*, Renmin University of China. Supervisor: Prof. Qin Jin. 
- *2018.09 - 2021.06*, Peking University. Supervisor: Prof. Xiaoru Yuan. 

# 💬 Invited Talks
- *2024.09*, "AI+X" National Forum for Outstanding Doctoral Students.

# 💻 Experiences
- *2022 - 2024*, Research Internship, [Alibaba Group](https://www.alimama.com/), Beijing, China.
- *2021 - 2022*, Project of Winter Olympic Visualization, [Beijing Municipal Commission of Transport](https://jtw.beijing.gov.cn/), Beijing, China.
- *2021*, WeChat Program for COVID-19 visualization, [Tencent HealthCare](https://healthcare.tencent.com/), Beijing, China.
