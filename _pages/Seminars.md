---
layout: archive
title: "Seminars"
permalink: /Seminars/
author_profile: true
---

## Frontiers of Data Science (FDS): Theory, Applications, and Trustworthiness
### Organized by Ming Zhong, Ren Wang, Binghui Wang

**10/06/2023**: [Ermin Wei](http://users.eecs.northwestern.edu/~erminwei/) Associate Professor at the Electrical and Computer Engineering Department and Industrial Engineering and Management Sciences Department of Northwestern University

**Time and Location**: 12:45 pm - 1:45 pm, Siegel Hall 118 (The Auditorium)

**Title**: Flexible and Faithful Federated Learning and Unlearning Methods

**Abstract**: Federated learning enables machine learning algorithms to be trained over decentralized edge devices without requiring the exchange of local datasets. We consider two scenarios in this talk. In the first scenario, we have cooperative agents running distributed optimization methods. Current literature fail to capture the heterogeneity in agents’ local computation capacities. We propose FedHybrid as a hybrid primal-dual method that allows heterogeneous agents to perform a mixture of first and second order updates.  We prove that FedHybrid converges linearly to the exact optimal point for strongly convex functions. In the second scenario, we consider strategic agents with different data distributions. We analyze how the distribution of data affects agents' incentives to voluntarily participate and obediently follow traditional federated learning algorithms. We design a Faithful Federated Learning (FFL) mechanism based on FedAvg method and VCG mechanism which achieves (probably approximate) optimality, faithful implementation, voluntary participation, and balanced budget. Lastly, we analyze an alternative approach to align individual agent’s incentive to participate by allowing unlearning option. We propose a multi-stage game theoretic framework and study the equilibrium properties.
<br/><br/>

**10/10/2023**: [Shuo Han](https://hanshuo.people.uic.edu/site/) Assistant Professor at the Department of Electrical and Computer Engineering of University of Illinois at Chicago

**Time and Location**: 12:45 pm - 1:45 pm, Siegel Hall 118 (The Auditorium)

**Title**: Strategic Influencing in Multi-Agent Systems

**Abstract**: In a multi-agent system, it is well known that an agent is capable of implicitly influencing the behaviors of other agents by playing her actions strategically. This allows the agent to potentially take advantage of opponents in a competitive setting or facilitate coordination with partners in a collaborative setting. In game theory, an optimal influencing strategy is characterized by the solution concept of Stackelberg equilibrium. Nevertheless, efficient and provably correct algorithms for computing a Stackelberg equilibrium only exist for relatively simple games. In this talk, I will discuss methods for computing a Stackelberg equilibrium in more complex and realistic game setups, including 1) influencing an agent who makes sequential decisions and 2) influencing multiple types of agents.
<br/><br/>

