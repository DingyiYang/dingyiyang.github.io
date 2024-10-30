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

I am a final-year Ph.D. student at Renmin University of China, advised by Prof. [Qin Jin](https://www.jin-qin.com/). My research focuses on Vision and Language, involving cross-modal generation, video understanding, and automatic evaluation. Currently, I am exploring book-level story evaluation and generation.


# 🔥 News
- *2024.09*: Our survey paper [What Makes a Good Story and How Can We Measure It? A Comprehensive Survey of Story Evaluation](https://arxiv.org/pdf/2408.14622) was released. Visit our [GitHub page](https://github.com/DingyiYang/Awesome-Story-Evaluation) for a quick review.
- *2024.09*: Completed my research internship at Alibaba Group. It's my pleasure to work with my mentor, [Tiezheng Ge](https://scholar.google.com/citations?user=db5ZTlMAAAAJ&hl=en).
- *2024.08*: [Synchronized Video Storytelling: Generating Video Narrations with Structured Storyline](https://aclanthology.org/2024.acl-long.513.pdf) was accepted by ACL 2024.
- *2023.10*: [Visual captioning at will: Describing images and videos guided by a few stylized sentences](https://dl.acm.org/doi/10.1145/3581783.3612263) was accepted by ACM MM 2023.
- *2023.07*: [Attractive storyteller: Stylized visual storytelling with unpaired text](https://aclanthology.org/2023.acl-long.619/) was accepted by ACL 2023.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/papers/synchronized.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Synchronized Video Storytelling: Generating Video Narrations with Structured Storyline](https://aclanthology.org/2024.acl-long.513.pdf)

**Dingyi Yang**, Chunru Zhan, Ziheng Wang, Biao Wang, Tiezheng Ge, Bo Zheng, Qin Jin

[**Open Source**](https://github.com/alibaba/alimama-video-narrator) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We explore the task of Synchronized Video Storytelling, generating text to **narrate the ongoing video scenes** and **serve as useful voiceovers.** 
- We release a new benchmark in the advertising domain called E-SyncVidStory.
- We propose an effective framework named VideoNarrator, which simultaneously supports storyline generation and controllable video story generation.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/papers/survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[What Makes a Good Story and How Can We Measure It? A Comprehensive Survey of Story Evaluation](https://arxiv.org/pdf/2408.14622)

**Dingyi Yang**, Qin Jin

[**Open Source**](https://github.com/DingyiYang/Awesome-Story-Evaluation) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We provide an in-depth discussion of the challenges in evaluating various story generation tasks.
- We analyze standardized criteria, addressing issues of inconsistent definitions and vague expressions.
- We systematically review traditional, LLM-based, and collaborative evaluation methods, highlighting their strengths and limitations in the context of story evaluation.
- We suggest potential future research directions, extending from story evaluation to general evaluations.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/papers/few_shot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Visual captioning at will: Describing images and videos guided by a few stylized sentences](https://dl.acm.org/doi/pdf/10.1145/3581783.3612263)

**Dingyi Yang**, Hongyu Chen, Xinglin Hou, Tiezheng Ge, Yuning Jiang, Qin Jin

- We explore Few-Shot Stylized Visual Captioning, which aims to generate captions in any desired style, using only a few examples as guidance during inference, without requiring further training.
- We propose an effective framework that handles multiple styles with a single model. It extracts the style representation from stylized samples, and aligns visual information to generate stylized captions.


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023</div><img src='images/papers/svst.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Attractive storyteller: Stylized visual storytelling with unpaired text](https://aclanthology.org/2023.acl-long.619.pdf)

**Dingyi Yang**, Qin Jin

- We explore Stylized Visual Storytelling, generating stories with complicated styles for image sequences.
- We propose StyleVSG, which applies style-specific parameters to control text style and incorporates a memory module to maintain context coherence.
- To balance style accuracy and visual relevance, we employ multi-task training using our pseudo {images-stylized story} pairs and {images-factual story} pairs.


</div>
</div>

- [An experimental study of text representation methods for cross-site purchase preference prediction using the social text data](https://jcst.ict.ac.cn/en/article/doi/10.1007/s11390-017-1763-6). Ting Bai, Hong-Jian Dou, Wayne Xin Zhao, **Dingyi Yang**, Ji-Rong Wen. Journal of Computer Science and Technology, 32(4): 828-842, 2017.

# 🔧 Projects
- [**Map Visualization Toolkit**](https://vis.pku.edu.cn/map_toolkit/): A comprehensive toolkit for map data processing, visualization, and interaction. Role: Creator and sole developer.
- [**COVID-19 Visualization and Visual Analytics**](https://vis.pku.edu.cn/ncov/home_en.html): A series of data visualization projects, helping people to understand the epidemic. Role: Main developer, design and set up the map visualization websites.

# 🎖 Honors and Awards
- *2024.09* National Scholarship (Top 0.2% in China)
- *2022.09 and 2023.09* The First Prize Scholarship.
- *2020.09 and 2019.09* Academic Excellence Scholarship.
- *2017.09* The Second Prize Sa-Shixuan Elite Fund Scholarship.
- *2016.09* The First Prize Scholarship.

# 📖 Educations
- *2021.09 - 2024.10 (now)*, Renmin University of China. Supervisor: Prof. [Qin Jin](https://www.jin-qin.com/). 
- *2018.09 - 2021.06*, Peking University. Supervisor: Prof. [Xiaoru Yuan](https://scholar.google.com/citations?user=mJJVqRYAAAAJ). 
- *2014.09 - 2018.06*, Renmin University of China. Advisor: Prof. [Yongcai Wang](https://yongcaiwang.github.io/index_en.html) and Prof. [Xin Zhao](https://scholar.google.com/citations?user=JNhNacoAAAAJ&hl=en).

# 💬 Invited Talks
- *2024.09.28*, "AI+X" National Forum for Outstanding Doctoral Students.

# 💻 Experiences
- *2022 - 2024*, Research Intern, [Alibaba Group](https://www.alimama.com/), Beijing, China.
- *2019 - 2021*, Winter Olympic Visualization Project, [Beijing Municipal Commission of Transport](https://jtw.beijing.gov.cn/), Beijing, China.
- *2020*, COVID-19 Visualization WeChat Mini Program, [Tencent HealthCare](https://healthcare.tencent.com/), Beijing, China.
