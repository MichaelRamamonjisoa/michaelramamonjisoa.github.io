---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}


Cześć!
======

I am a PhD student in Computer Vision and Machine Learning in the [Computer Vision Lab](https://cvlab.ii.pw.edu.pl/) of Warsaw University of Technology. I have also been lucky enough to spend 10 months as a visiting researcher in [valeo.ai](https://valeoai.github.io/blog/) team in Paris and I have had long term attachments with [Imagine group](http://imagine.enpc.fr/) of Ecole des Ponts.
My research revolves around Multimodal Learning. In particular, I'm interested in multimodal alignment, emphasising text + vision. I investigate it through means of various multimodal tasks. I work under the supervision of [Tomasz Trzcinski](https://cvlab.ii.pw.edu.pl/ttrzcins/). 

I obtained my master's degree in Computer Science at Warsaw University of Technology and my BSc from Wroclaw University of Science and Technology in Systems Engineering.


News
======
- 07/2024: Very excited to start as Student Researcher at Google DeepMind! I'll be working in the team led by [Cordelia Schmid](https://cordeliaschmid.github.io/) in Grenoble ⛰️
- 07/2024: Gave a talk on Open-Vocabulary Semantic Segmentation in my favorite academic lab - [Imagine](https://imagine-lab.enpc.fr/) ❤️
- 07/2024: Our study of single-query scenario for Open-world semantic segmentation availale on [arxiv](https://web3.arxiv.org/abs/2407.05061)!
- 07/2024: CLIP-DINOiser accepted to ECCV 2024 🍕 Very lucky to have worked with such great researchers: Oriane, Mic, Andrei, Tomasz and Patrick, thank you.
- 02/2024: Attending [AAAI-24 conference](https://aaai.org/aaai-conference/) in Vancouver to present my Booking.com internship [paper](https://arxiv.org/pdf/2310.19743.pdf).
- 01/2024: I presented [CLIP-DIY](https://arxiv.org/abs/2309.14289) at [WACV 2024](https://wacv2024.thecvf.com/) 🌴 Honored to be part of the Doctoral Consortium and be mentored by Michael Black!
- 10/2023: We organized [Women in Computer Vision Workshop at ICCV 2023 in Paris](https://sites.google.com/view/wicviccv2023) and it was something! Thanks to everyone who participated in the event!
- 07/2023: I graduated from [Neuromatch Academy Summer School](https://academy.neuromatch.io/) in Computational Neuroscience 🧠 It was a great experience!
- 01/2023: [EgoNN](https://github.com/jac99/Egonn) in [ICRA2023](https://www.icra2023.org/) as an oral presentation! 
- 12/2022: Our research proposal titled "Dynamic neural networks for efficient machine learning" received 3-year funding from the Polish National Science Centre. **2.5 years into my PhD and I have funding** - no more jobs on the side 👩‍🏭
- 10/2022: Our paper [Towards Unsupervised VQA: Do off-the-shelf features know how to reason?](https://arxiv.org/abs/2212.10292) got accepted to [NeurIPS 2022 Workshop: Self-Supervised Learning - Theory and Practice](https://sslneurips22.github.io/)! Thanks, Tom, Tomasz, and David!
- 09/2022: I received [Campus France](https://www.pologne.campusfrance.org/pl/program-stypendialny-sshn-na-pobyt-badawczy) scholarship for another 2-month visit in [IMAGINE team](http://imagine.enpc.fr/) of [Ecole des Ponts Paristech](http://www.enpc.fr/) in Paris this fall to work on unsupervised image representations for VQA with [David Picard](https://davidpicard.github.io/).
- 07/2022: Starting my summer research internship at Booking.com in Amsterdam!
- 03/2022: My project proposal got accepted to [NVIDIA Academic Hardware Grant Program](https://mynvidia.force.com/HardwareGrant/s/Application) and I received a GPU card to support my research. Thanks, NVIDIA!

Publications
======
{% for post in site.publications reversed %}
  {% include archive-single-homepage.html %}
{% endfor %}
