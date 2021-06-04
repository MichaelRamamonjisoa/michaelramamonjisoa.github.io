---
short: 'WaveletMonoDepth'
title: 'Single Image Depth Estimation using Wavelet Decomposition'
collection: publications
permalink: /publications/WaveletMonoDepth
thumbnail: /images/WaveletMonoDepth_thumbnail.gif
date: 19-06-2021
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)'
authors: '<a href="/about.html">Michaël Ramamonjisoa</a>, Michael Firman, Jamie Watson, Vincent Lepetit and Daniyar Turmukhambetov'
abstract: "We present a novel method for predicting accurate depths from monocular images with high efficiency. 
          This optimal efficiency is achieved by exploiting wavelet decomposition, which is integrated in a fully differentiable encoder-decoder architecture. 
          We demonstrate that we can reconstruct high-fidelity depth maps by predicting sparse wavelet coefficients. 
          In contrast with previous works, we show that wavelet coefficients can be learned without direct supervision on coefficients. 
          Instead we supervise only the final depth image that is reconstructed through the inverse wavelet transform. 
          We additionally show that wavelet coefficients can be learned in fully self-supervised scenarios, without access to ground-truth depth. 
          Finally, we apply our method to different state-of-the-art monocular depth estimation models, in each case giving similar or better results compared to the original model, while requiring less than half the multiply-adds in the decoder network."
bibtex: "@inproceedings{ramamonjisoa-2021-wavelet-monodepth,
          title     = {Single Image Depth Prediction with Wavelet Decomposition},
          author    = {Ramamonjisoa, Micha{\"{e}}l and
               Michael Firman and
               Jamie Watson and
               Vincent Lepetit and
               Daniyar Turmukhambetov},
          booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
          month = {June},
          year = {2021}
}"
    
code: "https://github.com/nianticlabs/wavelet-monodepth"
project_page: "https://github.com/nianticlabs/wavelet-monodepth"
pdf: "https://arxiv.org/pdf/2106.02022.pdf"
---

