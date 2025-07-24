---
layout: archive
title: "Computational Optimization"
permalink: /HOME/
author_profile: true
---


# Computational Optimization is the point where elegant mathematics and powerful computer science intersect

## Stochastic Flow shop scheduling
A classical puzzle is the flow-shop scheduling problem: given n jobs and m machines, each job must visit the machines in the same fixed order, and the processing time of job j on machine i is a non-negative random variable. The goal is to choose a permutation of the jobs that minimizes some objectives.
- For m = 2 and deterministic processing times, Johnson’s rule (1954) delivers the optimal permutation in O(n log n) time.
- For m = 2 and exponentially-distributed processing times, Talwar’s rule (1967) does the same.
- The natural next question—my starting point—was the case of general distributions on two machines. Phase-type (PH) distributions form a dense subset of all distributions on $R+$, any distribution can be approximated arbitrarily closely by a PH distribution. A PH distribution itself is the absorption-time distribution of a finite-state continuous-time Markov chain (CTMC) whose transient states are all exponential. Exploiting this structure, I embedded the two-machine flow shop in a CTMC whose state records the current phase of every active job on each machine. This yields a system of linear differential equations whose solution gives the exact evaluation for any fixed permutation. Closed-form expressions for the optimal permutation remain elusive, but the construction provides the first exact evaluation method for the two-machine case under general processing-time distributions. 
The extension to m ≥ 3 machines is now in progress, with the same PH/CTMC framework scaled by tensor-product state spaces.

## MIP+CP
Mixed-integer programming (MIP), rooted in strong linear relaxations and duality theory, has provided exact algorithms for discrete optimisation for over six decades; commercial solvers such as Gurobi and IBM CPLEX now implement these ideas at industrial scale. Constraint programming (CP), originating in computer science, complements MIP by exploiting combinatorial structure through domain filtering and propagation, often with particular effectiveness in scheduling. For years these two camps worked separately. My fascination was to bolt them together, MIP supplies global dual bounds, while CP supplies domain reduction. Hoping the resulting hybrid algorithms may dominate either technique used in isolation.


## Applications 

Equipped with these methodologies, we solved various real problems, especially in healthcare area.

#### 1\. _Surgery (Operating room) scheduling. Collaborated with **Ningbo First Hospital**._

Surgical operations are a crucial component of healthcare services, necessitating significant investment in costly equipment and human resources. The efficiency of surgical resource utilization is a cornerstone for cost reduction, work efficiency enhancement, and patient satisfaction. Presently, operating room scheduling is predominantly manual, leading to inflexibility, resource allocation disparities, and inefficiencies that increase patient wait times. The challenge of creating an effective operating room schedule is compounded by unpredictable emergency surgery arrivals, variable surgery durations, constraints related to specialized equipment, and the necessity for interdepartmental and staff coordination. This research project aims to address these challenges by developing sophisticated scheduling strategies that can handle the inherent complexities and unpredictabilities of the healthcare environment, improve resource use, and ultimately enhance the overall quality of care.


#### 2\. _Emergency Medical Service location and dispatching. Collaborated with **Ningbo Emergency Center**._

The objective of this project is to enhance the delivery of emergency medical services (EMS) by optimizing resource allocation and dispatching strategies for ambulances and paramedics. Leveraging state-of-the-art machine learning techniques, we aim to develop predictive models capable of accurately forecasting high-demand areas for emergency services. These forecasts will enable proactive positioning of EMS resources to ensure rapid response times. To translate these forecasts into actionable strategies, we will employ advanced operations research methodologies for prescriptive analysis. This will allow us to make informed decisions regarding the dispatching, scheduling, and routing of EMS vehicles and personnel. Our approach is designed to ensure that the right resources—with appropriate equipment and trained teams—are dispatched in a timely manner, thereby reducing response times and potentially saving lives. The project will be conducted in close collaboration with the Ningbo 120 emergency centre, drawing upon their operational insights and data to inform our models. Additionally, the initiative is supported by the Nottingham China Health Institute, which will provide both expertise and resources to aid in the research and implementation of our findings.




## People

#### PhD


Yifan Bao, Feb 2025.

Yiwen Hu, Sept 2024.

## Positions
_If you have a strong background in optimization/operations research/industrial engineering, coupled with good knowledge of mathematics and/or computer science, you are encouraged to apply for the PhD position._

