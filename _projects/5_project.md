---
layout: page
title: Adaptive Macoroscopic Ensemble Modeling and Control of Robot Teams
description: We introduce environmental feedback to macroscopic ensemble modeling and control of robot teams to adapt team assignment to changing environmental conditions. 
img: assets/img/centralized_adaptive_macro_model.png
importance: 1
category: Current Research
---

# Research Objective:

We want robot teams to monitor unknown dynamic environments.
This requires assigning robots to sampling locations, a variant of the Multi Robot Task Allocation (MRTA) problem.
Existing methods reduce the MRTA problem to a resource assignment problem and do not have the necessary scalability or fleixbility.
In contrast, macroscopic ensemble methods have the scalability but lack the necessary flexibility to adapt to environment changes.
This project aims to improve macroscopic ensemble methods in two critical ways.
Firstly, we will use environment model feedback to inform desired distributions of robots performing spatially distributed environmental monitoring tasks.
Secondly, we will leverage recent success in controlling higher order macroscopic ensemble moments to allow for small robot team size.
Together we show improved team-wide flexibility with evaluation done in simulation and experimentally. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/mASV_v2.png" title="Laboratory Testing Environment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
The miniature Autonomous Surface Vehicles v2 (mASV) are differential drive robots which use an Arduino Fio, XBee communication, and OptiTrack for global positioning. 
</div>

We experimentally verify our methods using the miniature Autonomous Surface Vehicles (mASVs) which are built in house at the ScALAR lab. Our testing environment is a 4m x 3m x 1.5m tank, equipped with 13 OptiTrack cameras, and the capability to make gyres in the tank. At any given time we can have upwards of 10 mASV in the tank performing different control strategies. Within the tank we have demonstrated heterogeneous teams using Crazyflie robots and mASV simultaneously.


## Relevant Publications: 

We currently have two papers under review.
Firstly, we introduced an adaptive macroscopic ensemble method which takes in environment feedback from a Gaussian Process Environment model (under review at IEEE RAL). Secondly, we present a distributed adpative macroscopic ensemble method that requires the addition of a communication task and an overhead unmanned aerial vehicle (under review at AAMAS '25). 

<div class="publications">
<h2>Associated Publications </h2>
     {% bibliography -f papers -q @*[project=adaptive_macro]* %}
</div>

This work is done in collaboration with Dr. Thales C. Silva and Dr. M. Ani Hsieh at the University of Pennsylvania GRASP lab. 