---
permalink: /
title: "Bo Pang"
author_profile: true
description: "Bo Pang's academic homepage for 3D perception, LiDAR place recognition, sparse-map retrieval, 3D multi-object tracking, and autonomous navigation."
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student at Zhejiang University working on 3D perception and autonomous navigation. My research focuses on LiDAR-based place recognition, sparse-map retrieval, loop closure detection, and 3D multi-object tracking for robust autonomous systems. I am particularly interested in map-light robot navigation, where robots operate with sparse, incomplete, or human-readable environmental cues.

I am open to overseas visiting research opportunities and long-term collaborations in robotics, autonomous driving, and embodied navigation.

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

- 3D perception and LiDAR-based scene understanding
- Place recognition, sparse-map retrieval, and loop closure detection
- Online 3D multi-object tracking
- Autonomous navigation and map-light robot navigation

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

Robotic Systems & Prototyping
======

Beyond algorithm development, I have hands-on experience in robotic system integration, including autonomous vehicle debugging, embedded electronics, PCB design, sensor interfacing, and field deployment. This engineering background helps me bridge perception algorithms with real robotic platforms, from data acquisition and hardware debugging to system-level validation.

<div class="engineering-card-grid">
  <a class="engineering-card" href="/portfolio/autonomous-vehicle-debugging/">
    <img src="/images/publications/pb-mot-pipeline.png" alt="Autonomous vehicle debugging placeholder">
    <h3>Autonomous Vehicle Debugging</h3>
    <p>System-level debugging for intelligent vehicle platforms, with emphasis on perception-system integration, data acquisition, and field validation.</p>
  </a>
  <a class="engineering-card" href="/portfolio/pcb-embedded-electronics/">
    <img src="/images/publications/sparse-map-lidar-localization.svg" alt="PCB and embedded electronics placeholder">
    <h3>PCB & Embedded Electronics</h3>
    <p>PCB design, sensor interfacing, embedded electronics, and power and communication considerations for robotic systems.</p>
  </a>
  <a class="engineering-card" href="/portfolio/field-robotics-integration/">
    <img src="/images/publications/pb-mot-pp-pipeline.png" alt="Field robotics integration placeholder">
    <h3>Field Robotics Integration</h3>
    <p>Connecting perception algorithms with sensors, computing hardware, data collection workflows, and practical robotic platform validation.</p>
  </a>
</div>
