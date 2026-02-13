---
layout: page
title: Adaptive Macroscopic Ensemble Modeling and Control of Robot Teams
description: We introduce environmental feedback to macroscopic ensemble modeling and control of robot teams to adapt team assignment to changing environmental conditions. 
img: assets/img/centralized_adaptive_macro_model.png
importance: 1
category: Current Research
---

# Research Objective:

We want robot teams to monitor unknown dynamic environments.
This requires assigning robots to sampling locations, a variant of the Multi Robot Task Allocation (MRTA) problem.
Existing methods reduce the MRTA problem to a resource assignment problem and do not have the necessary scalability or flexibility.
In biology, the ideal free distribution model is a population matching strategy which suggests that animals make weighted random resource selections based on perceived resource value.
This result suggests that animals make a resource selection which result in beneficial configurations for the population, where no better strategy exists for any one individual. 
Taking inspiration from biology, macroscopic ensemble methods naturally achieve population matching by letting robots make random task selections based on model parameters.
These methods have been shown to have scalability, but unlike their biological counterparts, macroscopic models for robot collectives lack the same flexibility to adapt to uncertain changing conditions.
This project aims to improve macroscopic ensemble methods in two critical ways.
Firstly, we will use environment model feedback to inform desired distributions of robots performing spatially distributed environmental monitoring tasks.
Secondly, we leverage the recent success of controlling higher order macroscopic ensemble moments to allow for small robot team size.
Together we show improved team-wide flexibility with evaluation done in simulation and experimentally. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mASV_v2.png" title="Laboratory Testing Environment" class="img-fluid rounded z-depth-1" %}

    </div>
</div>
<div class="caption">
The miniature Autonomous Surface Vehicles v2 (mASV) are differential drive robots which use an Arduino Fio, XBee communication, and OptiTrack for global positioning. 
</div>

We experimentally verify our methods using the miniature Autonomous Surface Vehicles (mASVs) which are built in house at the ScalAR lab. Our testing environment is a 4m x 3m x 1.5m tank, equipped with 13 OptiTrack cameras, and the capability to make gyres in the tank. At any given time we can have upwards of 10 mASV in the tank performing different control strategies. Within the tank we have demonstrated heterogeneous teams using Crazyflie robots and mASV simultaneously.


## Relevant Publications:

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/n7WnvdFIvLI?si=m9dmw7oqFu5e7gj6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<div class="caption">
In this video, we show the mixed reality experimental results for Adaptive Macroscopic Allocation to monitor spatiotemporal environments. The result is populations of robots that change based on the environment changes.   
</div>

The original model can be found in {% cite silva2022DARS %}. We have an extended abstract which discusses a distributed approach to the adaptive macroscopic ensemble allocation framework {% cite edwards2025distributed %}. 
Our work is currently under review at Advanced Intelligent Systems. The results of our experimental trials can be seen in the above video. Compared to standard adaptive sampling baselines we are able to monitor a wide range of spatiotemporal environments. 


This work is done in collaboration with Dr. Thales C. Silva and Dr. M. Ani Hsieh at the University of Pennsylvania GRASP lab.

