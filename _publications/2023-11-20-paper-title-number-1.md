---
title: "A Satcom On-the-Move Phased-Array Antenna Tracking Algorithm on Robot Operating System"
collection: publications
category: conferences
permalink: /publication2023-11-20-paper-title-number-1
excerpt: 'This paper discusses the development of an on-the-move satellite communication algorithm for maintaining connectivity between LEO satellites and moving vehicles on the ground.'
date: 2023-11-20
venue: 'IEEE International Conference on Control, Automation and Systems (ICCAS)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/10316776'
citation: '**S. Huang**, P. Chang, X. Lu, and J. Juang. (2023). &quot;A Satcom On-the-Move Phased-Array Antenna Tracking Algorithm on Robot Operating System.&quot; <i>IEEE International Conference on Control, Automation and Systems (ICCAS)</i>.'
---

In recent years, communication through low Earth orbiting (LEO) satellites has been advocated as an important scheme in realizing seamless and resilient networking. The paper discusses the development and implementation of a satellite communication on-the-move (SOTM) algorithm for the connectivity between LEO satellites and moving vehicles on ground. The algorithm encompasses the prediction of satellite position/velocity, the determination of the motion of the vehicle, the compensation of the anetenna array characteristics, and the tracking of the LEO satellite signal. To this end, the satellite position is predicted using the Simplified General Perturbations model 4 (SGP4) by extracting two-line elements; the attitude of the vehicle is determinated by processing inertial measurement sensor data; the pointing errors stemming from orbit and vehicle dynamics are compensated via the feedback from time-varying antenna look angles. At the system level, the robot operating system (ROS) architecture is developed to implement the proposed algorithm. The virtue of this design is that the components of SOTM are selective under different types of vehicles and circumstances. Furthermore, the simulations for the algorithm provide an evaluation of performance under measurement noises from both magnetic, angular rate, and gravity (MARG) module and global navigation satellite system (GNSS) module. Finally, the experiments, along with beamforming via a two-dimensional phased-array antenna, are presented to demonstrate the effectiveness of the proposed design.
