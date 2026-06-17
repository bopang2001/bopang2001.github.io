---
title: "Trajectory-Centric 3D Multi-Object Tracking"
excerpt: "Pose-aware online tracking and trajectory-centric offline optimization for autonomous driving perception."
collection: portfolio
permalink: /portfolio/trajectory-centric-3d-mot/
date: 2023-01-01
period: "2023 - 2025"
institution: "Zhejiang University"
redirect_from:
  - /portfolio/pb-mot/
---

**2023 - 2025**  
**Zhejiang University**

This research experience focuses on robust 3D multi-object tracking for autonomous driving, especially identity consistency, pose-aware association, and trajectory continuity under long range observations, occlusion, and ego-motion.

- Developed pose-aware association strategies for online 3D multi-object tracking, improving identity consistency through ego-motion-aware spatial reasoning.
- Achieved leaderboard-leading performance on the KITTI 3D Multi-Object Tracking benchmark in both online and offline settings, ranking first among submitted methods at the time of evaluation.
- Extended online tracking into a trajectory-centric offline optimization framework for evidence recovery, topology repair, gap completion, and kinematic state refinement.

## PB-MOT: Pose-aware Association Boosted Online 3D Multi-Object Tracking

**Status:** accepted by IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025.

PB-MOT addresses online 3D MOT for robotic and autonomous driving platforms. The method combines ego-motion-compensated state estimation with a rotated ellipse association strategy, aiming to preserve geometric precision and motion robustness while keeping the tracker computationally efficient.

**Links:** [Publication](/publication/2025-10-19-pb-mot) · [Video Demo](https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-mot.mp4) · [KITTI Benchmark](https://www.cvlibs.net/datasets/kitti/eval_tracking_detail.php?result=5f0e5c5888646315f2f17a38ad840d81b46e569b)

## PB-MOT++: Offline Trajectory Refinement for 3D Multi-Object Tracking

**Status:** manuscript under review.

PB-MOT++ extends the pose-aware tracking line toward trajectory-centric offline optimization. Instead of repeatedly operating on frame-wise detections, it optimizes trajectories through boundary recovery, topology repair, gap completion, and kinematic refinement. This direction is intended to improve long-range trajectory consistency with limited computational overhead.

**Links:** [Manuscript Record](/publication/2025-10-20-pb-mot-plus-plus) · [Video Demo](https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-motpp.mp4) · [KITTI Benchmark](https://www.cvlibs.net/datasets/kitti/eval_tracking_detail.php?result=c84c4a1ca8d9548e0647af9aeba0c276b805144a)

Video Demonstrations
======

<div class="research-video-grid">
  <div class="research-video-item">
    <h3>PB-MOT</h3>
    <video autoplay muted loop playsinline preload="auto" controls poster="/images/publications/pb-mot-pipeline.png">
      <source src="https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-mot.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p><a href="https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-mot.mp4" target="_blank" rel="noopener">Open full video</a></p>
  </div>
  <div class="research-video-item">
    <h3>PB-MOT++</h3>
    <video muted playsinline preload="metadata" controls poster="/images/publications/pb-mot-pp-pipeline.png">
      <source src="https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-motpp.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p><a href="https://github.com/bopang2001/bopang2001.github.io/releases/download/videos-1/pb-motpp.mp4" target="_blank" rel="noopener">Open full video</a></p>
  </div>
</div>
