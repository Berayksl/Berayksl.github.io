---
title: "Robust Temporal Logic Planning Under Contingency Constraints"
collection: publications
category: conferences
permalink: /publication/2025-01-01-Robust-Temporal-Logic-Planning-Under-Contingency-Constraints
date: 2025-01-10
experiment_video: "https://www.youtube.com/watch?v=1m2m6nuocjQ"
paperurl: https://ieeexplore.ieee.org/abstract/document/11163815
authors: "Sadik Bera Yuksel, Azizollah Taheri, Yasin Yazicioglu, Derya Aksaray"
venue: 'In the proceedings of IEEE 21st International Conference on Automation Science and Engineering (CASE)'
media: /images/publications/robust_TL_planning.gif
bibtex: |
    @INPROCEEDINGS{11163815,
    author={Yüksel, Sadık Bera and Taheri, Azizollah and Yazıcıoğlu, Yasin and Aksaray, Derya},
    booktitle={2025 IEEE 21st International Conference on Automation Science and Engineering (CASE)}, 
    title={Robust Temporal Logic Planning Under Contingency Constraints}, 
    year={2025},
    volume={},
    number={},
    pages={30-36},
    keywords={Computational modeling;Contingency management;Stochastic processes;Optimal control;Switches;Planning;Safety;Logic;Robots;Faces},
    doi={10.1109/CASE58245.2025.11163815}}'

---
[Access paper here](https://ieeexplore.ieee.org/abstract/document/11163815){:target="_blank"}

In dynamic and uncertain environments, robots are often required not only to complete their primary tasks but also to be able to switch to a contingency mode that facilitates a safe and effective response in the face of an unpredictable event. In this paper, we address the problem of synthesizing optimal high-level control policies for a robot 1) to satisfy a desired task and 2) to be able to respond safely in the face of an unexpected event. We model the dynamics of the robot as a Stochastic Transition System. We express the primary task as a Time Window Temporal Logic (TWTL) specification, and we consider the contingency behavior to be reaching a safe region in at most k time steps with a probability greater than a desired threshold. We propose an automata-theoretic framework to compute optimal policies for task satisfaction and contingency behavior. While the contingency behavior is always ensured, the task satisfaction probability is maintained by minimally extending the mission horizon when necessary. We demonstrate the performance of the proposed method through simulations and experiments.
