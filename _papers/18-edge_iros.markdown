---
title:  "Robust Edge-based Visual Odometry using Machine-Learned Edges"
teaser: "/img/teaser/iros_edge.png"
authors: "Fabian Schenk, Friedrich Fraundorfer."
conference: IROS
year: 2017 (oral)
comments: false
---

In this work, we present a real-time robust edgebased visual odometry framework for RGBD sensors (REVO). 
Even though our method is independent of the edge detection algorithm, we show that the use of state-of-the-art machine-learned edges gives significant improvements in terms of robustness
and accuracy compared to standard edge detection methods. 
In contrast to approaches that heavily rely on the photo-consistency assumption, edges are less influenced by lighting changes and the sparse edge representation offers a
larger convergence basin while the pose estimates are also very fast to compute. Further, we introduce a measure for tracking quality, which we use to determine when to insert a
new key frame. We show the feasibility of our system on realworld datasets and extensively evaluate on standard benchmark sequences to demonstrate the performance in a wide variety of
scenes and camera motions. Our framework runs in real-time on the CPU of a laptop computer and is available online.

[Paper](/files/schenk_iros_2017.pdf)
[Video](https://youtu.be/PUTV9vsdpbA)
[Code](https://github.com/fabianschenk/REVO)
