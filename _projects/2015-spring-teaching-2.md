---
title: "Optimal Control Problems in Robotics"
collection: projects
type: "Advisor: Dr. Amit Setia"
permalink: /projects/project-2
venue: "August"
date: 2021-08-08
location: "City, Country"
---

The aim of this project was to explore the application of various Optimal COntrol techniques for tasks such as trajectory planning and obstacle avoidance in robotics. We first did literature reading of pseudospectral transcription method for solving optimal control problems. We started with testing our method with simple optimization problems like Bryson-Denham and Toy Problem. 

We later used B-splines for trajectory generation along with collocation method for solving a optimal control problem of obstacle avoidance for differential drive robot. To test the peformance of the method, We conducted simulations using MATLAB and ROS. The method was able to peform very well in absence of disturbance. To make this method more robust and provid disturbance rejection capabilties we decided to add a layer of reference trajectory tracking MPC on top of the optimal control. 

## Results

![Obstacle avoidance](/images/untitled.jpg)
