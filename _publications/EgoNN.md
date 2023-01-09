---
short: 'EgoNN'
title: 'EgoNN: Egocentric Neural Network for Point Cloud Based 6DoF Relocalization at the City Scale'
thumbnail: /images/egonn.png
collection: publications
permalink: /publications/EgoNN
date: 2-04-2022
venue: 'Robotics and Automation Letters'
authors: 'Jacek Komorowski, Monika Wysoczanska and Tomasz Trzcinski'
abstract: "The letter presents a deep neural network-based method for global and local descriptors extraction from a point cloud acquired by a rotating 3D LiDAR. The descriptors can be used for two-stage 6DoF relocalization. First, a course position is retrieved by finding candidates with the closest global descriptor in the database of geo-tagged point clouds. Then, the 6DoF pose between a query point cloud and a database point cloud is estimated by matching local descriptors and using a robust estimator such as RANSAC. Our method has a simple, fully convolutional architecture based on a sparse voxelized representation. It can efficiently extract a global descriptor and a set of keypoints with local descriptors from large point clouds with tens of thousand points. Our code and pretrained models are publicly available on the project website."
bibtex: "@ARTICLE{9645340, <br>
author={Komorowski, Jacek and Wysoczanska, Monika and Trzcinski, Tomasz}, <br>
journal={IEEE Robotics and Automation Letters}, <br>
title={EgoNN: Egocentric Neural Network for Point Cloud Based 6DoF Relocalization at the City Scale}, <br>
year={2022}, <br>
volume={7}, <br>
number={2}, <br>
pages={722-729}, <br>
doi={10.1109/LRA.2021.3133593}}"
code: "https://github.com/jac99/Egonn"
pdf: "https://ieeexplore.ieee.org/document/9645340"
---

