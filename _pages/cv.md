---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
redirect_to: /files/Bera_Yuksel_CV - (11.24.2025).pdf
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Engineering**, Northeastern University, Expected 2028
   
* **M.S. in Computer Engineering**, Northeastern University, 2025  
  
* **B.S. in Electrical and Electronics Engineering**, Bilkent University, 2023  


Experience
======
* **Northeastern University**, Boston, MA — *Graduate Research Assistant* (Advisor: Prof. Derya Aksaray), **Sep 2023 – Present**  
  * Conducting research on temporal-logic-constrained reinforcement learning that incorporates STL specifications as hard constraints to enhance safety and real-world applicability.
  * Developed a temporal-logic-guided motion planning framework with contingency constraints to improve robustness under uncertainty. :contentReference[oaicite:6]{index=6}  
  * Deployed the planning algorithm on a real drone in a GPS-denied environment, integrating perception, control, and runtime monitoring for autonomous task execution.

* **ASELSAN**, Ankara, Turkey — *Transmitter and Receiver Design Intern*, **2022**  
  * Designed a diplexer consisting of two RF bandpass filters with distinct operation bands using Keysight Genesys.
  * Created PCB layouts and manufactured the designed diplexer with lumped elements.
  * Analyzed S-parameters using a vector network analyzer to verify compliance with requirements.

* **HAVELSAN**, Ankara, Turkey — *Robotics and Autonomous Systems Intern*, **2021**  
  * Implemented autonomous navigation for a differential drive robot in simulation using ROS and Python.
  * Developed a face recognition application on Qualcomm Robotics RB5 using OpenCV and optimized for real-time inference on embedded hardware. :contentReference[oaicite:12]{index=12}

* **Bilkent University**, Ankara, Turkey — *Teaching Assistant*, **Fall 2020**  
  * Assisted students in CS115 (Introduction to Programming in Python) during lab hours, providing targeted educational support. :contentReference[oaicite:13]{index=13}


Skills
======
* **Programming Languages:** Python, MATLAB, Assembly 
* **Machine Learning & AI:** PyTorch, JAX, TensorFlow, NumPy, Pandas, Scikit-learn, OpenCV
* **Robotics & Control:** ROS, SLAM, motion planning, reinforcement learning, control systems 
* **Tools & Software:** Git, Docker, Linux, LTspice, Vivado, Diptrace


Publications
======
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

