---
layout: default
title: Magnetic Medical Robotics Lab
description: PI Dr.Heng Wang
navigation_weight: 3

---
# Research


The research of our Lab is focused on the following areas: 

* Novel magnetic sensing and actuation principles, including new magnetic materials, structures and functions. 
* Intelligent estimation, control, planning, and learning algorithms for magnetically navigated medical robots.
* Multi-functional magnetic navigation systems for pose tracking, shape sensing, locomotion, and manipulation of multi-scale miniature medical robots (e.g., capsule robots, continuum robots, micro-nano robots, etc.)
* Simulation and virtual training platforms to facilitate research, development and application of magnetic robots in minimally invasive medicine.



![research overview](HomeSourceDocument/research overview.png) 


# **Magnetic Capsule Robot**

## 3-DoF Orientation Manipulation of Capsule Robots with a Triaxial Anisotropic Soft Magnet

[1] **H. Wang***, J. Cui, K. Tian, Y. Han, "Three-degrees-of-freedom orientation manipulation of small untethered robots with a single anisotropic soft magnet", Nature Communications, vol 14,  no. 1, 7491, Nov. 2023. (**Editor's Highlight Paper in Applied Mathematics and Physics**)

![soft magnet actuation](ResearchSourceDocument/soft-magnet_actuation.png)

![ResearchSourceDocument/orientation.mp4](https://drive.google.com/file/d/1XYbE5HQFSBEPvOA_hWmD3O38J46MsDnU/view?usp=drive_link)


> Conventional permanent magnet based magnetic actuation can only achieve 2-DoF orientation control and 5-DoF manipulation of small untethered robots. In this work, a triaxial ellipsoidal soft magnet is used as the actuation element for capsule robots instead of a permanent magnet to achieve full 3-DoF orientation manipulation.


# **New Magnetic Tracking Method: Soft-Magnet-based Pose Tracking System**

![principle](ResearchSourceDocument/soft-magnet tracking_principle.png) 

> Conventional magnetic tracking systems can be categorized as electromagnet-based systems (EM) and permanent-magnet-based systems (PM). EM tracking systems use a magnetic sensor on the target to measure the magnetic field of stationary electromagnet sources for pose estimation. However, EM systems need electric wiring to the moving sensor, which is delicate and easily broken. The wiring issue also prevents the EM systems from tracking untethered robots. PM tracking systems use an array of magnetic sensors to track a permanent magnet on the target. However, PM systems can only achieve 5-DoF pose tracking and suffer from ambient ferromagnetic disturbances.

> To address the above challenges in existing magnetic tracking systems, our lab proposes and develops a new magnetic tracking system based on the soft magnet with high magnetic permeability and low coercivity. A piece of soft magnet is attached to the target while an excitation electromagnet and magnetic sensors are stationary. The soft magnet experiences a position-dependent magnetization by the alternating magnetic field from the electromagnet, and then it generates a secondary magnetic field, which is measured for pose estimation. **The soft-magnet-based tracking system is wireless, non-contacting, and robust to magnetic disturbances.** This new soft-magnet-based tracking method has been uitilized for 1-DoF linear/angular position measurement, 3-DoF position tracking, and 6-DoF pose tracking of various medical robots and devices.

## Soft-Magnet-based Tracking: 1-DoF Linear/Angular Position Measurement System

[2] **H. Wang** and R. Rajamani*, “A Remote Position Sensing Method Based on Passive High Magnetic Permeability Thin Films”, Sensors and Actuators A: Physical, vol. 295, pp. 217-223, 2019.

[3] **H. Wang**, R. Madson and R. Rajamani*, “Electromagnetic Position Measurement System Immune to Ferromagnetic Disturbances”, IEEE Sensors Journal, vol. 19, no. 21, pp. 9662-9671, July 2019.

[4] **Heng Wang***#, Shuangyi Wang#, Rajesh Rajamani, “Electromagnetic Angular Position Sensing Using High-Magnetic-Permeability Materials”, IEEE Sensors Journal, vol. 22, no. 12, pp. 11626-11636, 2022.

![1-DoF position sensing](ResearchSourceDocument/soft-magnet tracking_1D.png) 

> The soft-magnet-based position sensing principle is utilized to develop linear position measurement systems for linear industrial actuators and angular position measurement systems for rotational mechanical joints.

## Soft-Magnet-based Tracking: 3-DoF Position Tracking of Flexible Robots
[5] **H. Wang**#, S. Wang#, H. Liu, K. Rhode, Z. G. Hou, R. Rajamani*, “3-D Electromagnetic Position Estimation System Using High-Magnetic-Permeability Metal for Transluminal Continuum Medical Robots”,  IEEE Robotics and Automation Letters (also reported on ICRA 2022), vol. 7, no. 2, pp. 2581 – 2588, Jan. 2022.

![3-DoF position tracking](ResearchSourceDocument/soft-magnet tracking_3D.png) 

>  The soft-magnet-based position sensing principle is utilized to develop a 3-DoF position tracking system for a flexible medical robot. The highly nonlinear magnetic response to soft-magnet motion is modeled. Experimental results show that the position tracking error is below 5 mm.


## Soft-Magnet-based Tracking: 6-DoF Pose Tracking System
[6] S. Liu, **H. Wang***, A wireless 6-DoF pose tracking system using a triaxially anisotropic soft magnet, IEEE/ASME Transactions on Mechatronics, 2024.

![6-DoF pose tracking](ResearchSourceDocument/soft-magnet tracking_6D.png) 

<iframe width="820" height="462" src="https://www.youtube.com/embed/vYDYIHm5EN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> The soft-magnet-based position sensing principle is extended for 6-DoF pose tracking. A triaxially anisotropic soft magnet is used as the sensitive target instead of a spherical soft magnet. The geometry-dependent anisotropic magnetization of the soft magnet enables 3-DoF orientation sensing. The developed soft-magnet tracking system can achieve full 6-DoF pose tracking with a passive magnet, which is not feasible in existing permanent-magnet tracking systems.


# **Active Electromagnetic Tracking Systems**

We develope active electromagnetic tracking technologies to improve tracking accuracy, to enlarge workspace, and to save energy of electromagnetic tracking systems.

## Active Tracking: Electromagnet Current Control
[7] **H. Wang**, A. Zemouche and R. Rajamani*, “Nonlinear Observer for Electromagnetic Position Estimation Using Active Current Control”, Mechanical Systems and Signal Processing, vol. 167, 108449, 2022.

[8] **Heng Wang** and Rajesh Rajamani*, “Electromagnetic Position Estimation Using Active Current Control and Nonlinear Observer”, in 2020 American Control Conference (ACC), Denver, USA, 2020. (ASME DSCD Mechatronics TC Best Paper Award)

![active current tracking](ResearchSourceDocument/active_current.png) 

> The current supply to the electromagnet source is actively controlled during pose tracking. The current is increased when the sensor (target) moves away from the electromagnet to remedy the magnetic sensitivity. An optimal current profile is designed and the current is controlled according to the profile based on the position estimate of the target. A nonlinear observer is designed to guarantee stability of both current control and position estimation.


## Active Tracking: Electromagnet Orientation Control
[9] Y. Shen, S. Dong, D. Liu, K. Zhang, **H. Wang***, "Active 6-DoF Electromagnetic Pose Tracking Using Orientation Control of the Magnetic Source", IEEE International Conference on Robotics and Biomimetics (ROBIO), 2023.

![active orientation tracking](ResearchSourceDocument/active_orientation.png) 

> The orientation of the electromagnet source is actively controlled to always point to the sensor (target) to maintain the optimal tracking accuracy.


# **Magnetic-Inertial Tracking System**

We fuse magnetic sensing and inertial sensing to achieve accurate and robust 6-DoF pose tracking for various medical applications, e.g., medical robot localization and virtual medical training.

## Development of Magnetic-Inertial Tracking System

[10] S. Dong, **H. Wang***, A compact and robust 6-DoF pose tracking system using magnetic-inertial sensors and a single uniaxial electromagnetic coil, IEEE Sensors Journal, Dec. 2023.

![magnetic-inertial tracking](ResearchSourceDocument/magnetic_inertial.png) 

> In magnetic-inertial tracking systems, only one electromagnetic coil is used, which makes the system compact. Fused with an inertial sensor, the tracking system become more robust.

## Virtual Ultrasound Training System based on Magnetic-Inertial Probe Tracking

[11] **H. Wang**#, S. Dong#, Q. Yang, J. Han, Z. He, Y. He*, S. Wang*, "A virtual ultrasonography simulator for skill training using magnetic-inertial probe tracking," IEEE/ASME Transactions on Mechatronics, June 2023.

![virtual ultrasound](ResearchSourceDocument/virtual_ultrasound.png) 

> A compact, inexpensive, and interactive ultrasonography simulator is developed using magnetic-inertial probe tracking and virtual ultrasound image generation. Embedded with magnetic and inertial sensors, the sham ultrasound probe is tracked by fusing magnetic measurement of a single electromagnet embedded in the phantom and inertial measurement of the probe. Then the virtual scan plane is determined according to the estimated probe pose to slice the digital anatomical model
for virtual image generation, providing visual feedback for skill training. Due to intuitive freehand interaction, accurate probe tracking, and real-time visual guidance of ultrasound images and three-dimensional (3-D) virtual scene of the probe and anatomy, the proposed simulator can provide immersive training experience for quick ultrasound skill acquirement.



# **Simulation Platform for Magnetic Robots**

![simulation platform](ResearchSourceDocument/simulation.png) 




(# indicates equal contribution)



[back](./)

