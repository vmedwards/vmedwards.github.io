---
layout: page
title: Verification of Emergent Behavior
description: Experimental verification of swarm behaviors is challenging, one way to address this is to use mixed reality. Existing theoretical work proposes robot formations emerge from time delay between inter robot communication. Our results using the Crazyflie platform demonstrate the existence of theoretically predicted emergent behaviors 
img: assets/img/nrl_mr.png
importance: 2
category: Past Research 
---

# Research Overview:
Performing experimental verification and validation (V&V) for robot swarms with large numbers of agents is challenging. As such, our theoretical insights far exceed our experimental results. The goal of this program was to bridge the scalability gap using new experimental tools, mainly: Mixed Reality. This method combines simulated and real robots to help achieve large numbers without needing all of the physical platforms. 

Mixed reality allows for early testing and evaluation of theoretical models, which improves field deployment readiness, and serves as a step in the experimental pipeline. In this work, we were specifically interested in the emergence of different collective behaviors which arise due to communication or sensor data processing time delay.

Two experimental platforms were studied including the Pelican Unmanned Ariel Vehicle (UAV) and the Crazyflie micro Ariel Vehicle.

<div class="container">
<div class="row justify-content-sm-center">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/pelican.jpg" title="pelican" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/crazyflie.jpg" title="crazyflie" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Left: Pelican UAV, Right: Bitcraze Crazyflie UAV
</div>
</div>


<p align="center">
<iframe width="420" height="315" src="https://www.youtube.com/embed/zuhuCXFaW5Y" frameborder="0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

<div class="caption">
This video demonstrates mixed reality used with 8 real and 16 simulated agents executing a known Ring behavior. The controller used has been theoretically studied and we know there are multiple different forms of emergent behavior. This result shows one such behavior.
</div>

Experimental results focused on demonstrating the ring emergent behavior, as well as demonstrating switching from one behavior to another, (Ring to Rotating behavior). For more details please consult the citations below.


<div class="publications">
<h2>Associated Publications </h2>
     {% bibliography -f papers -q @*[project=nrl_swarm]* %}
</div>

This work was done in collaboration with Dr. Jason Hindes, Dr. Ira B. Schwartz, Dr. Ioana Triandof, and Donald Sofge at the US Naval Research Laboratory. 

