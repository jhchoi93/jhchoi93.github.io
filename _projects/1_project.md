---
layout: page
title: RF-vital
description: RF-Based Health Monitoring from Moving Individuals
img: assets/img/RF-vital/overview.png
importance: 1
category: Wireless Health
---
<img src="https://img.shields.io/badge/-Wireless%20Health-brightgreen" height="30">&nbsp;&nbsp;<img src="https://img.shields.io/badge/-AI-blue" height="30">

## Overview
<p align="center"><img src="https://jhchoi93.github.io/assets/img/RF-vital/overview.png" width="700px"/></p>
**RF-vital** model learns the mapping from radio reflections to human respiration signal based on a novel multi-task adversarial learning  framework. Several test examples of our RF-vital model demonstrate the feasibility of recovering the fine respiration signs even under occluded, dark, and moving scenarios. 

Our RF-vital model outperforms the state-of-the-art video- and RF-based non-contact vital measurement approaches in static scenarios. Moreover, it continues to work properly in large motion scenarios, where the current methods fail completely. Our methods also can provide robust estimations, even in dark-light conditions and occlusions, enabling more realistic implementations of contactless health monitoring systems.
<br><br>

## Methodology
<p align="center"><img src="https://jhchoi93.github.io/assets/img/RF-vital/methodology.png" width="1050px"/></p>
The key idea is that the received radio signals retain both the reflections from human global motion (GM) and vital motion in a mixed form, while preserving the GM-only components at the same time. During training, our model leverages a novel multi-task adversarial learning framework to capture the mapping from radio signals to respiration while excluding the GM components in a self-supervised manner.
<br><br>

## Result Example
<p align="center"><img src="https://jhchoi93.github.io/assets/img/RF-vital/result.png" width="1050px"/></p>
<br><br>

## Demo Video
Coming soon.
<br><br>

## Paper
[**Remote Respiration Monitoring of Moving Person Using Radio Signals**](https://jhchoi93.github.io/assets/pdf/2022_ECCV_RFVital_main.pdf)  
Jae-Ho Choi, Ki-Bong Kang, and Kyung-Tae Kim  
*European Conference on Computer Vision* **(ECCV),** Oct 2022