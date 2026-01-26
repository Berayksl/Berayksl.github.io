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
* **Northeastern University**, Boston, MA  
  **Ph.D. in Computer Engineering** (GPA: 4.0/4.0), *Expected May 2028*  
  Relevant Coursework: Robotic Sensing and Navigation, Reinforcement Learning, Mobile Robotics, Advances in Deep Learning, Verifiable Machine Learning, Linear System Analysis, Formal Methods for Dynamical Systems :contentReference[oaicite:3]{index=3}

* **Bilkent University**, Ankara, Turkey  
  **B.S. in Electrical and Electronics Engineering**, *June 2023*  
  Relevant Coursework: Introduction to Machine Learning, Microprocessors, Natural Language Processing :contentReference[oaicite:4]{index=4}


Experience
======
* **Northeastern University**, Boston, MA — *Graduate Research Assistant* (Advisor: Prof. Derya Aksaray), **Sep 2023 – Present**  
  * Conducting research on temporal-logic-constrained reinforcement learning that incorporates STL specifications as hard constraints to enhance safety and real-world applicability. :contentReference[oaicite:5]{index=5}  
  * Developed a temporal-logic-guided motion planning framework with contingency constraints to improve robustness under uncertainty. :contentReference[oaicite:6]{index=6}  
  * Deployed the planning algorithm on a real drone in a GPS-denied environment, integrating perception, control, and runtime monitoring for autonomous task execution. :contentReference[oaicite:7]{index=7}

* **ASELSAN**, Ankara, Turkey — *Transmitter and Receiver Design Intern*, **Jul – Aug 2022**  
  * Designed a diplexer consisting of two RF bandpass filters with distinct operation bands using Keysight Genesys. :contentReference[oaicite:8]{index=8}  
  * Created PCB layouts and manufactured the designed diplexer with lumped elements. :contentReference[oaicite:9]{index=9}  
  * Analyzed S-parameters using a vector network analyzer to verify compliance with requirements. :contentReference[oaicite:10]{index=10}

* **HAVELSAN**, Ankara, Turkey — *Robotics and Autonomous Systems Intern*, **Jun – Aug 2021**  
  * Implemented autonomous navigation for a differential drive robot in simulation using ROS and Python. :contentReference[oaicite:11]{index=11}  
  * Developed a face recognition application on Qualcomm Robotics RB5 using OpenCV and optimized for real-time inference on embedded hardware. :contentReference[oaicite:12]{index=12}

* **Bilkent University**, Ankara, Turkey — *Teaching Assistant*, **Sep 2019 – Jan 2020**  
  * Assisted students in CS115 (Introduction to Programming in Python) during lab hours, providing targeted educational support. :contentReference[oaicite:13]{index=13}


Skills
======
* **Programming Languages:** Python, MATLAB, Assembly :contentReference[oaicite:14]{index=14}  
* **Machine Learning & AI:** PyTorch, JAX, TensorFlow, NumPy, Pandas, Scikit-learn, OpenCV :contentReference[oaicite:15]{index=15}  
* **Robotics & Control:** ROS, SLAM, motion planning, reinforcement learning, control systems :contentReference[oaicite:16]{index=16}  
* **Tools & Software:** Git, Docker, Linux, LTspice, Vivado, Diptrace, Proteus 8 :contentReference[oaicite:17]{index=17}



Publications
======
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

