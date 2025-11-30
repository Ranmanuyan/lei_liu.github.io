---
layout: archive
title: "Stochastic Systems & Learning LAB"
permalink: /SSL/
author_profile: true
---


Every dynamic system in the world—from manufacturing lines to healthcare operations—is governed by **stochastic, rule-based steps**. We view this complexity not as chaos, but as a discoverable mathematical structure.

We encode system behavior using **Continuous-Time Markov Chains (CTMC)** and **Phase-Type (PH) Distributions**. 

* **The States:** We model a system as moving through a vast set of possible **states** (e.g., "Job A on Machine 2, Phase 3").
* **The Matrix:** All transition rates and probabilities are contained within a massive **Transfer Rate Matrix ($\mathbf{Q}$)**. This matrix is our unique tool for unlocking risk.

By using specialized **Matrix Algebra** (like Kronecker operations) and high-performance solvers, we can **analytically compute exact measures of risk**.

We use the power of **Deep Learning** (Reinforcement Learning/Neuro-Symbolic AI) to efficiently search the combinatorial space, while using the **Matrix** as a perfect, noise-free **Reward Function**. 
Our goal is to find the **optimal control rules** hidden within the chain, allowing systems to operate with speed and guaranteed precision.



<!---
### 🚀 The Learning Breakthrough: Analytical Reward RL

We use the power of **Deep Learning (RL/Transformer Networks)** to efficiently search the combinatorial space. Crucially, we leverage the **Matrix solution** as a **perfect, zero-variance Reward Function** for our learning agent. This unique **Analytical Reward RL** approach allows us to:

1.  **Avoid Simulation Noise:** Train faster and more robustly than traditional RL.
2.  **Ensure Guaranteed Precision:** Find **optimal control rules** that operate with mathematical precision, not just approximate averages.

--->

## Research Projects

### Stochastic Flow Shop Scheduling: From Theory to AI Control

The Flow Shop Scheduling Problem, where $n$ jobs must visit $m$ machines in a fixed order with random processing times, is a fundamental challenge in optimization.

* **The Core Problem:** For $m \geq 3$ machines and general processing-time distributions, no exact method exists to find the optimal job permutation. While classical rules (Johnson’s, Talwar’s) solved the $m=2$ case for specific distributions, the general case requires advanced stochastic analysis.
<!---
* **Our Analytical Foundation:** We embed the flow shop in a **CTMC** whose state records the current **phase** of every active job. This yields a system of linear differential equations, providing the **first exact evaluation method for any fixed permutation** under general **Phase-Type (PH) distributions**.
* **The AI Leap (New):** We integrate this exact evaluation method into a **PPO/Transformer** framework. The Transformer network learns to construct the optimal sequence, guided by the CTMC's **zero-variance analytical reward**. This **RL-driven Hyper-heuristic** approach is currently deployed to tackle the $m \geq 3$ case, seeking non-linear scheduling rules that minimize system-wide stochastic risk.


### High-Impact Application Domains

#### 1. 🏥 Resilient Surgery Scheduling: Optimizing Tail Risk in Operating Rooms

Surgical operations represent high-stakes stochastic processes where unpredictable emergency arrivals, variable durations, and complex resource constraints lead to significant patient risk and cost overruns.

* **The Challenge:** Traditional scheduling is manual or relies on simple averages, leading to inflexibility and failure to control **tail risk** (low-probability, high-impact events like excessive delays).
* **Our Approach (Focus on Risk):** We model the OR system as a **CTMC** to precisely quantify the probability of critical events (e.g., $P(\text{Surgery delay} > 2 \text{ hours})$). Our **Learning Agent** is trained not to minimize average wait time, but to **minimize tail risk**, dynamically optimizing surgical resource allocation and staff coordination to build a truly resilient surgical schedule.

#### 2. 🚑 Emergency Medical Service (EMS) Network Optimization

This project aims to enhance the delivery of critical EMS services by optimizing resource allocation and dispatching strategies for ambulances and paramedics.

* **The Challenge:** Saving lives depends on minimizing response time variability, which is compounded by highly unpredictable demand patterns and complex travel times.
* **Our Approach (Focus on Fusion):** We use **advanced predictive models (e.g., Diffusion Models)** to accurately forecast high-demand areas, translating these spatial-temporal patterns into **Phase-Type distributions**. We then employ our **Analytical Reward RL platform** to develop **prescriptive dispatching, scheduling, and routing rules** that are optimized against the **exact expected survival probability**.  This fusion ensures that the right resources are positioned proactively and dispatched optimally, maximizing community survival outcomes based on mathematically guaranteed metrics.
--->


<!---
## Hybrid approach on Mixed-integer programming and Constraint programming
- Mixed-integer programming (MIP), rooted in strong linear relaxations and duality theory, has provided exact algorithms for discrete optimisation for over six decades; commercial solvers such as Gurobi and IBM CPLEX now implement these ideas at industrial scale. 
- Constraint programming (CP), originating in computer science, complements MIP by exploiting combinatorial structure through domain filtering and propagation, often with particular effectiveness in scheduling. 
- For years these two camps worked separately. My current fascination was to bolt them together, MIP supplies global dual bounds, while CP supplies domain reduction. Hoping the resulting hybrid algorithms may dominate either technique used in isolation.
--->



## People

#### PhD


Yifan Bao, Feb 2025.


#### UG
Ziyue XU, July 2025.

## Positions
_If you have a strong background in optimization/operations research/industrial engineering, coupled with good knowledge of mathematics and/or computer science, you are encouraged to apply for the PhD position._

