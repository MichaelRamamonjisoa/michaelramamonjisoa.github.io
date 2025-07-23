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

I am a Postdoctoral researcher at [valeo.ai](https://valeoai.github.io/blog/) working on groudning capabilities of VLMs. I completed my PhD in Computer Vision and Machine Learning in the [Computer Vision Lab](https://cvlab.ii.pw.edu.pl/) of [Warsaw University of Technology](https://eng.pw.edu.pl/). I have also been lucky enough to spend some time as a visiting PhD student in [valeo.ai](https://valeoai.github.io/blog/) team in Paris and with [Imagine group](http://imagine.enpc.fr/) of Ecole des Ponts. I also interned at [Google Deepmind](https://deepmind.google/) in the team led by [Cordelia Schmid](https://cordeliaschmid.github.io/) and at [Booking.com](https://www.booking.com/)

I like to work with different modalities and recently I've been interested in exploiting the complementarity of both exciting visual representation learning paradigms: self-supervision and image-text alignment for generalizable image backbones. I work under the supervision of [Tomasz Trzcinski](https://cvlab.ii.pw.edu.pl/ttrzcins/). 

I obtained my master's degree in Computer Science at Warsaw University of Technology and my BSc from Wroclaw University of Science and Technology in Systems Engineering.


News
======
- 07/2025: I am now a Postodoctroal redearcher in [valeo.ai](https://valeoai.github.io/blog/)!
- 05/2025: Contrastive Concepts accepted to TMLR [link](https://openreview.net/pdf?id=wyOv4kGkbU)!
- 02/2025: I've completed my internship at DeepMind and submitted my thesis. I am now on a job market, don't hesitate to reach out!
- 07/2024: I am very excited to start as a Student Researcher at Google DeepMind! I'll be working in the team led by [Cordelia Schmid](https://cordeliaschmid.github.io/) in Grenoble ⛰️
- 07/2024: Gave a talk on Open-Vocabulary Semantic Segmentation in my favourite academic lab - [Imagine](https://imagine-lab.enpc.fr/) ❤️
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
