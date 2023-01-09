---
short: 'MinkLoc'
title: 'MinkLoc++: Lidar and Monocular Image Fusion for Place Recognition'
collection: publications
thumbnail: /images/overview.jpeg
permalink: /publications/Minkloc
date: 21-03-2021
venue: 'International Joint Conference on Neural Networks (IJCNN 2021)'
authors: 'Jacek Komorowski, Monika Wysoczanska, and Tomasz Trzcinski'
abstract:"We present a discriminative multimodal descriptor based on a pair of sensor readings: a point cloud from a LiDAR and an image from an RGB camera. Our descriptor, named MinkLoc++, can be used for place recognition, re-localization and loop closure purposes in robotics or autonomous vehicles applications. We use late fusion approach, where each modality is processed separately and fused in the final part of the processing pipeline. The proposed method achieves state-of-the-art performance on standard place recognition benchmarks. We also identify dominating modality problem when training a multimodal descriptor. The problem manifests itself when the network focuses on a modality with a larger overfit to the training data. This drives the loss down during the training but leads to suboptimal performance on the evaluation set. In this work we describe how to detect and mitigate such risk when using a deep metric learning approach to train a multimodal neural network."
bibtex: "@INPROCEEDINGS{9533373,  
   author={Komorowski, Jacek and Wysoczańska, Monika and Trzcinski, Tomasz},  
   booktitle={2021 International Joint Conference on Neural Networks (IJCNN)},   
   title={MinkLoc++: Lidar and Monocular Image Fusion for Place Recognition},   
   year={2021},  
   doi={10.1109/IJCNN52387.2021.9533373}}"
pdf: "https://ieeexplore.ieee.org/document/9533373"
code: "https://github.com/jac99/MinkLocMultimodal"
---

