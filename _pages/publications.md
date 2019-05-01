---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
- [Learning Complex Dexterous Manipulation with Deep Reinforcement Learning and
Demonstrations](https://sites.google.com/view/deeprl-dexterous-manipulation), V. Kumar, A. Rajeswaran, A. Gupta, G. Vezzani, E. Todorov, S. Levine,
 Robotics: Science and Systems (RSS), 2018.
 - [Improving Superquadric Modeling and Grasping with Prior on Object Shapes](http://lornat75.github.io/papers/2018/vezzani-icra.pdf), G. Vezzani, U. Pattacini,
 G. Pasquale and L. Natale,  IEEE International Conference on Robotics and Automation (ICRA) 2018.
  - [Markerless visual servoing on unknown objects for humanoid robot platforms](https://arxiv.org/pdf/1710.04465.pdf), C. Fantacci, G. Vezzani, U. Pattacini, V. Tikhanoff  and L. Natale,  IEEE International Conference on Robotics and Automation (ICRA) 2018.
  - [Real-time pipeline for object modeling and grasping pose selection via superquadric functions](https://www.frontiersin.org/articles/10.3389/frobt.2017.00059/full), G. Vezzani,and L. Natale, submitted to the Frontiers topic "Building the iCub Mindware: Open-source Software for Robot Intelligence and Autonomy", 4, 59, 2017.
 - [A Novel Pipeline for Bi-manual Handover Task](https://www.tandfonline.com/doi/abs/10.1080/01691864.2017.1380535), G. Vezzani, M. Regoli, U. Pattacini
 and L. Natale, Special issue on Advanced Manipulation, Advanced Robotics, 1-14, 2017.
  - [Memory unscented particle filter for 6-DOF tactile localization](https://arxiv.org/pdf/1607.02757.pdf), G. Vezzani, U. Pattacini,
 G. Battistelli, L. Chisci, and L. Natale, IEEE Transaction on Robotics vol. 33 n. 5 pag. 1139-1155, October 2017.
 - [A Grasping Approach Based on Superquadric Models](http://lornat75.github.io/papers/2017/vezzani-icra.pdf), G. Vezzani, U. Pattacini, and L.
   Natale, in _IEEE International Conference on Robotics and Automation_, pp. 1579-1586, Singapore, 2017.
- [A Novel Bayesian Filtering Approach to Tactile Object Recognition](http://lornat75.github.io/papers/2016/vezzani-humanoids.pdf), G. Vezzani, N.
 Jamali , U. Pattacini , G. Battistelli, L. Chisci, and L. Natale, IEEE International Conference
 on Humanoid Robotics, pp. 256 - 263, Cancun, Mexico, 2016.  


  You can also find my articles on <u><a href=https://scholar.google.it/citations?user=Zlpuln8AAAAJ&hl=it>my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
