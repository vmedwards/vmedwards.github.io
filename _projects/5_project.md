---
layout: page
title: USV River Deployments
description: Deploying Unmanned Surface Vehicles on the Schuylkill River in Philadelphia PA to collect data about the health of the river. 
img: assets/img/river_project_group_shot.jpg
importance: 1
category: Current Research 
---

# Research Objective:
The [ScalAR Lab](https://scalar.seas.upenn.edu/) has two Unmanned Surface Vehicles (USV): one Clearpath Heron and one USV built in house. These robots are deployed in the Schuylkill River in Philadelphia PA. Various sensors are included onboard including: depth sensors, water quality sensors, and cameras. The aim is to collect data about the health of the river at a higher density than can currently be collected by a scientist. This involves having the robot exist in unstructured and complex environments which requires novel solutions. 

# Recent Work:
Each year, field deployments start in early May and end in late August. These deployments involve large teams, anywhere from 8 to a minimum of 3 people to deploy the systems safely. We can have anywhere from 5 to 12 field deployments in the summer. This is weather dependent. 

### Summer of 2022
The summer of 2022 the USV project was taken over by Alice Kate Li, an ESE PhD student. The objective for the summer was to continue to collect more data about the river and expand our capabilities to two autonomous surface vehicles. We had successful runs using both boats collecting many different types of data. During some of these deployments I was able to act as the safety kayaker and had a great time working with the robots up close and personal on the water. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/team_lead_alice.jpg" title="team_lead" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Team lead Alice Kate Li running the base station for the boat deployments. 
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/group_on_dock.jpg" title="group" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Group effort, from left to right: Yue, Alice, Jasleen, Maël, Bharg
</div>

<div class="container">
<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/double_boats.jpg" title="double_boats1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm-6 mt-3 mt-md-0">
	{% include figure.html path="assets/img/me_and_robots.jpg" title="double_boats2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</div>
<div class="caption">
Me and the big ASV and the Heron during a field deployment
</div>


### Summer of 2021
Getting the Clearpath Heron in working order after a full year off the water due to the COVID-19 pandemic. We had a successful season collecting depth data of the river bed autonomously. My role was to help setup the Gazebo simulation, update sensor packages for the addition of a VectorNav IMU, running the base station during deployments, and processing data collected.

<div class="container">
<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/work_in_pennovation.jpg" title="work1" class="img-fluid rounded z-depth-1" %}
    </div>
     <div class="col-sm-6 mt-3 mt-md-0">
	{% include figure.html path="assets/img/work_on_dock.jpg" title="work2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</div>
<div class="caption">
Left: Me, Fernando Caldera, and Michael Anoruo working in the Pennovation building preparing for a river deployment. Right: I am working on the dock fixing a problem with the boat. 
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
	{% include figure.html path="assets/img/boat_in_water.jpg" title="work3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
The boat successfully on the river with Michael Anoruo as safety Kayaker.  
</div>


<div class="publications">
<h2>Associated Publications </h2>
     {% bibliography -f papers -q @*[project=river]* %}
</div>

This work is done in collaboration with many students, post docs, and PIs in the ScalAR lab. 