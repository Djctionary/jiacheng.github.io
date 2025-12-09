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

Hi, I am a fourth-year undergraduate student working at the Robotics Institute under [Prof. Sarath Kodagoda](https://profiles.uts.edu.au/Sarath.Kodagoda) at the University of Technology Sydney (UTS). I spent my first two college years at Northeastern University (NEU), where I joined the [HACI Lab](https://cz26.github.io/CZ-HP/lab/) and was advised by [Dr. Changzeng Fu](https://cz26.github.io/CZ-HP/lab/).

My research interests focus on deploying AI algorithms, especially Reinforcement Learning (RL), to control robots (quadruped/humanoid) and autonomous systems. I am still expanding my horizons and exploring new areas in this field.

In my spare time, I'm passionate about developing AI applications for health and wellness. I collaborate with [Ziyi Zhao](https://ziyizhao-bio.github.io/) (Ph.D. student at UTS) on web-based AI health platforms, including [Palm Stream](https://palmstream.net) and [Skinova](https://skinova.au), which leverage AI technology to help people live healthier lives through smart skincare analysis and personalized health solutions.

I am currently looking for Ph.D. positions starting Fall 2026. You can check my CV here: [📄 CV]({{ '/docs/JiachengDongCV.pdf' | relative_url }})


# 🔥 News
- *2025.02*: &nbsp;🎉🎉 *The 1st MPDD Challenge: Multimodal Personality-aware Depression Detection*, **ACM MM 2025**, was successfully held! [🌐 Website](https://hacilab.github.io/MPDDChallenge.github.io/#HOME)
- *2025.12*: &nbsp;🎉🎉 I joined X-Lab at <a href="https://www.agibot.com/" target="_blank"><img src='images/Agibot.png' alt="AgiBot" width="20px" style="vertical-align:middle; margin-right:4px; border:none;"></a>[AgiBot](https://www.agibot.com/), supervised by [peng-zhihui](https://github.com/peng-zhihui). 

# 🤖 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Robotics</div><img src='images/UnitreeGo2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Goal-Directed Navigation for Unitree Go2 in Isaac Sim Using Reinforcement Learning**

**Jiacheng Dong**

*Support: UTS Robotics Institute*

[🎥 Video Demo](https://youtu.be/0b45lL_OgjI)

- A reinforcement learning-based navigation system for the Unitree Go2 quadruped robot in Isaac Sim simulation environment, enabling autonomous goal-directed locomotion.
</div>
</div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src='images/FilterRec_pipeline.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FilterRec: An Intent-Aware Framework for Dynamic Filter Recommendation**

Dingxian Wang, **Jiacheng Dong**, Jiaqi Deng, Jing Long, et al.

WWW 2026 (Under Review)

[📃 Paper](https://drive.google.com/file/d/1d6VriY-AimPp1Pavui1QqqeeEZHHJLXJ/view?usp=sharing)

- An intent-aware framework for dynamic filter recommendation systems.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2026</div><img src='images/PPHA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PPHA: Pre-Post Hidden Alignment for Multi-Task Speech Model Distillation with Rapid Convergence**

**Jiacheng Dong**, [Changzeng Fu](https://cz26.github.io/CZ-HP/lab/), Jiadong Wang

ICASSP 2026 (Under Review)

[📄 Paper](https://drive.google.com/file/d/1l1jfVBXZXVHmEO4A2QNrbDmtQWEmEd27/view?usp=sharing)

- A novel knowledge distillation framework for multi-task speech models that achieves rapid convergence through pre-post hidden state alignment.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/MPDD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**The First MPDD Challenge: Multimodal Personality-aware Depression Detection**

[Changzeng Fu](https://cz26.github.io/CZ-HP/lab/), [Zelin Fu](https://zin-fu.github.io/Zelin-Fu.github.io/), Xinhe Kuang, **Jiacheng Dong**, et al.

ACM MM 2025

[🌐 Website](https://hacilab.github.io/MPDDChallenge.github.io/)

- The first multimodal challenge on personality-aware depression detection, featuring datasets from both elderly clinical patients and young university students.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sensors 2025</div><img src='images/HGF-MiLaG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**HGF-MiLaG: Hierarchical Graph Fusion for Emotion Recognition in Conversation with Mid-Late Gender-Aware Strategy**

Y Wang, R Hao, Z Li, X Kuang, **J Dong**, et al.

Sensors 2025

[📃 Paper](https://scholar.google.co.in/citations?view_op=view_citation&hl=en&user=HjyLq8AAAAAJ&citation_for_view=HjyLq8AAAAAJ:u5HHmVD_uO8C) | [🤖 Code](https://github.com/floatingdream2003/HGF-MiLaG)

- A hierarchical graph fusion framework with gender-aware strategy for emotion recognition in conversations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACRA 2025</div><img src='images/Soft Robot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A Vine-inspired Solution for Enhancing Safety and Efficiency in Broadband Cable Installation**

Nathan Rees, [Sarath Kodagoda](https://profiles.uts.edu.au/Sarath.Kodagoda), Karthick Thiyagarajan, Sangmim Song, Yara Fakoua, Damian Sue, Chloe Judson, Jack Hibbard, Jackson Russell, **Jiacheng Dong**, et al.

ACRA 2025 (Australasian Conference on Robotics and Automation)

[📄 Paper](https://drive.google.com/file/d/1zeAJcETJq1KT7dmOi3jv3YeEAbqe2jJQ/view?usp=sharing)

- A vine-inspired robotic solution for safer and more efficient broadband cable installation.
</div>
</div>

# 🎖 Honors and Awards
- *2025* **Dean's List** – University of Technology Sydney (UTS)
- *2024* **National Third Prize** – 23rd National RoboMaster Super Combat Competition
- *2023-2024* **First Prize, Full Scholarship** – HACI Lab, Northeastern University
- *2024-2025* **Reviewer** – AAAI, ACM MM, and BESC conferences 

# 📖 Educations
- *2024.08 - Present*, **B.S. in Software Engineering with Honours**, University of Technology Sydney (UTS), Australia  
  GPA: 90.3/100
- *2022.09 - 2024.06*, **B.S. in Computer Science**, Northeastern University (NEU), China  
  GPA: 88.1/100 

# 💻 Internships
- *2025.12 - 2026.06*, **Reinforcement Learning Motion Control Engineer**, Shanghai AgiBot Innovation Technology Co., Ltd., China  
  Department: X-Lab (Full-Time)
- *2025.08 - 2025.12*, **Front-end Engineer**, Qin Xun Zhixin Technology (Zhejiang) Co., Ltd., China  
  Department: Web Application Development (Casual)
- *2025.03 - 2026.03*, **Full-Stack Engineer**, Cloud Xidong Big Data Technology (Qinhuangdao) Co., Ltd., China  
  Department: Web Application Development (Casual)

# 🌐 Web Development
- **[Palm Stream](https://palmstream.net)** - AI-powered health and longevity technology platform  
  *Collaborator: [Ziyi Zhao](https://ziyizhao-bio.github.io/) (Ph.D. @ UTS)*  
  A startup focused on leveraging AI technologies for health monitoring and wellness optimization.

- **[Skinova](https://skinova.au)** - Smart skincare ecosystem with AI-driven analysis  
  *Collaborator: [Ziyi Zhao](https://ziyizhao-bio.github.io/) (Ph.D. @ UTS)*  
  An integrated platform combining AI skin analysis, personalized skincare guidance, and professional medical aesthetic solutions through hardware-software integration and content-driven innovation.