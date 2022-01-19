---
title: "Applications of Model Predictive Control in Robotic Systems"
collection: projects
type: "Advisor: Dr. Rakesh Warier"
permalink: /projects/project-1
venue: "August"
date: 2021
location: "City, Country"
---

The project aimed at understanding the implementation of Model Predictive Control on robotic systems like 2D manipulator and comparing its peformance with other controllers. Since 2D robot arm is non linear system, we used the technique of feedback linearization to avoid high computation and complexity due to non-linear MPC. 

To test our approach we created a Simulink model of the entire system along with the controller and conducted simulations with various parameters and noises by moving the arm from an initial position to a goal position. We also created a Simscape multibody model to visualize the robot arm in 3D. We also created a MATLAB script to simulate the robot arm along with the PID controller and compare its performance with MPC.

To improve our understanding of MPC we also wrote our own script for refernce trajectory tracking using MPC. We are now trying to integrate this script with our simulations. Our aim is to further integrate learning based techniques with this method to reduce the dependecy on availablity of accurate dynamic model. 

## Results
### MPC using feedback linearization
![Simulation in simscape multibody](/images/ARM_MPC.gif)<br>

### PID 
![PID controller for 2D robot arm](/images/PID.gif)<br>


