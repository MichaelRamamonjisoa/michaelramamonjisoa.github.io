---
permalink: /publications/OVFact
date: 7-11-2025
venue: 'EMNLP'
thumbnail: /images/ovfact.png
title: "CLIP-DINOiser: Teaching CLIP a few DINO tricks for open-vocabulary semantic segmentation"
abstract: "Large vision-language models (VLMs) often struggle to generate long and factual captions. However, traditional measures for hallucination and factuality are not well suited for evaluating longer, more diverse captions and in settings where ground-truth human-annotated captions are unavailable. We introduce OVFact, a novel method for measuring caption factuality of long captions that leverages openvocabulary visual grounding and tool-based verification without depending on human annotations. Our method improves agreement with human judgments and captures both caption descriptiveness (recall) and factual precision in the same metric. Furthermore, unlike previous metrics, our reference-free method design enables new applications towards factuality-based data filtering. We observe models trained on an OVFact-filtered (2.5-5x less) subset of a largescale, noisy (VLM-generated) pretraining set meaningfully improve factuality precision without sacrificing caption descriptiveness across a range of downstream long caption benchmarks."

authors: '<a href="https://wysoczanska.github.io/">Monika Wysoczańska</a>, <a href="https://cs.stanford.edu/~shyamal/">Shyamal Buch</a>, <a href="https://anuragarnab.github.io/">Anurag Arnab</a>, <a href="https://cordeliaschmid.github.io/">Cordelia Schmid</a>'


bibtex: "@article{wysoczanska2025ovfact,
  title={OVFact: Measuring and Improving Open-Vocabulary Factuality for Long Caption Models},
  author={Wysocza{\'n}ska, Monika and Buch, Shyamal and Arnab, Anurag and Schmid, Cordelia},
  journal={EMNLP Findings},
  year={2025}
}"

code: "https://github.com/wysoczanska/ovfact/"
project_page: "https://wysoczanska.github.io/OVFact/"
pdf: "https://arxiv.org/pdf/2507.19262"
---
