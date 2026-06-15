---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

PDF CV
======

<div class="cv-pdf-viewer">
  <object data="{{ base_path }}/files/MyCV.pdf" type="application/pdf">
    <iframe src="{{ base_path }}/files/MyCV.pdf" title="Bo Pang CV"></iframe>
  </object>
</div>

Education
======

* Ph.D. student, Zhejiang University

Research interests
======

* 3D perception
* LiDAR-based place recognition and sparse-map retrieval
* Loop closure detection
* 3D multi-object tracking
* Autonomous navigation and map-light robot navigation

Publications
======
  <ul>{% assign publications = site.publications | sort: "publication_order" %}
  {% for post in publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Academic profiles
======

* [Google Scholar](https://scholar.google.com/citations?user=jLPrDZkAAAAJ&hl)
* [IEEE Xplore author profile](https://ieeexplore.ieee.org/author/757841103996784)
* [ORCID](https://orcid.org/0009-0002-5424-6260)

TODO
======

* Add a public academic email address.
