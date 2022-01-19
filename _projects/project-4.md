---
title: "Gennav"
collection: projects
type: "The Electronics and Robotics Club"
permalink: /projects/project-4
venue: "June"
date: 2020-02-02
location: "City, Country"
---

Gennav aims to create a general purpose python library that can be used for path planning in various robotics settings. It will have a collection of path planning algorithms, motion controllers along with various utilities to handle different methods of path optimisation, environment representation and eventually a geometry module to handle the underlying computations. 

Currently focused on the 2D path planning aspect of navigation. Rather than writing a big new python file for each new path planning algorithm, we could build on already defined utilities and primitives. This would be a big help to anyone working on any robot with autonomous navigation capabilities in the future. All they would need to do is implement the robot specific code and use gennav for the planning, control and optimization heavy lifting.

**Role:** Control and Planning

![Gennav](/images/gennav.png)<br>

[Github repo](https://github.com/ERC-BPGC/gennav)