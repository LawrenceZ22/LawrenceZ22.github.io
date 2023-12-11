---
layout: page
title: VisionED
description: A wearable visual sign recogniser for visually impaired users. 
img: assets/img/visioned_model.png
importance: 2
category: Coursework and Personal Research
giscus_comments: true
---

This project was the coursework of undergraduate course: System Design Project (INFR09032) at School of Informatics, The University of Edinburgh. The project team members are: Lea Andrusz, Ze Cao, Euan Chalmers, Jason Dialdestoro, Allison Jia, Mason Wan, Zhuoning Wu and <b> Lawrence Zhu </b>.

Project Abstrct:

VisionED is a headset designed for people with sight impairments to enhance their perception of indoor environments. 

Using trained machine learning models, our device can detect 8 common indoor signs, such as ’exit’ and ’wet floor’, and notify the user of these with a text-to-speech audio description. The location of an object relative to the user is conveyed using spatial audio beeps. Additional functionality includes reading text to the user and alerting them of the distance to the nearest solid objects.

Following multiple iterations of hardware designs, we have produced a physical prototype designed to ensure comfort for the user with shoulder pads to distribute the weight of the hardware components. The camera and depth detection sensors are mounted on glass frames to provide all audio cues corresponding to where the user faces as they turn their head. Buttons have been added to allow for easy changing of the audio volume as well as switching between different detection modes (sign detection, text detection and distance measurement). 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/VisionED_Product DEMO.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Our demo video
</div>