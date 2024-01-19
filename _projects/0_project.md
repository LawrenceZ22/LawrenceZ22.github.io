---
layout: page
title: Mult-model Egocentric Hand Pose Dataset
description: The first multi-model dataset for egocentric hand pose and action that includes RGB, IR and Thermal images.
img: assets/img/multimodel_hands.png
importance: 1
category: MAPS Lab
related_publications: 
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/multimodel_hands.png" title="multi-model hands" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

🌟Ongoing🌟, Since November 2023

We use the <a href="https://lawrencez22.github.io/projects/4_project/">Head-mounted Sensor Platform</a> to construct the first dataset comprising egocentric hand actions captured through RGB-D, IR, and thermal cameras. The 2.5D hand pose is semi-automatically annotated using <a href="https://github.com/CMU-Perceptual-Computing-Lab/openpose">OpenPose</a> on RGB-D images and is further optimized before being projected onto the thermal image frame. More details will be included in our ECCV24 submission.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rgb_hands.png" title="rgb" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/thermal_hands.png" title="thermal" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ir_hands.png" title="ir" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<p>Annotated 2.5D hand pose on RGB-D (left), thermal (middle) and IR (right) images when pouring a bottle of water into a mug.<p>