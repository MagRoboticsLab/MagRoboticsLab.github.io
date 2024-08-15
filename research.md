---
layout: default
title: Magnetic Medical Robotics Lab
description: PI Dr. Heng Wang
navigation_weight: 3

---
# Research


The research of our Lab is focused on the following areas: 

* Novel magnetic sensing and actuation principles, including new magnetic materials, structures and functions. 
* Intelligent estimation, control, planning, and learning algorithms for magnetically navigated medical robots.
* Multi-functional magnetic navigation systems for pose tracking, shape sensing, locomotion, and manipulation of multi-scale miniature medical robots (e.g., capsule robots, continuum robots, micro-nano robots, etc.)
* Simulation and virtual training platforms to facilitate research, development and application of magnetic robots in minimally invasive medicine.



<img src="magnetic_systems.png" alt="magnetic system" width="800"/> 
* A magnetic robotic system is consisted of 1) an intelligent magnetic actuation system, such as an electromagnet actuation system or mobile permanent-magnet system, 2) magnetic miniature robots (rigid or soft, single or swarm, tethered or untethered), and 3) a sensing system such as cameras or medical imaging machines.



---------
*********

# **New Magnetic Tracking Method: Soft-Magnet-based Pose Tracking System**

<img src="medical_robot.png" alt="medical robot" width="800"/> 
> Conventional magnetic tracking systems can be categorized as electromagnet-based systems (EM) and permanent-magnet-based systems (PM). EM tracking systems use a magnetic sensor on the target to measure the magnetic field of stationary electromagnet sources for pose estimation. However, EM systems need electric wiring to the moving sensor, which is delicate and easily broken. The wiring issue also prevents the EM systems from tracking untethered robots. PM tracking systems use an array of magnetic sensors to track a permanent magnet on the target. However, PM systems can only achieve 5-DoF pose tracking and suffer from ambient ferromagnetic disturbances.
> To address the above challenges in existing magnetic tracking systems, our lab proposes and develops a new magnetic tracking system based on the soft magnet with high magnetic permeability and low coercivity. A piece of soft magnet is attached to the target while an excitation electromagnet and magnetic sensors are stationary. The soft magnet experiences a position-dependent magnetization by the alternating magnetic field from the electromagnet, and then it generates a secondary magnetic field, which is measured for pose estimation. This new soft-magnet-based tracking method has been uitilized for 1-DoF linear/angular position measurement, 3-DoF position tracking, and 6-DoF pose tracking of various medical robots and devices.

## Soft-Magnet-based Tracking: 1-DoF Linear/Angular Position Measurement System
[1] Fan, X.#, **Dong, X.#**, Karacakol, A.C., Xie, H. and Sitti, M., 2020. Reconfigurable multifunctional ferrofluid droplet robots. Proceedings of the National Academy of Sciences, 117(45), pp.27916-27926. [Link](https://www.pnas.org/content/117/45/27916.short)

![1-DoF position sensing](soft-magnet tracking_1D.png) 
> The soft-magnet-based position sensing principle is utilized to develop linear position measurement systems for linear industrial actuators and angular position measurement systems for rotational mechanical joints.

