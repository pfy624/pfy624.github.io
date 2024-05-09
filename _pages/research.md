---
# layout: archive # too wide
title: "Feiyang Pan's Research Page"
permalink: /research/
author_profile: true
---

# Research Interets 

1. Signal/Image Processing and Artificial Intelligence 
   - Densoising method
   - Object Detection

2. Prognostics and health management (fault diagnosis, anomaly detection) : 
   - Intelligent Sensor Method
   - Ultrasound Method
   - Simulation and modeling

---


# Research Experiences 

## 1. Numerical Simulation of Plasma Equilibrium Evolution in Nuclear Fusion 

*Undergraduate Research Program at USTC* 

Supervisor: [Prof. Mengping ZHANG](https://dsxt.ustc.edu.cn/zj_ywjs.asp?zzid=860 "Prof. Mengping ZHANG's homepage"){:target="_blank"} 

07/2021 ~ 05/2022, USTC 

Defense: 12/30/2022 

The controlled nuclear fusion is one of the most prospective solution to the energy crisis and environmental problems. The tokamak has been widely investigated as the most feasible magnetically confined fusion device. Tearing mode instabilities have great influence on the fusion reaction thus worth stuying. 

In this research, in order to simulate the evolution process of tokamak plasma instability numerically, we reviewed different formulations of the MHD equations, selected a suitable type of nonconservative resistive MHD, and developed a parallel solver using hybrid finite difference-Fourier pseudo spectral method in cylindrical coordinates. Using our solver, we simulated the (m,n)=(2,1) resistive tearing mode instability, and checked the results against those obtained from the CLT and M3D-C1 code with researchers from Institute of Plasma Physics, Chinese Academy of Science. Our solver exhibits satisfactory performance in conserving numerical divergence of the magnetic field, fitting the theoretical relation between logrithmic growth rate of kinetic energy and resistivity, revealing the tearing mode structure independent of initial peturbation at the linear stage, and reaching the final saturation stage. 

Below is a plot of the perturbation on the toroidal component of the electric field at time T=7000, which reveals the resistive tearing mode structure and should be independent of the initial perturbation, and a log-plot of kinetic energy evolution under different resistivity. Our code reveals the linear growing stage, mode structure and the logrithmic growth rate very well. 

<center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../files/undergraduate-research-program/cpt_13.png" 
        width = "46.5%">
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../files/undergraduate-research-program/energy.png" 
        width = "50%">
    <br>
    <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        left: tearing mode sturtcure; right: kinetic energy
    </div>
    <p> </p>
</center>


---
