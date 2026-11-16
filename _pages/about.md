---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
publication_categories:
  - Human Behavior and Robot Interaction
  - Planning and Control
  - Robot Systems and Evaluation
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in [Robotics](https://robotics.umich.edu/) at the [University of Michigan](https://robotics.umich.edu/), advised by [Prof. Christoforos Mavrogiannis](https://chrismavrogiannis.com/) in the [Fluent Robotics Lab](https://fluentrobotics.com/). I study **motion planning and decision-making** for robots operating around people, with a focus on how robot motion communicates intent and how human behavior affects navigation.

I develop and deploy **embodied AI systems** for robots operating alongside people, connecting perception, planning, and control with real-world studies of human–robot interaction.

**I am seeking a Summer 2027 research internship in robot planning, robot learning, or human–robot interaction.**

[CV]({{ site.baseurl }}/files/Pranav_Goyal_CV_Research_2027.pdf?v=20261116) · [Google Scholar](https://scholar.google.com/citations?user=4lQd0TsAAAAJ) · [GitHub](https://github.com/pranavgo) · [Email](mailto:prgoyal@umich.edu)

My current research focuses on learning from **multimodal cues** to understand human behavior and the surrounding environment. I study how this contextual understanding can guide robots toward more informed and adaptive decision-making around people.

Previously I worked with [Prof. Harold Soh](https://haroldsoh.com/) at NUS's [CLeAR Lab](https://clear-nus.github.io/) on diffusion-based planning, and with [Prof. Howie Choset](https://www.ri.cmu.edu/ri-faculty/howie-choset/) and [Prof. Robin Murphy](https://engineering.tamu.edu/cse/profiles/rmurphy.html) at CMU's [Biorobotics Lab](https://biorobotics.ri.cmu.edu/index.php) during my undergrad at [BITS Pilani Goa](https://www.bits-pilani.ac.in/goa/).

## Selected Publications

{% for category in page.publication_categories %}
{% assign category_publications = site.publications | where: "homepage_category", category | sort: "date" | reverse %}

<section class="publication-group" aria-labelledby="{{ category | slugify }}">
  <h3 class="publication-group__heading" id="{{ category | slugify }}">
    {{ category }}
  </h3>
{% for post in category_publications %}{% include archive-single-publication.html compact="yes" heading_level=4 %}{% endfor %}
</section>

{% endfor %}

See my [full publication list](/publications/) and [research experience](/experience/) for all projects, papers, and roles.

## News

* **THRI 2026.** Our paper, [Intent Representation and Human Distraction Modulate the Effects of Legible Robot Motion in Hallway Navigation](/publication/2026-10-30-Rethinking-Legibility-in-Social-Robot-Hallway-Navigation), has been accepted to *ACM Transactions on Human-Robot Interaction*.
* **ICRA 2026.** [Bi<sup>3</sup>, A Biplatform, Bicultural, Biperson Dataset for Social Robot Navigation](/publication/2026-05-01-Bi3-A-Biplatform-Bicultural-Biperson-Dataset).
* **HRI 2026.** [How Human Motion Prediction Quality Shapes Social Robot Navigation Performance](/publication/2026-03-17-How-Human-Motion-Prediction-Quality-Shapes-Social-Robot-Navigation-Performance).
