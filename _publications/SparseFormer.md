---
short: 'SparseFormer'
title: 'SparseFormer: Attention-based Depth Completion Network'
collection: publications
permalink: /projects/SparseFormer
thumbnail: /images/sparseformer.png
date: 19-06-2022
venue: 'International Conference on Computer Vision (ICCV) Workshop on 3D Reconstruction in the Wild'
authors: '<a href="https://frederikwarburg.github.io/index.html">Frederik Warburg</a>, <a href="/about.html">Micha\"el Ramamonjisoa</a>, and <a href="https://m.lopezantequera.com/">Manuel López-Antequera</a>'
abstract: "Most pipelines for Augmented and Virtual Reality estimate the ego-motion of the camera by creating a map of
sparse 3D landmarks. In this paper, we tackle the problem of depth completion, that is, densifying this sparse 3D
map using RGB images as guidance. This remains a challenging problem due to the low density, non-uniform and
outlier-prone 3D landmarks produced by SfM and SLAM
pipelines. We introduce a transformer block, SparseFormer,
that fuses 3D landmarks with deep visual features to produce dense depth. The SparseFormer has a global receptive
field, making the module especially effective for depth completion with low-density and non-uniform landmarks. To
address the issue of depth outliers among the 3D landmarks,
we introduce a trainable refinement module that filters outliers through attention between the sparse landmarks"
bibtex: "@article{warburg2022sparseformer, <br>
    Title = {SparseFormer: Attention-based Depth Completion Network}, <br>
    Author = {F. Warburg, M. Ramamonjisoa and M.L. Antequera}, <br>
    Journal = {CV4AR Workshop at The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, <br>
    Year = {2022}<br>
    }"
pdf: "https://arxiv.org/pdf/2206.04557.pdf"
---
