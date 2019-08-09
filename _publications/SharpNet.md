---
id: 'SharpNet'
title: 'SharpNet: Fast and Accurate Recovery of Occluding Contours in Monocular Depth Estimation'
collection: publications
permalink: /publication/SharpNet
thumbnail: /images/SharpNet_thumbnail.gif
date: 07-08-2019
venue: 'arXiv'
authors: 'Michaël Ramamonjisoa and Vincent Lepetit'
abstract: "We introduce SharpNet, a method that predicts an accurate depth map for an input color image, with a particular attention to the reconstruction of occluding contours: Occluding contours are an important cue for object recognition, and for realistic integration of virtual objects in Augmented Reality, but they are also notoriously difficult to reconstruct accurately.
          For example, they are a challenge for stereo-based reconstruction methods, as points around an occluding contour are visible in only one image. 
          Inspired by recent methods that introduce normal estimation to improve depth prediction, 
          we introduce a novel term that constrains depth and occluding contours predictions. 
          Since ground truth depth is difficult to obtain with pixel-perfect accuracy along occluding contours, 
          we use synthetic images for training, followed by fine-tuning on real data. 
          We demonstrate our approach on the challenging NYUv2-Depth dataset, 
          and show that our method outperforms the state-of-the-art along occluding contours, 
          while performing on par with the best recent methods for the rest of the images. 
          Its accuracy along the occluding contours is actually better than the ''ground truth''
          acquired by a depth camera based on structured light. We show this by introducing a 
          new benchmark based on NYUv2-Depth for evaluating occluding contours in monocular reconstruction, 
          which is our second contribution."
bibtex: "@article{ramamonjisoa2019sharpnet,
    Title = {SharpNet: Fast and Accurate Recovery of Occluding Contours in Monocular Depth Estimation},
    Author = {Michael Ramamonjisoa and Vincent Lepetit},
    Journal = {arXiv preprint arXiv:1905.08598},
    Year = {2019}
    }"
code: "https://github.com/MichaelRamamonjisoa/SharpNet"
pdf: "https://arxiv.org/pdf/1905.08598.pdf"
---

