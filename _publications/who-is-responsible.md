---
title: "Who Is Responsible? Self-Adaptation Under Multiple Concurrent Failures with Unknown Faults in Complex Robotic Systems"
collection: publications
category: conferences
permalink: /publication/wir
excerpt: 'In this work we present an approach that autonomously identifies and mitigates multiple concurrent failures in complex robotic systems, even when the faults are unknown.'
date: 2026-11-11
venue: '2026 IEEE International Conference on Autonomic Computing and Self-Organizing Systems (ACSOS)'
bibtexurl: 'http://awied1404.github.io/files/wir.bib'
paperurl: 'http://awied1404.github.io/files/wir.pdf'
citation: 'A. Wiedholz, R. Paintner, A. Hoffmann and T. Huber, "Who Is Responsible? Self-Adaptation Under Multiple Concurrent Failures with Unknown Faults in Complex Robotic Systems," 2026 IEEE International Conference on Autonomic Computing and Self-Organizing Systems (ACSOS), Cesena, Italy, 2026, pp. 230-241, doi: 10.1109/ACSOS69738.2026.00037.'
---
Robotic systems increasingly operate in dynamic, unpredictable environments, where tightly coupled sensors and software modules increase the probability of a single failure cascading across components. Therefore, multiple strategies can be plausible to resolve the underlying fault. Most existing self-adaptive approaches that have been applied to robotics assume predefined one-to-one failure-to-adaptation mappings. We present a ROS2-based self-adaptation approach building upon MAPE-K that addresses (1) multiple simultaneous failures with differing criticality, (2) cascading failures across components, and (3) multiple plausible resolving strategies per detected failure. Central to our approach is an adaptation rule set which lets designers specify failure patterns, assign criticality levels, and enumerate multiple plausible adaptation strategies. This rule set, combined with an automatically extracted live dependency graph, enables lightweight root-cause analysis and strategy ranking to prioritize minimal and effective adaptations. Our approach implements a lightweight self-optimizing component which learns estimated success probabilities of different strategies for each known failure. Experiments on an underwater robot scenario and a perception use case show that our approach can identify root causes among concurrent failures, favors inexpensive adaptations, reduces unnecessary adaptations, and achieves performance comparable to existing baselines designed for sequential failures. The code is publicly available.
