---
layout: page
title: Calibrated Mixed Reality
description: Mixed reality allows for the combination of robots and simulated agents to improve scalability. To improve the fidelity of these experiments data driven models are used to match performance.
img: assets/img/cmr_magic_robots.png
importance: 3
category: Past Research
---

# Summary:
While a member of the [APRIL Robotics Lab](https://april.eecs.umich.edu/) at the University of Michigan I worked on various projects. This included the Cybersees project which aimed to have a robot survey landfills, assisting in feature identification from overhead aerial images, as well as working on scalable experimentation for verification of collective behavior. In addition, I was completing course work which focused on core robotics skills including: Artificial Intelligence, Computer Vision, Simultaneous Localization and Mapping (SLAM), and Linear Control.

# Research Overview

"Simulation is doomed to succeed," was first coined by Rodney A. Brooks and Maja Mataric, published in "Real robots, real learning problems." in Robot Learning, Springer, 1993. This quote was the inspiration for the work we did at the University of Michigan. We knew from previous experiments in the lab that large robot teams required large engineering teams. Our objective was to lessen the engineering overhead by leveraging insights that real robots and simulated robots could be coupled together. However, there needs to be a way to ensure that the robots and the simulated agents were sufficiently similar to allow for fair performance analysis.

This work began as paper replication for Advanced Artificial Intelligence, EECS 692.  The paper was: Wu, Wencen, Iain D. Couzin, and Fumin Zhang. "Bio-inspired source seeking with no explicit gradient estimation." IFAC Proceedings Volumes 45.26 (2012): 240-245. We were able to achieve the results presented in the paper using the MAEbot platform. 

<div class="container">
<div class="row justify-content-sm-center">

    <div class="col-sm-8 mt-3 mt-md-0">
{% include figure.html path="assets/img/paper_rep.jpg" title="maebot" class="img-fluid rounded z-depth-1" %}	
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
{% include figure.html path="assets/img/maebot.jpg" title="maebot" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
</div>
<div class="caption">
Left: Results from the replication of Wu et al. We saw comparable performance on different robots using camera information as input. Right: MAEbot robotic platform
</div>


In addition to the replication, we extended this work using mixed reality to observe the impacts on large numbers of robots on the source seeking algorithm. What we observed experimentally is that more robots crowded the space and further work is needed to better accommodate large numbers of robots.

<p align="center">
<iframe width="420" height="315" src="https://www.youtube.com/embed/OyFo3LrQx1w" frameborder="0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

<div class="caption">
This video shows four MAEbots and various numbers of simulated robots performing source seeking. 
</div>

Beyond this we also considered larger platforms, where the dynamics of the robot interacting with the environment were more significant. The magic robots are golden retriever sized, skid-steer robots.
Using model fitting techniques and motor models we were able to find parameters to improve the fidelity of the simulated robots. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cmr_magic_robots.png" title="magic robot" class="img-fluid rounded z-depth-1" %}
    </div>
     <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/april_robot.jpg" title="magic robot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Left: Experimental demonstration of calibrated mixed reality, after a calibration was performed. Right: Magic Robot
</div>

<p align="center">
<iframe width="420" height="315" src="https://www.youtube.com/embed/eIinT30xru8" frameborder="0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

<div class="caption">
This video shows two Magic Robots in action performing a pre-specified trajectory, results are included which demonstrate that simulated agents perform better when calibration is used to fit model parameters. 
</div>

<div class="publications">
<h2>Associated Publications </h2>
     {% bibliography -f papers -q @*[project=mr_michigan]* %}
</div>



This work was done in collaboration with Dr. Peter Gaskell and Dr. Ed Olson at the University of Michigan. 