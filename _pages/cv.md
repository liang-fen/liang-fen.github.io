---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Science and Technology (Pattern Recognition), Nanjing University of Science and Technology, Nanjing, China (in progress)
* B.S., Nanjing University of Science and Technology (please update years if needed)

Research Experience
======
* Graduate Research, School of Computer Science and Engineering, NJUST
  * Topic: Controlled medical image generation, esp. retinal fundus image synthesis
  * Work: SpaVAR — Spatial Control Visual Autoregressive model with scale-aligned vessel conditioning; multi-scale feature decoupling and dynamic convolutional condition encoder

Skills
======
* Python, PyTorch; Generative models (VAR, Diffusion); Medical image processing
* Fundus image analysis: vessel segmentation (U-Net), pseudo-label pipelines

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Contact
======
* Email: 1902946745@qq.com
* Nanjing University of Science and Technology, Nanjing 210094, China
