---
layout: page
title: Collaborative Macorscopic Ensemble Modeling and Control of Robot Teams
description: We present solutions to the multi robot task allocation (MRTA) problem by controlling robot-robot collaborations to inform time-varying team-wide objectives at the macrosocpic level. 
img: assets/img/combine_well_mixed.png
importance: 1
category: Current Research
---

# Research Objective:
We know that some dynamic environments have known periodic behavior, e.g., rivers with tidal shifts.
To properly monitor changing environments it is necessary to assign robots to sampling locations.
This is a variant of the Multi Robot Task Allocation (MRTA) problem in dynamic.
Solutions to this problem can be categorized as follows.
On one hand, microscopic solutions plan and control for individual robots and require expensive replanning when environment conditions change.
On the other hand, macroscopic solutions design team-wide objectives to distribute robots throughout an environment.
Macroscopic approaches have been shown to have nice analytical guarantees, scalability, and can be applied to heterogeneous robot collectives.
However, macroscopic methods often ignore robot-robot collaborations in favor of model simplicity.
As a result have been proven to be asympotically stable, i.e., given a desired distribution of robots we can find model parameters that will ensure those populations are achieved.
The problem we aim to address is to design a macroscopic ensemble modeling and control method for multi robot teams that controls time-varying populations of robots.
Our solution introduces robot-robot collaborations to the model which allow for the potential of time-varying distributions of robots in the workspace. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/mASVs.jpg" title="Laboratory Testing Environment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
The miniature Autonomous Surface Vehicles (mASV) are differential drive robots which use an Arduino Fio, XBee communication, and OptiTrack for global positioning. 
</div>

We experimentally verify our methods using the miniature Autonomous Surface Vehicles (mASVs) which are built in house at the ScALAR lab. Our testing environment is a 4m x 3m x 1.5m tank, equipped with 13 OptiTrack cameras, and the capability to make gyres in the tank. At any given time, we can have upwards of 10 mASV in the tank performing different control strategies. Within the tank we have demonstrated heterogeneous teams using Crazyflie robots and mASV simultaneously.


## Relevant Publications:
<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/well-mixed.png" title="well_mixed" class="img-fluid rounded z-depth-1" %}
    </div>
       <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/non_mixed_collab.jpg" title="well_mixed" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
 Left: An example of robot-robot collaboration. Right: An example of breaking the well-mixed assumption.
</div>

<div class="row justify-content-sm-center">
       <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/DARS_24_pic2.jpeg" title="well_mixed" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
 A photo of me presenting at the DARS '24 conference at Cornell Tech. Photo taken by Danna Ma. 
</div>

I recently presented at DARS '24 at Cornell Tech on collaborative macroscopic ensemble modeling and control of robot teams. We showed that our proposed model had the possibility of capturing time-varying populations and we introduced two interpretations of robot-robot collaboration. This work had an emphasis on studying the well-mixed assumption which is critical when using macroscopic ensemble methods. Our work was well recieved by the audience and I had a great round of questions after my talk!

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Tm8C4HIm440?si=KDC9k_nS4nYtefmX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<div class="caption">
This is the conference video to correspond with our IROS 2023 paper. 
</div>



I presented our work to IROS '23 in Detroit, MI. This work covered the application of collaborative macroscopic ensemble methods to environmental monitoring scenarios. Our solution avoids partitioning the environment and allows the robots to more flexibly perform the monitoring task.

<p align="center">
<iframe width="420" height="315" src="https://www.youtube.com/embed/X0QHgYM1s-g" frameborder="0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

<div class="caption">
This video shows mixed reality trials with 4 real miniature Autonomous Surface Vehicles (mASV) and 6 simulated robots. The result is a robot team performing different tasks (red, blue, or green lights) where the distributions change over time without changing the model parameters or re-planning. 
</div>

Our work presented at DARS '22 uses a nonlinear stochastic model to achieve time-varying distributions of robots which was a limitation of previous linear stochastic models. Our results suggest further work is needed to understand how macroscopic models can better incorporate feedback from the environment.  



<div class="publications">
<h2>Associated Publications </h2>
     {% bibliography -f papers -q @*[project=collaborative_macro]* %}
</div>

This work is done in collaboration with Dr. Thales C. Silva and Dr. M. Ani Hsieh at the University of Pennsylvania GRASP lab. 