---
title: "Safe and Smooth: Certified Continuous-Time Range-Only Localization"
collection: publications
permalink: /publication/2023-02-01-Safe-and-Smooth-Certified-Continuous-Time-Range-Only-Localization
date: 2023-02-01
venue: 'IEEE Robotics and Automation Letters'
citation: ' Frederike D{\&quot;u}mbgen,  Connor Holmes,  Timothy Barfoot, &quot;Safe and Smooth: Certified Continuous-Time Range-Only Localization.&quot; IEEE Robotics and Automation Letters, 2023.'
---

**Abstract**: A common approach to localize a mobile robot is by measuring distances to points of known positions, called anchors. Locating a device from distance measurements is typically posed as a non-convex optimization problem, stemming from the nonlinearity of the measurement model. Non-convex optimization problems may yield suboptimal solutions when local iterative solvers such as Gauss-Newton are employed. In this letter, we design an optimality certificate for continuous-time range-only localization. Our formulation allows for the integration of a motion prior, which ensures smoothness of the solution and is crucial for localizing from only a few distance measurements. The proposed certificate comes at little additional cost since it has the same complexity as the sparse local solver itself: linear in the number of positions. We show, both in simulation and on real-world datasets, that the efficient local solver often finds the globally optimal solution (confirmed by our certificate), but it may converge to local solutions with high errors, which our certificate correctly detects.

Use [Google Scholar](https://scholar.google.com/scholar?q=Safe+and+Smooth:+Certified+Continuous+Time+Range+Only+Localization){:target="_blank"} for full citation