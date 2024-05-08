---
title: "On Semidefinite Relaxations for Matrix-Weighted State-Estimation Problems in Robotics"
collection: publications
permalink: /publication/2023-08-01-On-Semidefinite-Relaxations-for-Matrix-Weighted-State-Estimation-Problems-in-Robotics
date: 2023-08-01
venue: 'arXiv:2308.07275'
citation: ' Connor Holmes,  Frederike D{\&quot;u}mbgen,  Timothy Barfoot, &quot;On Semidefinite Relaxations for Matrix-Weighted State-Estimation Problems in Robotics.&quot; arXiv:2308.07275, 2023.'
---

**Abstract**: In recent years, there has been remarkable progress in the development of so-called certifiable perception methods, which leverage semidefinite, convex relaxations to find global optima of perception problems in robotics. However, many of these relaxations rely on simplifying assumptions that facilitate the problem formulation, such as an isotropic measurement noise distribution. In this paper, we explore the tightness of the semidefinite relaxations of matrix-weighted (anisotropic) state-estimation problems and reveal the limitations lurking therein: matrix-weighted factors can cause convex relaxations to lose tightness. In particular, we show that the semidefinite relaxations of localization problems with matrix weights may be tight only for low noise levels. We empirically explore the factors that contribute to this loss of tightness and demonstrate that redundant constraints can be used to regain tightness, albeit at the expense of real-time performance. As a second technical contribution of this paper, we show that the state-of-the-art relaxation of scalar-weighted SLAM cannot be used when matrix weights are considered. We provide an alternate formulation and show that its SDP relaxation is not tight (even for very low noise levels) unless specific redundant constraints are used. We demonstrate the tightness of our formulations on both simulated and real-world data.

Use [Google Scholar](https://scholar.google.com/scholar?q=On+Semidefinite+Relaxations+for+Matrix+Weighted+State+Estimation+Problems+in+Robotics){:target="_blank"} for full citation