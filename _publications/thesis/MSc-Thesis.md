---
title: "Approximated Algorithmic Mechanism for Scheduling Chilean Operating Rooms with Multi-Agent Based Simulation"
collection: 'publications'
permalink: /publication/MSc_Thesis
excerpt: ''
date: 2021-12-02
venue: 'MSc. Thesis'
---
The Operating Room Scheduling Problem (ORSP) consists of efficiently allocating re-
sources in operating rooms. The scheduling of staff, patients and time are some of the most
problematic issues considering unexpected emergency cases and overtime surgeries. Even
without these issues, the lack of an objective indicator that points out who to attend com-
plicates the task.
Most of the optimization solutions, in theory and practice make use of deadlines and costs
as objective functions. Deadlines are usually set for a diagnosis and not for the specific
patient, though, in the Chilean healthcare system only a specific subset of patients have
deadlines for their cases. Optimization literature describes how to obtain an optimal or near
optimal schedule, however, surgeons must approve these schedules and make changes given
that some patients may need treatment with more urgency than what is shown in the data:
ultimately, they are the ones with the most information about patients. These changes affect
the optimality of results to an unknown extent and give space to misaligned incentives.
Mechanism design applies game theory to deal with situations where agent valuations are
taken into account. We aim to design a practical mechanism to obtain a schedule that takes
into account the opinion of surgeons on patients risk, while also improving the scheduling
system on other metrics: given the importance of the task, such mechanism should not allow
untruthful behaviour.
We formalize the scheduling problem as a mechanism variation of the operating room
scheduling problem, and we prove that such a mechanism is NP-complete. Given these
results, we propose an 2t-approximation algorithm in expectation which, in combination
with the work of Lavi and Swamy, give a 2t-approximation truthful in expectation mechanism
[17]. To obtain this result, we improve on an scheduling problem with a 6t-approximation
algorithm by giving a 2t-approximation.
To address the practical impact of the solution, we implemented the mechanism solution
in a simulation environment that uses the data of Chilean hospitals given by various public
healthcare institutions. Given practical issues with the approximation mechanism, we opt
for an implementation that makes the mechanism non-truthful, but minimizes the quadratic
error to the truthful solution in the spirit of Vickrey-nearest core-selecting auctions [27]. This
method allows the quantification of the benefit of not showing true valuations. Results are
compared with simpler scheduling methods as well as the original schedule, which our mech-
anism improves. This comparison showed similar performance to metric specific optimizing
methods, while also maximizing the social benefit which includes surgeon valuations.

[Download paper here](https://anduresu.github.io/files/MSc_Thesis_AndresOArredondo.pdf)