---
title:  "Combining Edge Images and Depth Maps for Robust Visual Odometry"
teaser: "/img/teaser/bmvc_edge_icp.png"
authors: "Fabian Schenk, Friedrich Fraundorfer"
conference: BMVC
year: 2017 (poster)
comments: false
---
We propose a robust visual odometry system for RGBD sensors. The
core of our method is a combination of edge images and depth maps for joint camera pose
estimation. Edges are more stable under varying lighting conditions than raw intensity
values and depth maps further add stability in poorly textured environments. This leads
to higher accuracy and robustness in scenes, where feature- or photoconsistency-based
approaches often fail. We demonstrate the robustness of our method under challenging
conditions on various real-world scenarios recorded with our own RGBD sensor.
Further, we evaluate on several sequences from standard benchmark datasets covering a
wide variety of scenes and camera motions. The results show that our method performs
best in terms of trajectory accuracy for most of the sequences indicating that the chosen
combination of edge and depth terms in the cost function is suitable for a multitude of
scenes.

[Paper](https://github.com/fabianschenk/fabianschenk.github.io/raw/master/files/schenk_bmvc_2018.pdf)
[Video](https://youtu.be/uj3rRyqSEnQ)
[Code](https://github.com/fabianschenk/REVO)
