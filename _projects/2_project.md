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

After 12 weeks of hard work, our team has implemented all the core features we outlined in our project plan and has conducted comprehensive testing to produce a high-quality product.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/VisionED_Product DEMO.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Our demo video
</div>



<!-- You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images. -->
<!-- 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>
 -->
<!-- 
The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div> -->
<!-- ```
{% endraw %} -->
