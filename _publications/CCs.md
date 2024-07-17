---
permalink: /publications/CCs
date: 6-07-2024
venue: 'arxiv'
thumbnail: /images/cc_teaser.png
title: "A Study of Test-time Contrastive Concepts for Open-world, Open-vocabulary Semantic Segmentation
abstract: "Recent VLMs, pre-trained on large amounts of image-text pairs to align both modalities, have opened the way to open-vocabulary semantic segmentation. Given an arbitrary set of textual queries, image regions are assigned the closest query in feature space. However, the usual setup expects the user to list all possible visual concepts that may occur in the image, typically all classes of benchmark datasets, that act as negatives to each other. We consider here the more challenging scenario of segmenting a single concept, given a textual prompt and nothing else. To achieve good results, besides contrasting with the generic 'background' text, we study different ways to generate query-specific test-time contrastive textual concepts, which leverage either the distribution of text in the VLM's training set or crafted LLM prompts. We show the relevance of our approach using a new, specific metric."

authors: '<a href="https://wysoczanska.github.io/">Monika Wysoczańska</a>, <a href="https://vobecant.github.io/">Antonin Vobecky</a>, Amaia Cardiel, <a href="https://cvlab.ii.pw.edu.pl/ttrzcins/"> Tomasz Trzciński </a>, <a href="https://imagine.enpc.fr/~marletr/"> Renaud Marlet </a>, <a href="https://abursuc.github.io/">Andrei Bursuc</a>, <a href="https://osimeoni.github.io/">Oriane Siméoni</a>'


bibtex: "@article{wysoczańska2024studycc,
      title={A Study of Test-time Contrastive Concepts for Open-world, Open-vocabulary Semantic Segmentation}, 
      author={Monika Wysoczańska and Antonin Vobecky and Amaia Cardiel and Tomasz Trzciński and Renaud Marlet and Andrei Bursuc and Oriane Siméoni},
      year={2024},
      journal={arXiv}, 
}"
code: "https://github.com/wysoczanska/"
project_page: "https://wysoczanska.github.io/"
pdf: "https://web3.arxiv.org/pdf/2407.05061"
---
