---
title: "An Efficient Global Optimality Certificate for Landmark-Based SLAM"
collection: publications
permalink: /publication/2023-03-01-An-Efficient-Global-Optimality-Certificate-for-Landmark-Based-SLAM
date: 2023-03-01
venue: 'IEEE Robot. Autom. Lett.'
citation: ' Connor Holmes,  Timothy Barfoot, &quot;An Efficient Global Optimality Certificate for Landmark-Based SLAM.&quot; IEEE Robot. Autom. Lett., 2023.'
---

**Abstract**: Modern state estimation is often formulated as an optimization problem and solved using efficient local search methods. These methods at best guarantee convergence to local minima, but, in some cases, global optimality can also be certified. Although such global optimality certificates have been well established for 3D pose-graph optimization, the details have yet to be worked out for the 3D landmark-based SLAM problem, in which estimated states include both robot poses and map landmarks. In this letter, we address this gap by using a graph-theoretic approach to cast the subproblems of landmark-based SLAM into a form that yields a sufficient condition for global optimality. Efficient methods of computing the optimality certificates for these subproblems exist, but first require the construction of a large data matrix. We show that this matrix can be constructed with complexity that remains linear in the number of landmarks and does not exceed the stateof-the-art computational complexity of one local solver iteration. We demonstrate the efficacy of the certificate on simulated and real-world landmark-based SLAM problems. We also integrate our method into the state-of-the-art SE-Sync pipeline to efficiently solve landmark-based SLAM problems to global optimality. Finally, we study the robustness of the global optimality certificate to measurement noise, taking into consideration the effect of the underlying measurement graph.

Use [Google Scholar](https://scholar.google.com/scholar?q=An+Efficient+Global+Optimality+Certificate+for+Landmark+Based+SLAM){:target="_blank"} for full citation