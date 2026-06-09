---
short: 'EPFv2'
title: 'EPFv2'
thumbnail: /images/EPFv2.png
permalink: /publications/EPFv2
collection: publications
date: 14-08-2025
venue: 'CVPR 2026 (Spotlight)'
abstract: 'Egocentric 3D human motion estimation is essential for AR/VR experiences, yet remains challenging due to limited body coverage from the egocentric viewpoint, frequent occlusions, and scarce labeled data. We present EgoPoseFormer v2, a method that addresses these challenges through two key contributions: (1) a transformer-based model for temporally consistent and spatially grounded body pose estimation, and (2) an auto-labeling system that enables the use of large unlabeled datasets for training.The proposed model is fully differentiable, introduces identity-conditioned queries, multi-view spatial refinement, causal temporal attention, and supports both keypoints and parametric body representations under a constant compute budget.The proposed auto-labeling system scales learning to tens of millions of unlabeled frames via uncertainty-aware semi-supervised training. The system follows a teacher-student schema to generate pseudo-labels and guide training with uncertainty distillation, enabling the model to generalize to different environments. In experiments on the EgoBody3M benchmark, EgoPoseFormer v2 outperforms two state-of-the-art methods by 12.2% and 19.4% in accuracy, and reduces temporal jitter by 22.2% and 51.7%, respectively. Furthermore, our auto-labeling system additionally improves the wrist MPJPE by 13.1%'
authors: 'Zhenyu Li, Sai Kumar Dwivedi, Filip Maric, Carlos Chacon, Nadine Bertsch, Filippo Arcadu, Tomas Hodan, <b>Michael Ramamonjisoa</b>, Peter Wonka, Amy Zhao, Robin Kips, Cem Keskin, Anastasia Tkach, Chenhongyi Yang'
 
bibtex: "@InProceedings{Li_2026_CVPR, <br>
    author    = {Li, Zhenyu and Dwivedi, Sai Kumar and Maric, Filip and Chac\'on, Carlos and Bertsch, Nadine and Arcadu, Filippo and Hodan, Tomas and Ramamonjisoa, Michael and Wonka, Peter and Zhao, Amy and Kips, Robin and Keskin, Cem and Tkach, Anastasia and Yang, Chenhongyi}, <br>
    title     = {EgoPoseFormer v2: Accurate Egocentric Human Motion Estimation for AR/VR}, <br>
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, <br>
    month     = {June}, <br>
    year      = {2026}, <br>
    pages     = {21121-21131, <br>
}"

pdf: "https://arxiv.org/pdf/2603.04090"
---
