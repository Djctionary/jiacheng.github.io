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

Hi, I am Jiacheng Dong, an incoming Master's student in Robotics at the University of Pennsylvania (UPenn), joining the [GRASP Lab](https://www.grasp.upenn.edu/). I completed my undergraduate studies at the University of Technology Sydney (UTS), where I worked at the Robotics Institute under [Prof. Sarath Kodagoda](https://profiles.uts.edu.au/Sarath.Kodagoda), after spending my first two years at Northeastern University (NEU) in the [HACI Lab](https://cz26.github.io/CZ-HP/lab.html), advised by [Prof. Changzeng Fu](https://cz26.github.io/CZ-HP/).

My research focuses on physics-based humanoid motion generation and retargeting, spanning both humanoid robots and game avatars. My long-term goal is to build capable companion humanoids that move and interact naturally in the physical world.

You can check my CV here: [📄 CV]({{ '/docs/JiachengDongCV.pdf' | relative_url }})


# News
- *2026.06*: &nbsp;I am doing my summer internship in X-Lab at <a href="https://www.agibot.com/" target="_blank"><img src='images/Agibot.png' alt="AgiBot" width="20px" style="vertical-align:middle; margin-right:4px; border:none;"></a>[AgiBot](https://www.agibot.com/), working on humanoid motion imitation and generation.
- *2025.12*: &nbsp;I did my winter internship in X-Lab at <a href="https://www.agibot.com/" target="_blank"><img src='images/Agibot.png' alt="AgiBot" width="20px" style="vertical-align:middle; margin-right:4px; border:none;"></a>[AgiBot](https://www.agibot.com/), working on humanoid whole-body motion control.
- *2025.02*: &nbsp;*The 1st MPDD Challenge: Multimodal Personality-aware Depression Detection*, **ACM MM 2025**, was successfully held! [🌐 Website](https://hacilab.github.io/MPDDChallenge.github.io/#HOME)

# Affiliation

<div class="affil-row">

  <div class="affil-card">
    <div class="affil-card__logo"><img class="logo-neu" src="images/NEU.png" alt="Northeastern University"></div>
    <div class="affil-card__role">B.S. CS</div>
    <div class="affil-card__org">Northeastern University</div>
    <div class="affil-card__sub"><strong><a href="https://cz26.github.io/CZ-HP/lab.html">HACI Lab</a></strong><br>Advised by <a href="https://cz26.github.io/CZ-HP/">Prof. Changzeng Fu</a></div>
    <div class="affil-card__date">Sep 2022 &ndash; Jun 2026</div>
  </div>

  <div class="affil-card">
    <div class="affil-card__logo"><img class="logo-uts" src="images/UTS.png" alt="University of Technology Sydney"></div>
    <div class="affil-card__role">B.Eng. Software</div>
    <div class="affil-card__org">University of Technology Sydney</div>
    <div class="affil-card__sub"><strong>Robotics Institute</strong><br>Advised by <a href="https://profiles.uts.edu.au/Sarath.Kodagoda">Prof. Sarath Kodagoda</a></div>
    <div class="affil-card__date">Aug 2024 &ndash; Jun 2026</div>
  </div>

  <div class="affil-card">
    <div class="affil-card__logo"><img class="logo-agibot" src="images/Agibot_logo.png" alt="AgiBot"></div>
    <div class="affil-card__role">Research Intern</div>
    <div class="affil-card__org"><a href="https://www.agibot.com/">AGIBOT Innovation Technology</a></div>
    <div class="affil-card__sub"><strong>X-Lab</strong><br>Advised by <a href="https://github.com/peng-zhihui">Zhihui Peng</a></div>
    <div class="affil-card__date">Dec 2025 &ndash; Jan 2026<br>Jun 2026 &ndash; Aug 2026</div>
  </div>

  <div class="affil-card">
    <div class="affil-card__logo"><img class="logo-penn" src="images/Upenn.png" alt="University of Pennsylvania"></div>
    <div class="affil-card__role">M.S. Robotics</div>
    <div class="affil-card__org">University of Pennsylvania</div>
    <div class="affil-card__sub"><strong><a href="https://www.grasp.upenn.edu/">GRASP Lab</a></strong></div>
    <div class="affil-card__date">Aug 2026 &ndash; Present</div>
  </div>

</div>

# Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Humanoid</div><img src='images/41118.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Co-speech Gestures from Humans to Humanoid Robots: An End-to-End Retargeting & Reinforcement-Learning Mimic Pipeline**

**Jiacheng Dong**, Shanjin Li

*UTS 41118 · Artificial Intelligence in Robotics*

[🌐 Project Portfolio](https://djctionary.github.io/UTS_41118_Project_Portfolio/)

- An end-to-end pipeline that recovers 3D human motion from video, retargets it to the NAO humanoid, and trains an RL policy for stable gesture imitation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Quadruped</div><img src='images/43008.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Goal-Directed Navigation for Unitree Go2 in Isaac Sim Using Reinforcement Learning**

**Jiacheng Dong**

*UTS 43008 · Reinforcement Learning*

[🎥 Video Demo](https://youtu.be/0b45lL_OgjI)

- A reinforcement learning-based navigation system for the Unitree Go2 quadruped robot in Isaac Sim simulation environment, enabling autonomous goal-directed locomotion.
</div>
</div>

# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src='images/FilterRec_pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FilterRec: An Intent-Aware Framework for Dynamic Filter Recommendation**

Dingxian Wang, **Jiacheng Dong**, Jiaqi Deng, Jing Long, et al.

WWW 2026

[📃 Paper](https://drive.google.com/file/d/1d6VriY-AimPp1Pavui1QqqeeEZHHJLXJ/view?usp=sharing)

- An intent-aware framework for dynamic filter recommendation systems.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Coming Soon</div><img src='images/coming-soon.svg' alt="Coming Soon" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PPHA: Pre-Post Hidden Alignment for Multi-Task Speech Model Distillation with Rapid Convergence**

**Jiacheng Dong**, Jingchao Xu, Shiqi Zhao, and Changzeng Fu

Coming Soon

- A novel knowledge distillation framework for multi-task speech models that achieves rapid convergence through pre-post hidden state alignment.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/MPDD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**The First MPDD Challenge: Multimodal Personality-aware Depression Detection**

[Changzeng Fu](https://cz26.github.io/CZ-HP/), [Zelin Fu](https://zin-fu.github.io/Zelin-Fu.github.io/), Xinhe Kuang, **Jiacheng Dong**, et al.

ACM MM 2025

[🌐 Website](https://hacilab.github.io/MPDDChallenge.github.io/)

- The first multimodal challenge on personality-aware depression detection, featuring datasets from both elderly clinical patients and young university students.
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sensors 2025</div><img src='images/HGF-MiLaG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**HGF-MiLaG: Hierarchical Graph Fusion for Emotion Recognition in Conversation with Mid-Late Gender-Aware Strategy**

Y Wang, R Hao, Z Li, X Kuang, **J Dong**, et al.

Sensors 2025

[📃 Paper](https://scholar.google.co.in/citations?view_op=view_citation&hl=en&user=HjyLq8AAAAAJ&citation_for_view=HjyLq8AAAAAJ:u5HHmVD_uO8C) | [🤖 Code](https://github.com/floatingdream2003/HGF-MiLaG)

- A hierarchical graph fusion framework with gender-aware strategy for emotion recognition in conversations.
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACRA 2025</div><img src='images/Pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A Vine-inspired Solution for Enhancing Safety and Efficiency in Broadband Cable Installation**

Nathan Rees, [Sarath Kodagoda](https://profiles.uts.edu.au/Sarath.Kodagoda), Karthick Thiyagarajan, Sangmim Song, Yara Fakoua, Damian Sue, Chloe Judson, Jack Hibbard, Jackson Russell, **Jiacheng Dong**, et al.

ACRA 2025 (Australasian Conference on Robotics and Automation)

[📄 Paper](https://drive.google.com/file/d/1zeAJcETJq1KT7dmOi3jv3YeEAbqe2jJQ/view?usp=sharing)

- A vine-inspired robotic solution for safer and more efficient broadband cable installation.
</div>
</div>

# Web Development
- **[Palm Stream](https://palmstream.net)** - AI-powered health and longevity technology platform  
  *Collaborator: [Ziyi Zhao](https://github.com/Jacoo-Zhao)*  
  A startup focused on leveraging AI technologies for health monitoring and wellness optimization.

- **[Skinova](https://skinova.au)** - Smart skincare ecosystem with AI-driven analysis  
  *Collaborator: [Ziyi Zhao](https://github.com/Jacoo-Zhao)*  
  An integrated platform combining AI skin analysis, personalized skincare guidance, and professional medical aesthetic solutions through hardware-software integration and content-driven innovation.

- **[EnglishMaster](https://englishmaster.space)** - Learn English from real sentences  
  *Solo project (design & development)*  
  A self-designed English learning platform that builds vocabulary and grammar through contextual, sentence-based practice.

# Honors and Awards
- *2025* **Dean's List** – University of Technology Sydney (UTS)
- *2024* **National Third Prize** – 23rd National RoboMaster Super Combat Competition
- *2023-2024* **First Prize, Full Scholarship** – HACI Lab, Northeastern University

# Acknowledgement

My deepest gratitude goes to [Prof. Changzeng Fu](https://cz26.github.io/CZ-HP/), who first led me into research and has been far more than an advisor to me.

I am also sincerely grateful to [Prof. Angela Huo](https://profiles.uts.edu.au/Huan.Huo), who supported me in many aspects of my life at UTS, and to [Prof. Sarath Kodagoda](https://profiles.uts.edu.au/Sarath.Kodagoda), who gave me the opportunity to deploy what I learned on real robots.