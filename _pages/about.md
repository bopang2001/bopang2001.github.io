---
permalink: /
title: "Bo Pang"
author_profile: true
description: "Bo Pang's academic homepage for 3D perception, LiDAR place recognition, sparse-map retrieval, 3D multi-object tracking, and autonomous navigation."
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. candidate in Control Science and Engineering at Zhejiang University. My research lies at the intersection of 3D perception, robot localization, and autonomous navigation.

My work focuses on LiDAR place recognition and sparse-map localization, 3D multi-object tracking, and trajectory-level perception for autonomous systems. I am also exploring sign-aware map-light navigation, where robots use environmental signs, semantic landmarks, and human-readable cues for route understanding and progress verification.

I am open to visiting research opportunities and long-term collaborations in robotics, autonomous driving, and embodied navigation.

<div class="homepage-contact">
  <strong>Contact:</strong>
  <a href="mailto:boaltria@gmail.com">boaltria@gmail.com</a>
  <span>Personal</span>
  <a href="mailto:pangbo_zju@zju.edu.cn">pangbo_zju@zju.edu.cn</a>
  <span>Zhejiang University</span>
</div>

<p class="cta-links">
  <a href="/publications/">Publications</a>
  <a href="/portfolio/">Research</a>
  <a href="/cv/">CV</a>
  <a href="/files/MyCV.pdf">Download CV</a>
</p>

Education
======

<div class="education-list">
  <div class="education-entry">
    <a class="education-logo-link" href="https://www.zju.edu.cn/english/" target="_blank" rel="noopener" aria-label="Zhejiang University">
      <img class="education-logo" src="https://upload.wikimedia.org/wikipedia/en/thumb/1/16/Zhejiang_University_Logo.svg/250px-Zhejiang_University_Logo.svg.png" alt="Zhejiang University logo">
    </a>
    <div class="education-text">
      <div class="education-primary"><strong><a href="https://www.zju.edu.cn/english/" target="_blank" rel="noopener">Zhejiang University</a></strong><span>,</span><a href="https://earth.google.com/web/search/Yuquan+Campus,+Zhejiang+University,+38+Zheda+Road,+Hangzhou,+China" target="_blank" rel="noopener">Hangzhou, China</a></div>
      <div>Ph.D. in Control Science and Engineering, Sep 2023 -- Present</div>
      <div>Advisors: Prof. Liang Li and Prof. Jiming Chen</div>
    </div>
  </div>

  <div class="education-entry">
    <a class="education-logo-link" href="https://www.en.sdu.edu.cn/" target="_blank" rel="noopener" aria-label="Shandong University">
      <img class="education-logo" src="https://upload.wikimedia.org/wikipedia/en/thumb/7/79/Shandong_University_Emblem.svg/250px-Shandong_University_Emblem.svg.png" alt="Shandong University logo">
    </a>
    <div class="education-text">
      <div class="education-primary"><strong><a href="https://www.en.sdu.edu.cn/" target="_blank" rel="noopener">Shandong University</a></strong><span>,</span><a href="https://earth.google.com/web/search/Central+Campus,+Shandong+University,+27+Shanda+Nanlu,+Jinan,+China" target="_blank" rel="noopener">Jinan, China</a></div>
      <div>B.Eng. in Automation, Sep 2019 -- Jun 2023</div>
      <div>Advisors: Prof. Chaoqun Wang, Prof. Yan Li, and Prof. Bo Sun</div>
      <div>GPA: 96.69 / 100</div>
    </div>
  </div>
</div>

Research Highlights
======

<div class="research-video-grid">
  <div class="research-video-item">
    <h3>PB-MOT++</h3>
    <p>Trajectory-centric offline optimization for boundary recovery, topology repair, gap completion, and kinematic refinement.</p>
    <video autoplay muted loop playsinline preload="auto" controls poster="/images/publications/pb-mot-pp-pipeline.png">
      <source src="https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-motpp.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p><a href="https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-motpp.mp4" target="_blank" rel="noopener">Open full-resolution video</a></p>
  </div>
  <div class="research-video-item">
    <h3>PB-MOT</h3>
    <p>Online 3D multi-object tracking with pose-aware association and robust trajectory continuity.</p>
    <video autoplay muted loop playsinline preload="auto" controls poster="/images/publications/pb-mot-pipeline.png">
      <source src="https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-mot.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p><a href="https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-mot.mp4" target="_blank" rel="noopener">Open full-resolution video</a></p>
  </div>
</div>

Research Interests
======

- 3D perception for autonomous systems
- LiDAR place recognition, loop closure, and sparse-map localization
- 3D multi-object tracking and trajectory-level perception
- Sign-aware map-light navigation with semantic landmarks
- Robotics and machine learning

Publications
======

{% include base_path %}

<ol class="bibliography">
{% assign publications = site.publications | where: "status_group", "publication" | sort: "publication_order" %}
{% for post in publications %}
  {% include publication-card.html post=post %}
{% endfor %}
</ol>

Manuscripts
======

<ol class="bibliography">
{% assign manuscripts = site.publications | where: "status_group", "manuscript" | sort: "publication_order" %}
{% for post in manuscripts %}
  {% include publication-card.html post=post %}
{% endfor %}
</ol>

Research Experience
======

<div class="research-card-grid">
  <div class="research-card">
    <h3><a href="/portfolio/signpostnav/">Vision-Language Navigation with Coarse Maps and Semantic Landmarks</a></h3>
    <p class="research-card-meta">Zhejiang University, 2026 - Present</p>
    <p>Semantic landmarks, coarse maps, and language-guided route reasoning for map-light robotic navigation.</p>
  </div>
  <div class="research-card">
    <h3><a href="/portfolio/sparse-map-lidar-localization/">Semantic Sparse-Map Retrieval and Loop Closure Detection</a></h3>
    <p class="research-card-meta">Zhejiang University, 2025 - 2026</p>
    <p>LiDAR-based localization and loop closure under sparse, incomplete, and deployment-oriented map representations.</p>
  </div>
  <div class="research-card">
    <h3><a href="/portfolio/trajectory-centric-3d-mot/">Trajectory-Centric 3D Multi-Object Tracking</a></h3>
    <p class="research-card-meta">Zhejiang University, 2023 - 2025</p>
    <p>Pose-aware online tracking and trajectory-centric offline optimization for autonomous driving perception.</p>
  </div>
</div>

Systems
======

I have hands-on experience with mobile robot platforms and embedded power electronics, with a focus on connecting sensors, onboard computing, power delivery, and robotic hardware for real-platform perception experiments.

<p class="cta-links">
  <a href="/robotic-systems/">View Systems Work</a>
</p>
