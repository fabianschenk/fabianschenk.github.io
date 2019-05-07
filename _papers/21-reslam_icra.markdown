---
title:  "RESLAM: A real-time robust edge-based SLAM system"
teaser: "/img/teaser/reslam_icra_teaser.png"
authors: "Fabian Schenk, Friedrich Fraundorfer"
conference: ICRA
year: 2019 (Interactive Poster)
comments: false
---

Simultaneous Localization and Mapping is a key requirement for many practical applications in robotics. In
this work, we present RESLAM, a novel edge-based SLAM system for RGBD sensors. Due to their sparse representation, larger convergence basin and stability under illumination
changes, edges are a promising alternative to feature-based or other direct approaches. We build a complete SLAM pipeline
with camera pose estimation, sliding window optimization, loop closure and relocalisation capabilities that utilizes edges
throughout all steps. In our system, we additionally refine the initial depth from the sensor, the camera poses and the camera
intrinsics in a sliding window to increase accuracy. Further, we introduce an edge-based verification for loop closures that
can also be applied for relocalisation. We evaluate RESLAM on wide variety of benchmark datasets that include difficult
scenes and camera motions and also present qualitative results. We show that this novel edge-based SLAM system performs
comparable to state-of-the-art methods, while running in real-time on a CPU. RESLAM is available as open-source software.

[Paper](https://github.com/fabianschenk/fabianschenk.github.io/raw/master/files/schenk_uavg_2019.pdf)
[Code](https://github.com/fabianschenk/RESLAM)
