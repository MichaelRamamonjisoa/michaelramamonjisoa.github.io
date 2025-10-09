---
short: 'DINOtxt'
title: 'DINO.txt'
thumbnail: /images/dinotxt.png
permalink: /publications/DINOtxt
collection: publications
date: 13-06-2025
venue: 'Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)'
abstract: 'Self-supervised visual foundation models produce powerful embeddings that achieve remarkable performance on a wide range of downstream tasks. However, unlike vision-language models such as CLIP, self-supervised visual features are not readily aligned with language, hindering their adoption in open-vocabulary tasks. Our method unlocks this new ability for DINOv2, a widely used self-supervised visual encoder. We build upon the LiT training strategy, which trains a text encoder to align with a frozen vision model but leads to unsatisfactory results on dense tasks. We propose several key ingredients to improve performance on both global and dense tasks, such as concatenating the [CLS] token with the patch average to train the alignment and curating data using both text and image modalities. With these, we successfully train a CLIP-like model with only a fraction of the computational cost compared to CLIP while achieving state-of-the-art results in zero-shot classification and open-vocabulary semantic segmentation.'
authors: 'Cijo Jose, Théo Moutakanni, Dahyun Kang, Federico Baldassarre, Timothée Darcet, Hu Xu, Daniel Li, Marc Szafraniec, <b>Michaël Ramamonjisoa</b>, Maxime Oquab, Oriane Siméoni, Huy V. Vo, Patrick Labatut, Piotr Bojanowski'

bibtex: "@InProceedings{Jose_2025_CVPR, <br>
    author    = {Jose, Cijo and Moutakanni, Th\\'eo and Kang, Dahyun and Baldassarre, Federico and Darcet, Timoth\\'ee and Xu, Hu and Li, Daniel and Szafraniec, Marc and Ramamonjisoa, Micha\"el and Oquab, Maxime and Sim\\'eoni, Oriane and Vo, Huy V. and Labatut, Patrick and Bojanowski, Piotr}, <br>
    title     = {DINOv2 Meets Text: A Unified Framework for Image- and Pixel-Level Vision-Language Alignment}, <br>
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, <br>
    month     = {June}, <br>
    year      = {2025}, <br>
    pages     = {24905-24916} <br>
}"

code: "https://github.com/facebookresearch/dinov3/tree/main/dinov3/eval/text"
project_page: "https://github.com/facebookresearch/dinov3/tree/main/dinov3/eval/text"
pdf: "https://arxiv.org/pdf/2412.16334"
---
