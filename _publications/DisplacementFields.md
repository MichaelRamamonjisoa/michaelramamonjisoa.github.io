---
short: 'DispFields'
title: 'Predicting Sharp and Accurate Occlusion Boundaries in Monocular Depth Estimation Using Displacement Fields'
collection: publications
permalink: /publications/DisplacementFields
thumbnail: /images/DisplacementFields_thumbnail.gif
date: 16-06-2020
venue: 'Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)'
authors: '<a href="/about.html">Michaël Ramamonjisoa</a><sup>*</sup>, Yuming Du<sup>*</sup> and Vincent Lepetit <br> <small><i><sup>* Denotes equal contribution.</sup></i></small>'
abstract: "Current methods for depth map prediction from monocular images tend to predict
  smooth, poorly  localized contours for  the occlusion boundaries in  the input
  image.   This is  unfortunate as  occlusion boundaries  are important  cues to
  recognize objects, and as  we show, may lead to a way  to discover new objects
  from scene  reconstruction.  To improve  predicted depth maps,  recent methods
  rely on various  forms of filtering or predict an  additive residual depth map
  to refine a  first estimate.  We instead  learn to predict, given  a depth map
  predicted  by some  reconstruction method,  a  2D displacement  field able  to
  re-sample pixels around the occlusion boundaries into sharper reconstructions.
  Our method can be applied to the  output of any depth estimation method and is
  fully  differentiable,  enabling  end-to-end  training.   For  evaluation,  we
  manually annotated  the occlusion  boundaries in  all the  images in  the test
  split of popular  NYUv2-Depth dataset. We show that our  approach improves the
  localization of occlusion boundaries  for all state-of-the-art monocular depth
  estimation   methods   that    we   could   evaluate,   without  degrading  the  depth
  accuracy for the rest of the images."
bibtex: "@article{ramamonjisoa2020dispnet, <br>
    Title = {Predicting Sharp and Accurate Occlusion Boundaries in Monocular Depth Estimation Using Displacement Fields}, <br>
    Author = {M. Ramamonjisoa and Y. Du and V. Lepetit}, <br>
    Journal = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)}, <br>
    Year = {2020}<br>
    }"
code: "https://github.com/dulucas/Displacement_Fields"
project_page: /projects/DisplacementFields
pdf: "https://arxiv.org/pdf/2002.12730.pdf"
---

