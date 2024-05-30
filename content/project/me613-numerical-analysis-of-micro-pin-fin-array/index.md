---
slides: test
url_pdf: "https://nbviewer.org/github/Pinetree-Lee/starter-hugo-academic/blob/main/assets/media/pdfs/IR_measurement_data_processing.pdf"
summary: Calibration of IR camera and simultaneous data processing for
  estimating local heat flux in pool boiling situation
authors:
  - Hansol Lee
url_video: "https://youtu.be/Ty_i0zoSwDk?si=JN6wEoTowtX1RXED"
date: 2024-05-28T10:39:32.082Z
categories:
  - Experiment
  - IR
external_link: ""
url_slides: ""
title: Hands-on experience on infrared (IR) measurement and data processing
subtitle: Calibration of IR camera and simultaneous data processing for
  estimating local heat flux in pool boiling situation
tags:
  - IR_thermometry
  - Data_processing
  - Code_development
  - Experiment
links:
  - icon: linkedin
    icon_pack: fab
    name: Follow
    url: https://www.linkedin.com/in/hansollee-research/
image:
  caption: Simultaneous measurement of boiling surface temperature and heat flux
  focal_point: Smart
  filename: featured.png
url_code: ""
---
W﻿hile working as an undergraduate research intern in Applied Heat Transfer Lab., I had a chance to have a hands-on experience on IR thermometry and its data processing. Specifically, I conducted calibration of an IR camera using black body radiation and data processing to estimate local heat flux in pool boiling situation using a given temperature distribution.

To calibrate the IR camera, first, the temperature within a cavity container whose inner sides are covered by black body materials is measured by the IR camera. For this cavity container, the surface temperature and the emissivity are assumed to be known. Based on the measurement, we can estimate the uncertainty of the IR camera itself and how the measured temperature is different from the known value. The result shows that the IR camera has a maximum error of 0.86 Celcius degree within the temperature range of 20 to 180 Celcius degree.

In the field of heat transfer, the data obtained from IR cameras often require the post-processing procedure such as estimating local heat flux from it. I did a short-term project to build an in-house code to estimate the local heat flux in a pool boiling situation using IR thermometry data. This work enables me to learn about solving transient 3D conduction problems and build a continuous movie form sequential solutions. The result of the work is shown in the link above this page.

