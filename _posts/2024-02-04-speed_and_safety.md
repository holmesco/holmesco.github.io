---
title: 'From Speed To Safety in Robotics'
date: 2024-02-04
permalink: /posts/
tags:
  - certifiable methods
---


The field of robotics is one that has always been full of practical challenges. By far, one of the greatest hurdles that every roboticist faces is that of designing algorithms that can be deployed for *realtime* operation. There is a tacit expectation in the robotics community and -- perhaps more importantly -- in broader society that robots *should* be able to perform tasks as fast as any human (or animal) can. This expectation has pushed the field to produce incredibly efficient methods, but it has also led to reliance on algorithms that prioritize speed rather than safety.

In particular, almost all robots rely on *local optimization methods* to perform most of their tasks, from state estimation to motion planning to control execution. Though these methods have become very fast over the past decades, it is well known that they have one crucial flaw: if these methods are not initialized well, they can produce solutions that are completely incorrect. What is worse, a robot that is using these methods will remain completely unaware of their failure. 

As such, there has been a growing interest in the robotics and vision community in so-called **certifiably correct methods**. These methods typically leverage **convex relaxations** of robotics problems to either provide a check the validity of solutions or provide a solution that is *guaranteed* to be correct (regardless of initialization). In other words, these methods can imbue robotic algorithms with immunity to the failure mode mentioned above. 

This immunity is not without its own unique set of challenges. These relaxations often involve solving the problem in a much higher dimensional space, leading to problems with speed and scalability. My current research is concerned with addressing these challenges in the context of robotics.