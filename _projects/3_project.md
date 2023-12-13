---
layout: page
title: Distance-transform-based Arrow Direction Estimation
description: An innovative method for arrow direction estimation deployed in VisionED.
img: assets/img/dt_arrow.png
importance: 3
category: Coursework and Personal Research
---

Problem Intro

The primary challenge in estimating arrow directions lies in the variability of arrow shapes and sizes. Traditional contour-based arrow direction estimators often behave differently when analyzing arrows with contours of 7 sides compared to those with 9 sides. Inspired by <a href="https://ieeexplore.ieee.org/document/10048516" target="_blank">Wang, et al.</a>, generating a distance transform on edge images has been shown to improve the robustness of feature tracking. I independently designed an arrow direction estimator based on distance transform for the VisionED project. This method ensures accurate identification of arrow tips and tails in complex environments, assuming the arrows have a uniform texture.