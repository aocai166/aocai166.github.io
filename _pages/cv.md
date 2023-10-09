---
layout: archive
title: "Bio"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computational Geophysics, Rice University, 2022
* B.S. in Geophysics, University of Science and Technology of China (USTC), 2016
* Exchange student, University of Göttingen, 2015

Work experience
======
* 06/2022- : Technical Geophysicist
  * Chevron Energy Technology Company
  * User support and technical development of scientific seismic imaging software, including Gaussian-beam migration (iGBMig)
and least-squares reverse time migration (LSRTM), for the sub-salt imaging problems.
  * HPC resource coordinator and manager for the sub-salt imaging team.

* 06/2020-08/2020: Machine Learning-Earth Science Intern
  * Chevron Energy Technology Company
  * Code extension of 3D U-nets to multi-class semantic image segmentation for shallow hazards detection in large-scale seismic
volumes. Hyperparameters tuning and comparative studies of Focal loss, Tversky loss, Dice loss, Focal-Tversky loss and their
combinations. Application on production volumes and quantified results based on validation accuracy, IoU, and Dice coefficient.

* 09/2019-12/2019: Machine Learning Engineer Intern
  * SLB Digtal Foundation Center
  * Comparative study of Generative Adversarial Networks (GAN) for seismic impedance inversion, including Cycle-GAN, Least-
square GAN, Wasserstein GAN and Wasserstein GAN-GP. Combining Wasserstein loss, cycle-consistent loss and gradient
penalty loss and developed Wasserstein Cycle-GAN for improved impedance inversion with an example on 3D seismic volume.

* 05/2019-08/2019: Machine Learning-Earth Science Intern
  * Chevron Energy Technology Company
  * Development of machine learning denoise (3D U-nets with dilated convolution) based seismic image optimization workflow.
  * Successful applications on Gulf of Mexico field seismic data (~TB scale 3D seismic digital data); created business impact.
  
Proficiencies & Skills
======
* Programming: Python; C, C++; Java; Fortran; MATLAB; Message Passing Interface (MPI); CUDA; Linux Shell.
* Machine Learning: Supervised Learning; Semi-supervised Learning; Neural Networks; TensorFlow; Keras; PyTorch.
* Relevant Coursework: Statistical Machine Learning; Deep Learning; Numerical Analysis; Numerical Optimization;
Topics in Inverse Problem; Computational Science (OpenMP, MPI, CUDA, OpenCL).

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* SEG, AGU, AAPG, Rice Badminton Club
