---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in [Robotics](https://robotics.umich.edu/) at the [University of Michigan](https://robotics.umich.edu/), working in the [Fluent Robotics Lab](https://fluentrobotics.com/) with [Prof. Christoforos Mavrogiannis](https://chrismavrogiannis.com/). I work on **motion planning, control, and human-robot interaction**, mostly social navigation, getting robots to move among people as easily as people move around each other. Previously I worked with [Prof. Harold Soh](https://haroldsoh.com/) at NUS's [CLeAR Lab](https://clear-nus.github.io/) on diffusion-based planning, and with [Prof. Howie Choset](https://www.ri.cmu.edu/ri-faculty/howie-choset/) and [Prof. Robin Murphy](https://engineering.tamu.edu/cse/profiles/rmurphy.html) at CMU's [Biorobotics Lab](https://biorobotics.ri.cmu.edu/index.php) during my undergrad at [BITS Pilani Goa](https://www.bits-pilani.ac.in/goa/).

My research focuses on navigation under **actionable uncertainty** in human environments, such as whether a person has noticed the robot or what lies around a blind corner. I develop methods that model this uncertainty and plan motion to reduce it, using the robot's movement both to gather information and to make its intent clear to the people around it. In [Rethinking Legibility](/publication/2026-03-16-Rethinking-Legibility-in-Social-Robot-Navigation), we found that signaling an immediate choice, like which side to pass on, beats signaling a final goal, and holds up even when people are distracted. A related thread is human motion prediction and the data behind it, including [how prediction quality shapes navigation](/publication/2026-03-17-How-Human-Motion-Prediction-Quality-Shapes-Social-Robot-Navigation-Performance) and the datasets ([ACME](/publication/2026-02-10-ACME-Multi-Cultural-Multi-Embodiment-Social-Navigation-Dataset), [Bi<sup>3</sup>](/publication/2026-05-01-Bi3-A-Biplatform-Bicultural-Biperson-Dataset)) and testing tools ([SocRATES](/publication/2026-01-20-SocRATES-Towards-Automated-Scenario-based-Testing-RA-L)) these models need. You can reach me at prgoyal@umich.edu.

## News
* **HRI 2026 (LBR).** Rethinking Legibility in Social Robot Navigation
* **HRI 2026.** How Human Motion Prediction Quality Shapes Social Robot Navigation Performance
* **IEEE RA-L.** SocRATES, Automated Scenario-based Testing of Social Navigation Algorithms
* **ICRA 2026.** Bi<sup>3</sup>, A Biplatform, Bicultural, Biperson Dataset for Social Robot Navigation
* **RSS 2024 workshop.** Runner-up Best Paper Award for our scenario-testing paper

## Selected Publications

{% for post in site.publications reversed %}{% if post.header.teaser %}{% include archive-single-publication.html compact="yes" %}{% endif %}{% endfor %}

Full list on my [Publications](/publications/) page and [Google Scholar](https://scholar.google.com/citations?user=4lQd0TsAAAAJ).
