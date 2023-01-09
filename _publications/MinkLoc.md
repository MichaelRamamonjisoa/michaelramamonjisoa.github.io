---
short: 'MinkLoc'
title: 'MinkLoc++: Lidar and Monocular Image Fusion for Place Recognition'
collection: publications
thumbnail: /images/overview.jpeg
permalink: /publications/Minkloc
date: 21-03-2021
venue: 'International Joint Conference on Neural Networks (IJCNN 2021)'
authors: 'Jacek Komorowski, Monika Wysoczanska, and Tomasz Trzcinski'
abstract: "The letter presents a deep neural network-based method for global and local descriptors extraction from a point cloud acquired by a rotating 3D LiDAR. The descriptors can be used for two-stage 6DoF relocalization. First, a course position is retrieved by finding candidates with the closest global descriptor in the database of geo-tagged point clouds. Then, the 6DoF pose between a query point cloud and a database point cloud is estimated by matching local descriptors and using a robust estimator such as RANSAC. Our method has a simple, fully convolutional architecture based on a sparse voxelized representation. It can efficiently extract a global descriptor and a set of keypoints with local descriptors from large point clouds with tens of thousand points. Our code and pretrained models are publicly available on the project website."
pdf: "https://ieeexplore.ieee.org/document/9533373"
code: "https://github.com/jac99/MinkLocMultimodal"
---

