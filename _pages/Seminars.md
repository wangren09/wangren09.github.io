---
layout: archive
title: "Seminars"
permalink: /Seminars/
author_profile: true
---

### Frontiers of Data Science (FDS) Seminar (Organized by Ming Zhong, Ren Wang, Binghui Wang)

10/06/2023: [Ermin Wei](http://users.eecs.northwestern.edu/~erminwei/) Associate Professor at the Electrical and Computer Engineering Department and Industrial Engineering and Management Sciences Department of Northwestern University

**Title**: Flexible and Faithful Federated Learning and Unlearning Methods

**Abstract**: Federated learning enables machine learning algorithms to be trained over decentralized edge devices without requiring the exchange of local datasets. We consider two scenarios in this talk. In the first scenario, we have cooperative agents running distributed optimization methods. Current literature fail to capture the heterogeneity in agents’ local computation capacities. We propose FedHybrid as a hybrid primal-dual method that allows heterogeneous agents to perform a mixture of first and second order updates.  We prove that FedHybrid converges linearly to the exact optimal point for strongly convex functions. In the second scenario, we consider strategic agents with different data distributions. We analyze how the distribution of data affects agents' incentives to voluntarily participate and obediently follow traditional federated learning algorithms. We design a Faithful Federated Learning (FFL) mechanism based on FedAvg method and VCG mechanism which achieves (probably approximate) optimality, faithful implementation, voluntary participation, and balanced budget. Lastly, we analyze an alternative approach to align individual agent’s incentive to participate by allowing unlearning option. We propose a multi-stage game theoretic framework and study the equilibrium properties.


10/10/2023: [Shuo Han](https://hanshuo.people.uic.edu/site/) Assistant Professor at the Department of Electrical and Computer Engineering of University of Illinois at Chicago

**Title**: Strategic Influencing in Multi-Agent Systems

**Abstract**: In a multi-agent system, it is well known that an agent is capable of implicitly influencing the behaviors of other agents by playing her actions strategically. This allows the agent to potentially take advantage of opponents in a competitive setting or facilitate coordination with partners in a collaborative setting. In game theory, an optimal influencing strategy is characterized by the solution concept of Stackelberg equilibrium. Nevertheless, efficient and provably correct algorithms for computing a Stackelberg equilibrium only exist for relatively simple games. In this talk, I will discuss methods for computing a Stackelberg equilibrium in more complex and realistic game setups, including 1) influencing an agent who makes sequential decisions and 2) influencing multiple types of agents.

10/17/2023: [Jinshuo Dong](https://www2.math.upenn.edu/~jinshuo/) post-doc at IDEAL (i.e. Northwestern University and TTI Chicago)

**Title**: The Design Choice of Privacy as a Rigid Constraint

**Abstract**: Privacy is a top-priority concern when modern data science achievements are applied to sensitive data. Typically it is imposed as a hard constraint, while other measures such as utility are set as the optimization objective. In this talk, we delve into this design choice by analyzing its consequences in two specific scenarios. More specifically, we provide answers to the following questions:
1. Is it possible to deplete the privacy budget in the most basic application of differential privacy?
2. Can we battle against strategic behavior while maintaining hard privacy constraints in legal proceedings (in particular, electronic discovery)?
The first question suggests a hypothesis testing perspective of differential privacy, and for the second we design an incentive-compatible mechanism that relate the privacy loss to a geometric quantity -- the number of extremal points after a projective transformation. Our findings suggest that privacy as a rigid constraint warrants careful consideration depending on the context.
