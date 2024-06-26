---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently an Assistant Professor in the School of Engineering at the University of Warwick. Prior to this, I was a Research Fellow at Warwick working on the core research project of the EPSRC [Supergen ORE Hub](https://www.supergen-ore.net). I obtained bachelor’s degree in Mechanical Engineering from Tsinghua University in 2015, and master’s degree in Mechanical Engineering from Tsinghua University in 2018. I obtained my PhD in Engineering at the University of Warwick in 2021, funded by the H2020 [ConFlex](https://www.conflex.org) project.

Research
======
My research interests are in physics-informed machine learning, AI for fluid dynamics, ML-based modeling, prediction, and control of complex fluid flows, and their applications on renewable energy systems e.g. wind energy and ocean energy.
## Wind farm digital twin
(a) The data and knowledge fusion framework for building the digital twin for wind farm wakes
![](images/WFDT.jpg)

(b) Case studies: a greedy case, a wake-steering case, and a partially-operating case
<img src="https://zhangxcii.github.io/images/greedy.mp4" width="250"> 
<img src="https://zhangxcii.github.io/images/yaw.mp4" width="250">
<img src="https://zhangxcii.github.io/images/partial.mp4" width="250">

## Wind field reconstruction via PINNs
(a) Wind LIDAR + NS equations: reconstructing atmospheric boundary layer flows
<img src="https://zhangxcii.github.io/images/ABLInflow2D.jpeg" width="600"> 

(b) 2D wind field prediction for the flow in front of a wind turbine. 
<img src="https://zhangxcii.github.io/images/ABLInflow2D.mp4" width="500"> 

(c) 3D wind field prediction for the flow in front of a wind turbine. 
![](images/sliceview.mp4)

![](images/rotor.mp4)

## Wake modelling via ML + CFD
(a) The overall surrogate modelling framework   
![](images/CFDML.png)

(b) Static wake models   
- [Deep convolutional GAN](https://zhangxcii.github.io/files/PaperJ10.pdf)    
Case studies: a greedy case  
![](images/gangreedy.jpeg)
Case studies: a wake-steering case   
![](images/ganyaw.jpeg)   
- [Super-fidelity net: handling multi-fidelity datasets](https://zhangxcii.github.io/files/PaperJ12.pdf)     
![](images/SFnet.jpeg)
   
(c) Dynamic wake models   
- [Bilateral CNN](https://zhangxcii.github.io/files/PaperJ13.pdf)    
![](images/single1.mp4)
![](images/single2.mp4)

- [POD-LSTM](https://zhangxcii.github.io/files/PaperJ4.pdf)    
![](images/PODLSTM.mp4)

## Phase-resolved sea wave prediction and predictable zone determination    
(a) Probabilistic phase-resolved wave prediction formulation    
![](images/wavepred.png)

(b) Wave prediction and predictable zone determination        
![](images/results_wave.jpeg)   
   
(c) Wave forecasting and forecastable horizon determination    
![](images/waveforecast.jpeg)


## Wave energy converter modelling via deep operator learning    
(a) The employed DeepONet network structure   
![](images/deeponet.jpeg)

(b) The evaluation of the data-driven model via spectral response amplitude operator    
![](images/RAO.jpeg)

## Intelligent control via reinforcement learning    
(a) Structural control of floating wind turbines   
![](images/RLturbine.png)   
(b) Wake-steering yaw control of wind farms    
![](images/RLfarm.jpeg)

## Uncertainty quantification       
(a) Quantification of parameter uncertainty in analytical wind turbine wake model   
![](images/florisuq.jpeg)    

(b) Quantification of parameter uncertainty in turbulence/transition models  
<img src="https://zhangxcii.github.io/images/sstuq.png" width="350"> 
<img src="https://zhangxcii.github.io/images/transuq.png" width="350"> 