**10/17/2023**: [Jinshuo Dong](https://www2.math.upenn.edu/~jinshuo/) Post-doc at IDEAL (Northwestern University and TTI Chicago)

**Time and Location**: 12:45 pm - 1:45 pm, Siegel Hall 118 (The Auditorium)

**Title**: The Design Choice of Privacy as a Rigid Constraint

**Abstract**: Privacy is a top-priority concern when modern data science achievements are applied to sensitive data. Typically it is imposed as a hard constraint, while other measures such as utility are set as the optimization objective. In this talk, we delve into this design choice by analyzing its consequences in two specific scenarios. More specifically, we provide answers to the following questions:
1. Is it possible to deplete the privacy budget in the most basic application of differential privacy?
2. Can we battle against strategic behavior while maintaining hard privacy constraints in legal proceedings (in particular, electronic discovery)?
The first question suggests a hypothesis testing perspective of differential privacy, and for the second we design an incentive-compatible mechanism that relate the privacy loss to a geometric quantity -- the number of extremal points after a projective transformation. Our findings suggest that privacy as a rigid constraint warrants careful consideration depending on the context.
<br/><br/>

**10/24/2023**: [Lifan Wang](https://physics.tamu.edu/directory/lifan/) Professor in Astrophysics at Texas A&M University


**Time and Location**: 12:45 pm - 1:45 pm, Siegel Hall 203

**Title**: A Data-Driven Approach to Spectroscopic Analyses in Astronomy

**Abstract**: Spectroscopic diagnostics plays a crucial role in astronomical studies. The observed photons experience extensive interaction among hundreds of thousands of atomic lines before escaping. Spectral features are broadened and blended in rapidly expanding objects like supernovae. AI has the potential to disentangle the coupling of the atomic lines and achieve quantitative measurement of the chemical compositions based on the observed spectra. This goal can be accomplished in two approaches. The first one is based on empirical analysis of observational data. Neural networks can be built to reduce the dimensionality of the problem. The second is to build physics-informed neural networks and construct physical models with observational data as the initial/boundary conditions. I will show the applications of these two to the studies of Type Ia supernovae, considered the most accurate extragalactic distance calibrators in the Universe.


**10/31/2023**: [Wei Cai](https://www.smu.edu/Dedman/Academics/Departments/Math/People/Faculty/WeiCai) Professor in Southern Methodist University


**Time and Location**: 10 am - 11 am, John T. Rettaliata Engineering Center 103

**Title**: DeepMartNet - A Martingale based Deep Neural Network Algorithm for Eigenvalue/BVP Problems of PDEs and Optimal Stochastic Controls

**Abstract**: In this talk, we will present a deep neural network (DNN) learning algorithm for solving high dimensional Eigenvalue (EV) and boundary value problems (BVPs)  for elliptic operators and initial BVPs (IBVPs) of quasi-linear parabolic equations as well as optimal stochastic controls. The method is based on the Martingale property in the stochastic representation for the eigenvalue/BVP/IBVP problems and martingale principle for optimal stochastic controls. A loss function based on the Martingale property can be used for an efficient optimization by sampling the stochastic processes associated with the elliptic operators or value process  for stochastic controls. The Martingale property conforms naturally with the stochastic gradient descent process  for the DNN optimization. The proposed algorithm can be used for eigenvalue problems and BVPs and  IBVPs with Dirichlet, Neumann, and Robin boundaries in bounded or unbounded domains and some feedback stochastic control problems. Numerical results for BVP and EV problems in high dimensions will be presented.


**11/14/2023**: [Meng Wang](https://ecse.rpi.edu/people/faculty/meng-wang) Associate Professor at Rensselaer Polytechnic Institute (RPI)

**Time and Location**: 12:45 pm - 1:45 pm, Siegel Hall 118 (The Auditorium)

**Title**: Computationally Efficient Deep Learning with Generalization Guarantees

**Abstract**: Deep learning has demonstrated extraordinary empirical success in various applications. Despite the great promise, DL has significant computation requirements. Moreover, DL lacks interpretability and performance guarantees and often acts as the “black box” due to its extreme complexity. This talk introduces our ongoing efforts to reduce the computation cost of deep learning while maintaining its ability to generalize on unseen data. Our first approach is network pruning, which removes part of the neuron weights in a complex model to reduce the inference cost. We illustrate how the degree of network sparsity impacts sample complexity and convergence rates quantitatively. Furthermore, we establish that typical magnitude-based pruning methods can effectively reduce model size without compromising generalization performance across a broad range of scenarios. Our second approach is the Mixture of Experts (MoE) architecture, which routes each input to a few subnetworks (termed as experts) rather than processing it through the entire network to reduce computation. We explore the application of patch-level MoEs (pMoEs) in vision and language tasks and offer the first theoretical guarantee of their generalization performance. We demonstrate that pMoEs simultaneously reduce sample complexity, computational complexity, and model complexity while maintaining equivalent generalization accuracy.


**11/17/2023**: [Neil Gong](https://ece.duke.edu/faculty/neil-gong) Assistant Professor at Duke University

**Time and Location**: 12:45 pm - 1:45 pm, Stuart Building 111

**Title**: Secure Content Moderation for Generative AI

**Abstract**: Generative AI–such as GPT-4 and DALL-E 3–raises many ethical and legal concerns such as the generation of harmful content, scaling disinformation and misinformation campaigns, as well as disrupting education and learning. Content moderation for generative AI aims to address these ethical and legal concerns via 1) preventing a generative AI model from synthesizing harmful content, and 2) detecting AI-generated content. Prevention is often implemented using safety filters, while detection is implemented by watermark. Both prevention and watermark-based detection have been recently widely deployed by industry. In this talk, we will discuss the security of existing prevention and watermark-based detection methods in adversarial settings.

<br/><br/>