<iframe width="820" height="462" src="https://www.youtube.com/embed/vYDYIHm5EN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Magnetically actuated endoscopes
[2] Son, D., **Dong, X.** and Sitti, M., 2018. A simultaneous calibration method for magnetic robot localization and actuation systems. IEEE Transactions on Robotics, 35(2), pp.343-352. [link](https://ieeexplore.ieee.org/abstract/document/8594561)

[3] [European patent](https://data.epo.org/publication-server/document?iDocId=6267866&iFormat=2)

[4] [US patent](https://patentimages.storage.googleapis.com/22/4d/c0/fbea0611f36694/US20200196844A1.pdf)

<img src="sensing_actuation.png" alt="capsule robot" width="800"/> 

> This paper proposes a method of simultaneously calibrating magnetic localization and actuation systems for magnetically actuated robots. In this method, uncalibrated magnetic localization and actuation systems are calibrated simultaneously with minimal human intervention, which enables self-calibration, flexible reconfiguration, and long-term correctness of the system parameters. This method employs a bundle adjustment framework using a quadratic measurement model for sensors and the magnetic dipole model for actuators. The proposed method has been verified in comparison with finite element simulations and existing calibration methods for magnetic actuators and sensor arrays. In the experiments, the determinant of coefficient (R2 value) was 99.84% for the sensor system and 99.45% for the actuator system after the calibration, comparable with individual state-of-art calibration methods of calibrating magnetic actuators and sensor arrays. This method has potential to improve the reconfigurability and long-term accuracy of magnetic robot localization and actuation systems, such as magnetically actuated capsule endoscopes.


## Soft climbing medical robots (coming soon)

## Liquid biopsy medical robots (coming soon)

# **Microrobots for manipulation**


**Key words**: soft microgrippers, control and motion planning, 3D assseembly, tissue engineering
<img src="manipulation.png" alt="robotic manipulation" width="800"/> 


## 3D dexterous manipulation
[5] Chung, S.E.#, **Dong, X.#** and Sitti, M., 2015. Three-dimensional heterogeneous assembly of coded microgels using an untethered mobile microgripper. Lab on a Chip, 15(7), pp.1667-1676. [Link](https://pubs.rsc.org/en/content/articlepdf/2015/lc/c5lc00009b)

> Abstract: Three-dimensional (3D) heterogeneous assembly of coded microgels in enclosed aquatic environments is demonstrated using a remotely actuated and controlled magnetic microgripper by a customized electromagnetic coil system. The microgripper uses different ‘stick–slip’ and ‘rolling’ locomotion in 2D and also levitation in 3D by magnetic gradient-based pulling force. This enables the microrobot to precisely manipulate each microgel by controlling its position and orientation in all x–y–z directions. Our microrobotic assembly method broke the barrier of limitation on the number of assembled microgel layers, because it enabled precise 3D levitation of the microgripper. We used the gripper to assemble microgels that had been coded with different colours and shapes onto prefabricated polymeric microposts. This eliminates the need for extra secondary cross-linking to fix the final construct. We demonstrated assembly of microgels on a single micropost up to ten layers. By increasing the number and changing the distribution of the posts, complex heterogeneous microsystems were possible to construct in 3D.


<iframe width="820" height="496" src="https://www.youtube.com/embed/gAwHHdvs4Eo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Motion planning for automatic grasping
[6] **Dong, X.** and Sitti, M., 2017, May. Planning spin-walking locomotion for automatic grasping of microobjects by an untethered magnetic microgripper. In 2017 IEEE International Conference on Robotics and Automation (ICRA) (pp. 6612-6618). IEEE. [Link](https://ieeexplore.ieee.org/abstract/document/7989782)

<img src="planning.png" alt="gripper planning" width="600"/> 

> Most demonstrated mobile microrobot tasks so far have been achieved via pick-and-placing and dynamic trapping with teleoperation or simple path following algorithms. In our previous work, an untethered magnetic microgripper has been developed which has advanced functions, such as gripping objects. Both teleoperated manipulation in 2D and 3D have been demonstrated. However, it is challenging to control the magnetic microgripper to carry out manipulation tasks, because the grasping of objects so far in the literature relies heavily on teleoperation, which takes several minutes with even a skilled human expert. Here, we propose a new spin-walking locomotion and an automated 2D grasping motion planner for the microgripper, which enables time-efficient automatic grasping of microobjects that has not been achieved yet for untethered microrobots. In its locomotion, the microgripper repeatedly rotates about two principal axes to regulate its pose and move precisely on a surface. The motion planner could plan different motion primitives for grasping and compensate the uncertainties in the motion by learning the uncertainties and planning accordingly. We experimentally demonstrated that, using the proposed method, the microgripper could align to the target pose with error less than 0.1 body length and grip the objects within 40 seconds. Our method could significantly improve the time efficiency of micro-scale manipulation and have potential applications in microassembly and biomedical engineering.


---------
*********

# **Bioinspired soft robots**
* **Key words**: soft robots, bioinspiration, biomechanics, swimming robots, fluidic manipulation

<img src="bioinspired_soft_robot.png" alt="soft robots" width="800"/> 

## Artificial cilia
[7] **Dong, X.#**, Lum, G.Z.#, Hu, W.#, Zhang, R., Ren, Z., Onck, P.R. and Sitti, M., 2020. Bioinspired cilia arrays with programmable nonreciprocal motion and metachronal coordination. Science advances, 6(45), p.eabc9323. [Link](https://advances.sciencemag.org/content/6/45/eabc9323)

<img src="cilia.jpeg" alt="cilia robot" width="600"/> 


> Coordinated nonreciprocal dynamics in biological cilia is essential to many living systems, where the emergentmetachronal waves of cilia have been hypothesized to enhance net fluid flows at low Reynolds numbers (Re). Experimental investigation of this hypothesis is critical but remains challenging. Here, we report soft miniature devices with both ciliary nonreciprocal motion and metachronal coordination and use them to investigate the quantitative relationship between metachronal coordination and the induced fluid flow. We found that only antiplectic metachronal waves with specific wave vectors could enhance fluid flows compared with the synchronized case. These findings further enable various bioinspired cilia arrays with unique functionalities of pumping and mixing viscous synthetic and biological complex fluids at low Re. Our design method and developed soft miniature devices provide unprecedented opportunities for studying ciliary biomechanics and creating cilia-inspired wireless microfluidic pumping, object manipulation and lab- and organ-on-a-chip devices, mobile microrobots, and bioengineering systems.


<iframe width="846" height="502" src="https://www.youtube.com/embed/up3zPToiRd0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Design methodology of soft robots
[8] Lum, G.Z.#, Ye, Z.#, **Dong, X.#**, Marvi, H., Erin, O., Hu, W. and Sitti, M., 2016. Shape-programmable magnetic soft matter. Proceedings of the National Academy of Sciences, 113(41), pp.E6007-E6015. [Link](https://www.pnas.org/content/113/41/E6007) 

<img src="pnas_design.jpg" alt="Design" width="600"/>

> At small scales, shape-programmable magnetic materials have significant potential to achieve mechanical functionalities that are unattainable by traditional miniature machines. Unfortunately, these materials have only been programmed for a small number of specific applications, as previous work can only rely on human intuition to approximate the required magnetization profile and actuating magnetic fields for such materials. Here, we propose a universal programming methodology that can automatically generate the desired magnetization profile and actuating fields for soft materials to achieve new time-varying shapes. The proposed method can enable other researchers to fully capitalize the potential of shape-programming technologies, allowing them to create a wide range of novel soft active surfaces and devices that are critical in robotics, material science, and medicine.



## Bio-inspired swimming robots
[9] Ren, Z.#, Hu, W.#, **Dong, X.** and Sitti, M., 2019. Multi-functional soft-bodied jellyfish-like swimming. Nature communications, 10(1), pp.1-12. [Link](https://www.nature.com/articles/s41467-019-10549-7.pdf)

<img src="jellyfish.jpg" alt="swimming robot" width="600"/> 

> The functionalities of the untethered miniature swimming robots significantly decrease as the robot size becomes smaller, due to limitations of feasible miniaturized on-board components. Here we propose an untethered jellyfish-inspired soft millirobot that could realize multiple functionalities in moderate Reynolds number by producing diverse controlled fluidic flows around its body using its magnetic composite elastomer lappets, which are actuated by an external oscillating magnetic field. We particularly investigate the interaction between the robot’s soft body and incurred fluidic flows due to the robot’s body motion, and utilize such physical interaction to achieve different predation-inspired object manipulation tasks. The proposed lappet kinematics can inspire other existing jellyfish-like robots to achieve similar functionalities at the same length and time scale. Moreover, the robotic platform could be used to study the impacts of the morphology and kinematics changing in ephyra jellyfish.



---------
*********

# **Swarm microrobots**
* **Key words**: control, collective motion, cooperative behaviors


![Swarm](swarm_all.png) 

## Reconfigurable and cooperative swarms
[10] Dong, X. and Sitti, M., 2020. Controlling two-dimensional collective formation and cooperative behavior of magnetic microrobot swarms. The International Journal of Robotics Research, 39(5), pp.617-638. [Link](https://journals.sagepub.com/doi/full/10.1177/0278364920903107)

<iframe width="410" height="307" src="https://www.youtube.com/embed/TVcUt4bgYEE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="410" height="307" src="https://www.youtube.com/embed/1NgyePOxXTI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Programmable static formations
[11] Dong, X. and Sitti, M., 2019. Collective Formation and Cooperative Function of a Magnetic Microrobotic Swarm. In Robotics: Science and Systems. [Link](http://m.roboticsproceedings.org/rss15/p07.pdf)

![Swarm](swarm.jpeg) 
> Magnetically actuated mobile microrobots can access distant, enclosed, and small spaces, such as inside microfluidic channels and the human body, making them appealing for minimally invasive tasks. Despite their simplicity when scaling down, creating collective microrobots that can work closely and cooperatively, as well as reconfigure their formations for different tasks, would significantly enhance their capabilities such as manipulation of objects. However, a challenge of realizing such cooperative magnetic microrobots is to program and reconfigure their formations and collective motions with under-actuated control signals. This article presents a method of controlling 2D static and time-varying formations among collective self-repelling ferromagnetic microrobots (100 μm to 350 μm in diameter, up to 260 in number) by spatially and temporally programming an external magnetic potential energy distribution at the air–water interface or on solid surfaces. A general design method is introduced to program external magnetic potential energy using ferromagnets. A predictive model of the collective system is also presented to predict the formation and guide the design procedure. With the proposed method, versatile complex static formations are experimentally demonstrated and the programmability and scaling effects of formations are analyzed. We also demonstrate the collective mobility of these magnetic microrobots by controlling them to exhibit bio-inspired collective behaviors such as aggregation, directional motion with arbitrary swarm headings, and rotational swarming motion. Finally, the functions of the produced microrobotic swarm are demonstrated by controlling them to navigate through cluttered environments and complete reconfigurable cooperative manipulation tasks.




(# indicates equal contribution)



[back](./)

