---
title: "SUNSET - A Sensor-fUsioN based semantic SegmEnTation exemplar for ROS-based self-adaptation"
collection: publications
category: conferences
permalink: /publication/sunset
excerpt: 'In this work we present an exemplar that enables rigorous, repeatable evaluation of architecture-based self-adaptation in dynamic environments. It implements a sensor fusion semantic-segmentation pipeline driven by a trained Machine Learning (ML) model whose input preprocessing can be perturbed to induce realistic performance degradations.'
date: 2026-09-11
venue: '8th International Workshop on Robotics Software Engineering co-located with the 2026 ICRA'
bibtexurl: 'http://awied1404.github.io/files/sunset.bib'
paperurl: 'http://awied1404.github.io/files/sunset.pdf'
citation: 'Andreas Wiedholz, Rafael Paintner, Alwin Hoffmann, Carlos Hernandez, Tobias Huber: SUNSET- A Sensor-fUsioN based semantic SegmEnTation exemplar for ROS-based self-adaptation. RoSE@ICRA 2026'
---
The fact that robots are getting deployed more often in dynamic environments, together with the increasing complexity of their software systems, raises the need for self-adaptive approaches. In these environments robotic software systems increasingly encounter (1) failures whose symptoms are easy to observe but root causes might be ambiguous or (2) multiple failures appearing concurrently. We present SUNSET, a ROS2-based exemplar that enables rigorous, repeatable evaluation of architecture-based self-adaptation in such conditions. It implements a sensor fusion semantic-segmentation pipeline driven by a trained Machine Learning (ML) model whose input preprocessing can be perturbed to induce realistic performance degradations. The exemplar exposes five observable failures, each of which can be caused by different faults and supports concurrent failures spanning self-healing and self-optimisation. SUNSET includes the segmentation pipeline, a trained ML model, fault-injection scripts, a baseline controller for further comparisons, and step-by-step integration and evaluation documentation to facilitate reproducible studies. The code is available at https://github.com/XITASO/sunset.
