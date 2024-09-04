---
layout: page
title: ThermoHands
description: The first benchmark for evaluating egocentric 3D hand pose estimation using RGB, depth, NIR, and thermal imaging.
img: assets/img/multimodal_hands.png
importance: 1
category: MAPS Lab
related_publications: 
---

Sep 2023 - Jun 2024

<a href="https://github.com/LawrenceZ22/ThermoHands">Our official GitHub repo</a>

## Abstract

In this work, we present ThermoHands, a new benchmark for thermal image-based egocentric 3D hand pose estimation, aimed at overcoming challenges such as varying lighting conditions and obstructions (e.g., handwear). The benchmark includes a multi-view and multi-spectral dataset collected from 28 subjects performing hand-object and hand-virtual interactions under diverse scenarios, accurately annotated with 3D hand poses through an automated process. We introduce a new baseline method, THEFormer, utilizing dual transformer modules for effective egocentric 3D hand pose estimation in thermal imagery. Our experimental results highlight THEFormer's leading performance and affirm thermal imaging's effectiveness in enabling robust 3D hand pose estimation in adverse conditions.

## Dataset Details

We use the <a href="https://lawrencez22.github.io/projects/4_project/">Head-mounted Sensor Platform</a> to construct the first dataset comprising egocentric hand actions captured through RGB-D, IR, and thermal cameras.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/DatasetSceneSetup.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Dataset scene setup of ThermoHands
</div>

The 2.5D hand pose is semi-automatically annotated using <a href="https://github.com/CMU-Perceptual-Computing-Lab/openpose">OpenPose</a> on RGB-D images and is further optimized before being projected onto the thermal image frame.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/GTAnnotation.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Ground truth annotation of the ThermoHands dataset
</div>

We also evaluated this dataset using HTT (Wen et al., 2023) and our baseline method for thermal imaging, THEFormer; more details can be found in our paper.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/CrossSpectrumDemo.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Performance of HTT on our four spectrum modalities
</div>