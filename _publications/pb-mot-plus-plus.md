---
title: "PB-MOT++: Extending Pose-aware Association to Trajectory-Centric Offline Optimization"
collection: publications
category: manuscripts
publication_order: 2
authors: "<strong>Bo Pang</strong>, Yang Xu, Jiming Chen, and Liang Li"
permalink: /publication/2025-10-20-pb-mot-plus-plus
excerpt: "Trajectory-centric offline optimization built on pose-aware association."
abstract: >-
  Reliable perception of dynamic traffic participants is essential for intelligent transportation systems and autonomous driving. While recent advances in 3D multi-object tracking (3D MOT) have substantially improved benchmark performance, trajectory fragmentation and identity inconsistency remain challenging under prolonged occlusion or sparse observations. Existing offline methods partially alleviate these issues through global matching or sequence-level refinement, yet many remain detection-centric and offer limited capability for active trajectory reconstruction.
  To address this problem, we propose PB-MOT++, a computationally efficient trajectory-centric offline optimization framework that extends our previous pose-aware tracker, PB-MOT. Instead of repeatedly operating on frame-wise detections, PB-MOT++ directly optimizes trajectories through an evidence-first four-stage pipeline: boundary recovery, topology repair, gap completion, and kinematic refinement. By separating structural restoration from geometric smoothing, the proposed framework effectively reduces error propagation and improves long-range trajectory consistency.
  Extensive experiments on the KITTI benchmark demonstrate the effectiveness of PB-MOT++. Our method achieves state-of-the-art performance with 83.16% HOTA and 87.23% AssA, while maintaining 2351.08 FPS on a CPU-only platform. These results show that high-fidelity offline trajectory optimization can substantially improve tracking quality with minimal computational overhead.
venue: "Manuscript under review"
status: "Manuscript under review"
videourl: "https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-motpp.mp4"
kittiurl: "https://www.cvlibs.net/datasets/kitti/eval_tracking_detail.php?result=c84c4a1ca8d9548e0647af9aeba0c276b805144a"
teaser: "publications/pb-mot-pp-pipeline.png"
thumbnail_label: "Pipeline"
citation: 'B. Pang, Y. Xu, J. Chen, and L. Li, &quot;PB-MOT++: Extending Pose-aware Association to Trajectory-Centric Offline Optimization,&quot; manuscript under review.'
---

PB-MOT++ extends pose-aware association to trajectory-centric offline optimization.
