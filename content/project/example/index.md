---
title: TacFR-Gripper
summary: "TacFR-Gripper is a prototype of a reconfigurable Fin ray-based soft and compliant robotic gripper equipped with tactile skin, which is designed for dexterous in-hand manipulation tasks."
tags:
  - In-Hand Manipulation
  - Soft Robotic Hand
  - Reconfigurable Gripper



date: '2024-3-1T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://sites.google.com/view/tacfr-gripper/homepage'

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
# slides: ""
---

This soft, compliant gripper can adaptively grasp objects of diverse shapes and stiffness levels. An array of Force Sensitive Resistor (FSR) sensors is embedded within the robotic finger to serve as the tactile skins, which enables the robot with the capacity to perceive contact information during manipulation. Moreover, we implement a Graphical Neural Network (GNN)-based tactile perception approach to enable reliable grasping without accident slip or excessive force, which has been proven to outperform traditional threshold-based approach.  We provide theoretical analysis for gripper design, including kinematic analysis, workspace analysis, and a finite element analysis centered on the relationship between the gripper's load and its deformation. Three physical experiments were undertaken to quantify the performance of the TacFR-Gripper. These experiments aimed to: i) assess the grasp success rate across various everyday objects through different configurations, ii) verify the effectiveness of tactile skin with the GNN algorithm in grasping. iii) evaluate the gripper's in-hand manipulation capabilities for object pose control.  The experimental results indicated that the TacFR-Gripper can grasp a wide range of complex-shaped objects with a high success rate, deliver dexterous in-hand manipulation, and the integrated tactile skin enhances grasp stability by incorporating tactile feedback during manipulations.
