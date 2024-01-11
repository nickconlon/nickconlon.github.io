---
title: "Event-Triggered Generalized Outcome Assessment (ET-GOA) Evaluation"
excerpt: "A project to evaluate the ET-GOA algorithm which enables a robot to understand when and how its competency changes."
collection: portfolio
---

This project investigated how an autonomous robot could capture and understand both <i>when</i> and <i>how</i> its
competency may change during a mission. As an extension to Factorized Machine Self-Confidence, we developed a Model
Quality Assessment which assesses how close an agent's model predictions are from real observations. We then developed
the Event-Triggered Generalized Outcome Assessment (ET-GOA) algorithm which uses the Model Quality assessment to selectively
trigger a Generalized Outcome Assessment in real-time. We validated the Model Quality Assessment and ET-GOA algorithm
in both simulation and with a live unmanned ground vehicle. We believe that real-time updating and communication of
competency can calibrate human users to changing robot capabilities, so they can make more informed and safer decisions
with respect to their robotic counterparts.

<!--br/><img src='/images/500x300.png'-->

This project extends the following:

[Generalizing Competency Self-Assessment for Autonomous Vehicles Using Deep Reinforcement Learning](https://arc.aiaa.org/doi/10.2514/6.2022-2496)

[Dynamic Competency Self-Assessment for Autonomous Agents](https://arxiv.org/abs/2303.01646)

We published this article: 

[Event-triggered robot self-assessment to aid in autonomy adjustment](https://www.frontiersin.org/articles/10.3389/frobt.2023.1294533/full)

You can find the code on GitHub here: 

[Event-Triggered Generalized Outcome Assessment (ET-GOA) Evaluation](https://github.com/nickconlon/goa_robot_study)