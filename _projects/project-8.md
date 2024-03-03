---
title: "NSF Surfside"
collection: projects
type: "Biorobotics Lab"
permalink: /projects/project-8
venue: "June"
date: 2022-06-06
location: "City, Country"
---
The NSF Surfside project aimed at using the data from Champlain Towers South Condominium collapse at Surfside,
Florida on June 2021 for developing method to reconstruct 3d point clouds of the disaster site and developing a method for void detection in these regions which have high changes of concealing a survivor. The project was supported by NSF USA and was lead by Prof Robin Murphy and Prof Howie Choset.

 The data invloved top-down RGB drone shots from the collapse site over four days. I worked on the 3D reconstruction and registration of a Miami surfside collapse using SFM techniques. The major challenges with this task were the lack of ground truth data and the presence of dynamic objects in regions of interest. I worked on tackling both of these challenges and came up with a unique Hierarchical Localization + COLMAP SFM-based pipeline to first estimate the camera positions in the same coordinate space and then register the reconstructed point cloud from different days. This eventually helped in developing a semi-autonomous void detection pipeline. The work from this project was published in SSRR 2022 and IROS 2023.


[![NSF Miami Surfside](\images\surfside.png)]
