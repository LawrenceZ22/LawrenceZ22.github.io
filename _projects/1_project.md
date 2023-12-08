---
layout: page
title: Thermal Calib
description: A modular chessboard for stereo camera calibration to be performed between thermal cameras and RGB/IR cameras.
img: assets/img/thermal_cali_board.png
importance: 1
category: MAPS Lab
related_publications: 
---
November, 2023

A modular calibration chessboard, designed in the style of OpenCV, is used for stereo calibration among thermal, RGB, and IR cameras. It consists of a black baseboard filled with white cubes that can be individually cooled or heated. This feature enables thermal cameras to capture grid images, which display identical chessboard corners as those in RGB and SWIR (Short Wave Infrared) images. The chessboard's grid patterns are detectable by both OpenCV and MATLAB. A significant advantage of this design is the absence of depth differences between the black and white squares in the images, contrasting with traditional designs that utilized hollowed boards.

Credit: The idea of having the baseboard as a whole came from Shikai Geng, School of Informatics, The Univerisity of Edinburgh.

<b>Further details and the model file of this board will be included in our ECCV 2024 submission for the thermal hand pose dataset.<b>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/thermal_calib_thermal.png" title="thermal" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/thermal_calib_rgb.png" title="rgb" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/thermal_calib_ir.png" title="ir" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<p>Chessboard images captured by thermal (left), RGB (middle), and IR (right) cameras at the same time and chessboard grids detected by MATLAB.<p>