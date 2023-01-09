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


Welcome to my webpage!
======

I am a PhD student in Computer Vision and Machine Learning in the [Computer Vision Lab](https://cvlab.ii.pw.edu.pl/) of Warsaw University of Technology. My research revolves around Multimodal Learning, with particular focus on complex reasoning tasks. I work under the supervision of [Tomasz Trzcinski](http://staff.ii.pw.edu.pl/~ttrzcins/). 

I received my Masters degree in Computer Science at Warsaw University of Technology and BSc from Wroclaw University of Science and Technology in Systems Engineering.


News
======
- 12/2022: Our research proposal for OPUS 23/ST6 titled "Dynamic neural networks for efficient machine learning" got 3-year funding.
- 11/2022: I am attending NeurIPS 2022 and presenting our work during [SSL Workshop](https://sslneurips22.github.io/pages/accepted-paper.html).
- 10/2022: Our paper [Towards Unsupervised VQA: Do off-the-shelf features know how to reason?](https://arxiv.org/abs/2212.10292) got accepted to [NeurIPS 2022 Workshop: Self-Supervised Learning - Theory and Practice](https://sslneurips22.github.io/)! Thanks Tom, Tomasz and David!
- 09/2022: I received [Campus France](https://www.pologne.campusfrance.org/pl/program-stypendialny-sshn-na-pobyt-badawczy) scholarship for another 2-month visit at ENPC in Paris.
- 07/2022: Starting my summer research internship at Booking.com in Amsterdam!
- 10/2021: [EgoNN](https://github.com/jac99/Egonn) got accepted to Robotics and Automation Letters (RA-L). Check the paper [here](https://ieeexplore.ieee.org/document/9645340).  
- 09/2021: I am visiting [IMAGINE team](http://imagine.enpc.fr/) of [Ecole des Ponts Paristech](http://www.enpc.fr/) in Paris this fall to work on unsupervised image representations for VQA with [David Picard](https://davidpicard.github.io/).
- 03/2021: Our work on [Lidar and Monocular Image Fusion for Place Recognition](https://github.com/jac99/MinkLocMultimodal) got accepted to IJCNN 2021. ([paper](https://ieeexplore.ieee.org/document/9533373))


Publications
======
{% for post in site.publications reversed %}
  {% include archive-single-homepage.html %}
{% endfor %}
