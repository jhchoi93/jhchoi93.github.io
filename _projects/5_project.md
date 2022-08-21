---
layout: page
title: Micro-Doppler
description: Analysis of micro-movements based on radio micro-Doppler signatures
img: assets/img/micro-Doppler/main.png
importance: 3
category: Wireless Sensing
---
<img src="https://img.shields.io/badge/-Wireless%20Sensing-blueviolet" height="30">
&nbsp;&nbsp;<img src="https://img.shields.io/badge/-Signal%20Processing-lightgrey" height="30">

## *Micro-Doppler for Human Physiology*
<p align="center"><img src="https://jhchoi93.github.io/assets/img/micro-Doppler/vital.png" width="600px"/></p>

For effective construction of the calibrated EO-IR-SAR dataset. We developted a UAV-borne data acquisition system, which is capable of collecting temporally/spatially synchronized EO-IR images. In terms of SAR branch, we leveraged a cycle GAN framework to form corresponding fake-SAR images. 
<br><br>

## *Micro-Doppler for Human Voice*
<p align="center"><img src="https://jhchoi93.github.io/assets/img/micro-Doppler/voice.png" width="700px"/></p>

Based on the parallelized EfficientDet architecture, we comprehensively analyzed the detection/classification performance with respect to EO-IR-SAR fusion at each level, and designed an attention-based module to maximize the fusion gain.
<br><br>

## *Micro-Doppler for UAV targets*
<p align="center"><img src="https://jhchoi93.github.io/assets/img/micro-Doppler/UAV.png" width="1050px"/></p>

We collected our own dataset in two different conditions, which we refer to as RRMstatic and RRM-moving for stationary and moving conditions respectively. The RRM-static and RRM-moving datasets consist of synchronized FMCW radar echoes (i.e., RF signals), RGB videos, and ground-truth respiration signals, each of which was collected in a situation where a person faces forward while sitting in a chair or freely walks around the interior room, respectively. For static cases, we placed a chair about 70 cm away from the radar and camera, and then requested each participant to look straight ahead while holding her/his breath intermittently. For moving cases, we obtained FMCW radar reflections in moving scenarios where each person was allowed to walk around freely except for irregular movements such as a person running or falling, within a space of about 4 m × 5 m.
<br><br>

## Paper
**Fusion-rPPG: Video-RF Fusion Transformer for Advanced Remote Physiology Measurement**  
Jae-Ho Choi, Ki-Bong Kang, and Kyung-Tae Kim  
*AAAI Conference on Artificial Intelligence* **(AAAI)**, Submitted

[**Remote Respiration Monitoring of Moving Person Using Radio Signals**](https://jhchoi93.github.io/assets/pdf/2022_ECCV_RFVital_main.pdf)  
Jae-Ho Choi, Ki-Bong Kang, and Kyung-Tae Kim  
*European Conference on Computer Vision* **(ECCV),** Oct 2022

[**Analysis of Micro-Doppler Signatures of Small UAVs Based on Doppler Spectrum**](https://jhchoi93.github.io/assets/pdf/2021_TAES_UAV_mainOth.pdf)  
Ki-Bong Kang, Jae-Ho Choi, Byung-Lae Cho, Jung-Soo Lee, and Kyung-Tae Kim  
*IEEE Transactions on Aerospace and Electronic Systems* **(TAES)**, Oct 2021