---
short: 'CLIP-DIY'
title: 'CLIP Dense Inference Yields Open-Vocabulary Semantic Segmentation For-Free'
thumbnail: /images/clipdiy.png
collection: publications
permalink: /publications/CLIP-DIY
date: 04-01-2024
venue: 'WACV 2024'
authors: '<a href="https://wysoczanska.github.io/">Monika Wysoczańska</a>, <a href="/about.html">Michaël Ramamonjisoa</a>, Tomasz Trzciński, <a href="https://osimeoni.github.io/">Oriane Siméoni</a>'
abstract: "The emergence of CLIP has opened the way for open-world image perception. The zero-shot classification capabilities of the model are impressive but are harder to use for dense tasks such as image segmentation. Several methods have proposed different modifications and learning schemes to produce dense output. Instead, we propose in this work an open-vocabulary semantic segmentation method, dubbed CLIP-DIY, which does not require any additional training or annotations, but instead leverages existing unsupervised object localization approaches. In particular, CLIP-DIY is a multi-scale approach that directly exploits CLIP classification abilities on patches of different sizes and aggregates the decision in a single map. We further guide the segmentation using foreground/background scores obtained using unsupervised object localization methods. With our method, we obtain state-of-the-art zero-shot semantic segmentation results on PASCAL VOC and perform on par with the best methods on COCO."
bibtex: "@InProceedings{Wysoczanska_2024_WACV,  <br>
    author    = {Wysocza{\\'n}ska, Monika and Ramamonjisoa, Micha{\\\"e}l and Trzci{\\'n}ski, Tomasz and Sim{\\'e}oni, Oriane},   <br>
    title     = {CLIP-DIY: CLIP Dense Inference Yields Open-Vocabulary Semantic Segmentation For-Free},   <br>
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},   <br>
    month     = {January},   <br>
    year      = {2024},   <br>
    pages     = {1403-1413}   <br>
}"
code: "https://github.com/wysoczanska/clip-diy"
pdf: "https://arxiv.org/pdf/2309.14289.pdf"
---
