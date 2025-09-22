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
* Ph.D. in Electrical and Computer Engineering, Northeastern University, 2024
* Ph.D. in Mathematics, Northeastern University, 2025
* M.S. in Electrical and Computer Engineering, Northeastern University, 2019
* B.Sc. in Electrical Engineering, Sharif University of Technology, 2017

Experience
======
* Graduate Research Assistant (Sep 2017 - Aug 2024)
  * ECE Department, Northeastern University
  * Interpretability of black box models is often complicated and needs a prodigious amount of analysis. Our collaboration with Harvard medical school enables us to study the applicability of our methods on biomedical data, where we focus on developing novel learning algorithms to aid in the discovery of subtypes of a lung disease called Chronic Obstructive Pulmonary Disease (COPD).

* Graduate Research Assistant (Sep 2024 - Aug 2025)
  * Math Department, Northeastern University

* Researcher (May 2016 - Aug 2016)
  * Astar (Institute for Infocomm Research)
  * Efficient WLAN connection of a client, moving from one access point to another with sensor assistance and power-efficient real-time WLAN data transfer. Setting up a WiFi module and measuring the power profile of WL1837MOD WlinkTM. Using sensors (accelerometer) for Motion detection by machine learning algorithms. Using sensors for detecting heart rate and breath rate.

Honors And Awards
======
* Best Ph.D. Thesis Award
  * Poisson Geometry of Flag Varieties and Representation Theory of their Quantum Deformations, Northeastern Univeristy Mathematics Department, 2025
* [Ph.D. Spotlight](https://coe.northeastern.edu/news/phd-spotlight-aria-masoomi-phd24-computer-engineering-and-mathematics/)
  * Computer Engineering and Mathematics, Northeastern University, 2024
* [ICLR Spotlight Paper](https://openreview.net/forum?id=45Mr7LeKR9)
  * Explanations of Black-Box Models based on Directional Feature Interactions, 2022
* [NeurIPS Spotlight Paper](https://neurips.cc/virtual/2021/spotlight/27161)
  * Reliable Estimation of KL Divergence using a Discriminator in Reproducing Kernel Hilbert Space, 2021
* [Singapore International Pre-Graduate Award (SIPGA)](https://www.a-star.edu.sg/Scholarships/for-undergraduate-studies/singapore-international-pre-graduate-award-sipga)
  * A*STAR, 2016
* Among the best B.Sc. Thesis of Electrical Engineering Department
  * Sharif University of Technology, 2017
* Ranked 58th (top 0.5\%) in Iran University Entrance Exam, 2012

Publications
======
  <!-- <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  <ul class="cv-pubs">
  {% for post in site.publications reversed %}
    <li>
      <strong>
        {% if post.paperurl %}
          <a href="{{ post.paperurl }}" target="_blank">{{ post.title }}</a>
        {% else %}
          {{ post.title }}
        {% endif %}
      </strong>
      <br>
      {{ post.authors }}.
      <em>{{ post.publisher }}</em>,
      {{ post.date | date: "%Y" }}.
    </li>
  {% endfor %}
</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Skills
======
* Programming Languages
  * Python, MATLAB, C/C++, Maccaulay2, SageMath
* Data Science & Machine Learning
  * PyTorch, pandas, NumPy, scikit-learn, LaTeX
* Version Control
  * Git
  
Service and leadership
======
* Summer School Organizer
  * Machine Learning for Mathematicians and Physicists Summer School, Northeastern University, 2025
* Conference Reviewer
  * Advances in Neural Information Processing Systems (NeurIPS), 2025
  * Association for the Advancement of Artificial Intelligence (AAAI), 2024
  * Advances in Neural Information Processing Systems (NeurIPS), 2021
  * Society for Artificial Intelligence and Statistics (AISTATS), 2021
