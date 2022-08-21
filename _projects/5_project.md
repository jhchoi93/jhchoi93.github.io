---
layout: page
title: Sensor Fusion
description: Developing/analyzing fusion algorithms of multi-modal inputs
img: assets/img/Sensor-Fusion/main.png
importance: 3
category: Sensor Fusion
---
<img src="https://img.shields.io/badge/-Sensor%20Fusion-ff69b4" height="30">&nbsp;&nbsp;<img src="https://img.shields.io/badge/-AI-blue" height="30">

## *Aerial Detection/Classification from EO-IR-SAR Imagery*<hr>
### Dataset
<p align="center"><img src="https://jhchoi93.github.io/assets/img/Sensor-Fusion/eo-ir-sar_dataset.png" width="700px"/></p>

For effective construction of the calibrated EO-IR-SAR dataset. We developted a UAV-borne data acquisition system, which is capable of collecting temporally/spatially synchronized EO-IR images. In terms of SAR branch, we leveraged a cycle GAN framework to form corresponding fake-SAR images. 


### Methodology
<p align="center"><img src="https://jhchoi93.github.io/assets/img/Sensor-Fusion/eo-ir-sar_result.png" width="1050px"/></p>

Based on the parallelized EfficientDet architecture, we comprehensively analyzed the detection/classification performance with respect to EO-IR-SAR fusion at each level, and designed an attention-based module to maximize the fusion gain.
<br><br>

## *Video-RF Fusion for Contactless Health Monitoring*<hr>
### Dataset
<p align="center"><img src="https://jhchoi93.github.io/assets/img/Sensor-Fusion/video-rf_dataset.png" width="600px"/></p>

We collected our own dataset in two different conditions, which we refer to as RRMstatic and RRM-moving for stationary and moving conditions respectively. The RRM-static and RRM-moving datasets consist of synchronized FMCW radar echoes (i.e., RF signals), RGB videos, and ground-truth respiration signals, each of which was collected in a situation where a person faces forward while sitting in a chair or freely walks around the interior room, respectively. For static cases, we placed a chair about 70 cm away from the radar and camera, and then requested each participant to look straight ahead while holding her/his breath intermittently. For moving cases, we obtained FMCW radar reflections in moving scenarios where each person was allowed to walk around freely except for irregular movements such as a person running or falling, within a space of about 4 m × 5 m.

### Methodology
<p align="center"><img src="https://jhchoi93.github.io/assets/img/Sensor-Fusion/video-rf_framework.png" width="1050px"/></p>

For complete utilization of the complementarity of RGB and RF, we present a novel network architecture, dubbed fusion-rPPG network, which employs both video and RF reflections for physiological measurement. To this end, our end-to-end fusion-rPPG network establishes an encoding branch matching the specific domain knowledge of each sensor, leveraging temporal shift convolutional attention network (TS-CAN) for the visual domain and time-Doppler representation-based 2D convolutional module for the radio domain. Furthermore, we introduce a transformer-based multi-level fusion strategy that aligns domain discrepancy while guaranteeing complementary/adaptive fusion from each sensory branch.

### Demo Video
Coming soon.
<br><br>

## Paper<hr>
**Fusion-rPPG: Video-RF Fusion Transformer for Advanced Remote Physiology Measurement**  
Jae-Ho Choi, Ki-Bong Kang, and Kyung-Tae Kim  
*AAAI Conference on Artificial Intelligence* **(AAAI)**, Submitted

[**Fusion of Target and Shadow Regions for Improved SAR ATR**](https://ieeexplore.ieee.org/document/9751685)  
Jae-Ho Choi, Myung-Jun Lee, Nam-Hoon Jeong, Geon Lee, and Kyung-Tae Kim  
*IEEE Transactions on Geoscience and Remote Sensing* **(TGRS)**, Apr 2022