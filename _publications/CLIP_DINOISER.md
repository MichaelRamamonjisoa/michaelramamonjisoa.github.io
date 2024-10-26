---
permalink: /publications/CLIP-DINOiser
date: 1-10-2024
venue: 'ECCV'
thumbnail: /images/clipdinoiser.gif
title: "CLIP-DINOiser: Teaching CLIP a few DINO tricks for open-vocabulary semantic segmentation"
abstract: "The popular CLIP model displays impressive zero-shot capabilities thanks to its seamless interaction with arbitrary text prompts. However, its lack of spatial awareness makes it unsuitable for dense computer vision tasks, e.g., semantic segmentation, without an additional fine-tuning step that often uses annotations and can potentially suppress its original open-vocabulary properties. Meanwhile, self-supervised representation methods have demonstrated good localization properties without human-made annotations nor explicit supervision. In this work, we take the best of both worlds and propose a zero-shot open-vocabulary semantic segmentation method, which does not require any annotations. We propose to locally improve dense MaskCLIP features, computed with a simple modification of CLIP's last pooling layer, by integrating localization priors extracted from self-supervised features. By doing so, we greatly improve the performance of MaskCLIP and produce smooth outputs. Moreover, we show that the used self-supervised feature properties can directly be learnt from CLIP features therefore allowing us to obtain the best results with a single pass through CLIP model. Our method CLIP-DINOiser needs only a single forward pass of CLIP and two light convolutional layers at inference, no extra supervision nor extra memory and reaches state-of-the-art results on challenging and fine-grained benchmarks such as COCO, Pascal Context, Cityscapes and ADE20k."

authors: '<a href="https://wysoczanska.github.io/">Monika Wysoczańska</a>, <a href="https://osimeoni.github.io/">Oriane Siméoni</a>, <a href="/about.html">Michael Ramamonjisoa</a>, <a href="https://abursuc.github.io/">Andrei Bursuc</a>, <a href="http://staff.ii.pw.edu.pl/~ttrzcins/"> Tomasz Trzciński </a>, <a href="https://ptrckprz.github.io/"> Patrick Pérez </a>'


bibtex: "@article{wysoczanska2024clipdino,<br>
          title     = {CLIP-DINOiser: Teaching CLIP a few DINO tricks for open-vocabulary semantic segmentation}, <br>
          author    = {Wysocza{\\'{n}}ska, Monika and <br>
               Sim{\\'{e}}oni, Oriane and <br>
               Ramamonjisoa, Micha{\\\"{e}}l and <br>
               Bursuc, Andrei and <br>
               Trzci{\\'{n}}ski, Tomasz and <br>
               P{\\'{e}}rez, Patrick}, <br>
          booktitle = {ECCV}, <br>
          year = {2024} <br>
}"

code: "https://github.com/wysoczanska/clip_dinoiser/"
project_page: "https://wysoczanska.github.io/CLIP_DINOiser/"
pdf: "https://arxiv.org/pdf/2312.12359.pdf"
---
