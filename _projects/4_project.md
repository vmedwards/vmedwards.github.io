---
layout: page
title: Heterogeneous Robotic Swarms
description: Segregation of heterogeneous robotic swarms is a necessary step before performing a new task.
img: assets/img/seg.png
importance: 3
category: Past Research 
---

# Research Overview
Swarming systems consist of many robots, typically with simple capabilities or behaviors that when functioning together achieve more than any individual agent could achieve. There are many examples from nature including: bees, ants, schooling fish, and even crowds of people express emergent behavior. When we observe different types of agents working together, or heterogeneous swarms, we know from natural examples that some type of organization or ability to self segregate is important. This research project aimed to write a control law which would segregate a swarm of heterogeneous robots. We formulated the problem using convex optimization and were able to prove segregation was achieved for idealized point robots.

Experimental results were demonstrated on E-Puck robots in the [VERLab](https://www.verlab.dcc.ufmg.br/), at the Federal University of Minas Gerais by Paulo Rezeck. 


<div class="publications">
<h2>Associated Publications </h2>
     {% bibliography -f papers -q @*[project=swarm_segregation]* %}
</div>

This work was done in collaboration with Dr. M Ani Hsieh at Drexel University, and Dr. Luiz Chaimowicz and Paulo Rezeck at the Federal University of Minas Gerais. 