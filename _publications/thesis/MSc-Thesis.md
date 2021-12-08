---
title: "Approximated Algorithmic Mechanism for Scheduling Chilean Operating Rooms with Multi-Agent Based Simulation"
collection: 'publications'
permalink: /publication/MSc_Thesis
excerpt: ''
date: 2021-12-02
venue: 'MSc. Thesis'
---
Operating rooms are one of the most important parts of hospitals and the main cost and revenue source. Scheduling patients, efficiently allocating resources in operating rooms, would greatly improve service quality. However, automatic scheduling of non-emergency patients is complicated
due to the lack of an objective indicator that points out who to attend. Implemented optimization solutions must be approved by a board of surgeons given low trust on the system, due to lack of decision making explainability. The changes they perform affect the optimality of results to an unknown extent and give space to misaligned incentives. Mechanism design applies game theory to deal with situations where agent valuations are taken into account. We formalize the problem and design a $2t$-approximated mechanism which is truthful in expectation. The mechanism produces a solution that takes into account the opinions (as values) of surgeons on patients risk, while also improving the scheduling.
To address the practical impact of the solution, we implemented the mechanism solution in a simulation environment that uses the data of Chilean hospitals given by various public healthcare institutions. Given practical issues we opt for an implementation that minimizes the quadratic error to the truthful solution. Results are compared with simpler scheduling methods as well as a classifier trained in the original data, approximating current behavior. This comparison showed similar performance to metric specific optimizing methods, while also maximizing the social benefit which includes surgeon valuations.

[Download paper here](https://anduresu.github.io/files/MSc_Thesis_AndresOArredondo.pdf)