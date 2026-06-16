---
permalink: /
title: "Bo Pang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student at Zhejiang University working on 3D perception and autonomous navigation. My research focuses on LiDAR-based place recognition, sparse-map retrieval, loop closure detection, 3D multi-object tracking, and map-light robot navigation.

My recent work includes PB-MOT, a pose-aware association approach for online 3D multi-object tracking accepted by IROS 2025. I am also developing semantic-aware sparse-map retrieval methods for robust LiDAR localization in large-scale environments.

I am interested in overseas academic exchange, postdoctoral opportunities, and research collaborations in robotics, autonomous driving, and spatial perception.

Education
======

**Zhejiang University**, Hangzhou, China  
Ph.D. in Control Science and Engineering, Sep 2023 -- Present  
Advisors: Prof. Liang Li and Prof. Jiming Chen

**Shandong University**, Jinan, China  
B.Eng. in Automation, Sep 2019 -- Jun 2023  
Advisors: Prof. Chaoqun Wang, Prof. Yan Li, and Prof. Bo Sun  
GPA: 96.69 / 100

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
{% assign publications = site.publications | sort: "publication_order" %}
{% for post in publications %}
  {% include publication-card.html post=post %}
{% endfor %}
</ol>
