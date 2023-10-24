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

I am a PhD student in Computer Vision and Machine Learning in the [Computer Vision Lab](https://cvlab.ii.pw.edu.pl/) of Warsaw University of Technology. My research revolves around Multimodal Learning. In particular, I'm interested in multimodal alignment, both in the brain, and deep learning models. I investigate it through the means of various multimodal tasks. I work under the supervision of [Tomasz Trzcinski](http://staff.ii.pw.edu.pl/~ttrzcins/). 

I obtained my Masters's degree in Computer Science at Warsaw University of Technology and my BSc from Wroclaw University of Science and Technology in Systems Engineering.


News
======
- 10/2023: Woah! [CLIP-DIY](https://arxiv.org/abs/2309.14289) got accepted to [WACV 2024](https://wacv2024.thecvf.com/)! Thank you Michael and Oriane ❤️ Polish dumplings as a teaser bring luck 🥟
- 10/2023: My Booking.com internship paper was accepted to IAAI-24 (AAAI - Innovative Applications of Artificial Intelligence)! Huge thanks to the whole Booking Content Intelligence team ❤️ We'll soon share the paper on arxiv!
- 10/2023: We organized [Women in Computer Vision Workshop at ICCV 2023 in Paris](https://sites.google.com/view/wicviccv2023) and it was something! Thanks everyone who participated in the event!
- 07/2023: I graduated from [Neuromatch Academy Summer School](https://academy.neuromatch.io/) in Computational Neuroscience 🧠 It was a great experience!
- 01/2023: [EgoNN](https://github.com/jac99/Egonn) in [ICRA2023](https://www.icra2023.org/) as an oral presentation! 
- 12/2022: Our research proposal for OPUS 23/ST6 titled "Dynamic neural networks for efficient machine learning" received 3-year funding from Polish National Science Centre.
- 10/2022: Our paper [Towards Unsupervised VQA: Do off-the-shelf features know how to reason?](https://arxiv.org/abs/2212.10292) got accepted to [NeurIPS 2022 Workshop: Self-Supervised Learning - Theory and Practice](https://sslneurips22.github.io/)! Thanks, Tom, Tomasz, and David!
- 09/2022: I received [Campus France](https://www.pologne.campusfrance.org/pl/program-stypendialny-sshn-na-pobyt-badawczy) scholarship for another 2-month visit in [IMAGINE team](http://imagine.enpc.fr/) of [Ecole des Ponts Paristech](http://www.enpc.fr/) in Paris this fall to work on unsupervised image representations for VQA with [David Picard](https://davidpicard.github.io/).
- 07/2022: Starting my summer research internship at Booking.com in Amsterdam!
- 03/2022: My project proposal got accepted to [NVIDIA Academic Hardware Grant Program](https://mynvidia.force.com/HardwareGrant/s/Application) and I received a GPU card to support my research. Thanks, NVIDIA!

Publications
======
{% for post in site.publications reversed %}
  {% include archive-single-homepage.html %}
{% endfor %}
