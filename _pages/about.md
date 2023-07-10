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

I am a PhD student in Computer Vision and Machine Learning in the [Computer Vision Lab](https://cvlab.ii.pw.edu.pl/) of Warsaw University of Technology. My research revolves around Multimodal Learning, with particular focus on fine-grained tasks. I work under the supervision of [Tomasz Trzcinski](http://staff.ii.pw.edu.pl/~ttrzcins/). 

I obtained my Masters degree in Computer Science at Warsaw University of Technology and BSc from Wroclaw University of Science and Technology in Systems Engineering.


News
======
- 07/2023: I'm attending [Neuromatch Academy Summer School](https://academy.neuromatch.io/) to learn about Computational Neuroscience 🧠
- 04/2023: We're excited to organize [Women in Computer Vision Workshop at ICCV 2023 in Paris](https://sites.google.com/view/wicviccv2023)! Stay tuned!
- 01/2023: [EgoNN](https://github.com/jac99/Egonn) in [ICRA2023](https://www.icra2023.org/) as an oral presentation! 
- 12/2022: Our research proposal for OPUS 23/ST6 titled "Dynamic neural networks for efficient machine learning" received 3-year funding from Polish National Science Centre.
- 11/2022: I am attending NeurIPS 2022 and presenting our work during [SSL Workshop](https://sslneurips22.github.io/pages/accepted-paper.html).
- 10/2022: Our paper [Towards Unsupervised VQA: Do off-the-shelf features know how to reason?](https://arxiv.org/abs/2212.10292) got accepted to [NeurIPS 2022 Workshop: Self-Supervised Learning - Theory and Practice](https://sslneurips22.github.io/)! Thanks, Tom, Tomasz, and David!
- 09/2022: I received [Campus France](https://www.pologne.campusfrance.org/pl/program-stypendialny-sshn-na-pobyt-badawczy) scholarship for another 2-month visit in [IMAGINE team](http://imagine.enpc.fr/) of [Ecole des Ponts Paristech](http://www.enpc.fr/) in Paris this fall to work on unsupervised image representations for VQA with [David Picard](https://davidpicard.github.io/).
- 07/2022: Starting my summer research internship at Booking.com in Amsterdam!
- 03/2022: My project proposal got accepted to [NVIDIA Academic Hardware Grant Program](https://mynvidia.force.com/HardwareGrant/s/Application) and I received a gpu card to support my research. Thanks NVIDIA!
- 12/2021: [EgoNN](https://github.com/jac99/Egonn) got accepted to Robotics and Automation Letters (RA-L). Check the paper [here](https://ieeexplore.ieee.org/document/9645340).  

Publications
======
{% for post in site.publications reversed %}
  {% include archive-single-homepage.html %}
{% endfor %}
