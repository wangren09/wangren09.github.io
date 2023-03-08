---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---


**1. Robust AI Guided by the Immune System**
------
Driven by rapid advances in neural networks (NNs), artificial intelligence has achieved remarkable success in many fields. However, small perturbations invisible to humans can be purposely added to inputs to cause NNs to make incorrect predictions. What is more, attackers can even customize different perturbation strategies to bypass existing NNs' learning methods and defenses. Thus, one open question is how to make NNs more robust to such adversarial perturbations. Humans have a highly evolved immune system that can defend against multiple threats, even those never encountered before. Inspired by the powerful immune system, this project aims to infuse key immune system principles into NNs to reduce the substantial gap between existing machine-centric robust learning frameworks and robust immune models. The project requires techniques such as population-based optimization, robust training, knowledge distillation, etc.

<div  align="center">
<img src='/images/immune_AI.png' width='500'>
</div>


**2. Robust AI with Theoretical Guarantee**
------
The project aims at (1) developing mathematical tools for supporting reliable implementations of AI algorithms (2) developing AI algorithms that are capable of making decisions and performing tasks in the face of uncertainties and perturbations. The project seeks to provide theoretical guarantees for the robustness of these algorithms, ensuring that they are able to maintain their performance and accuracy even when faced with unexpected and malicious inputs in an unreliable environment. The project involves the use of advanced techniques from mathematics, statistics, and computer science to develop algorithms that are capable of making AI systems more reliable, secure, and trustworthy. The ultimate goal of the project is to develop AI systems that are robust and reliable in real-world scenarios, enabling their safe and ethical deployment across a wide range of industries and applications.

<div  align="center">
<img src='/images/CNN_Recovery.png' width='500'>
</div>

**3. Backdoor Detection and Mitigation**
------
Backdoor attacks are a category of attacks on deep learning models where an attacker inserts a hidden trigger pattern into the training data, which can cause the model to misclassify inputs containing that pattern. Backdoor attacks can be difficult to detect and mitigate. This porject aims to detect and mitigate backdoor in different learning phases (data processing, training, and inference).

<div  align="center">
<img src='/images/DFTND_Framework.png' width='400'>
<img src='/images/Trojan3.JPG' width='240'>
</div>


**4. Privacy protection in AI**
------
One big concern is the exposure of privacy brought on by the data-intensive nature of AI, which may cause destructive outcomes, e.g., allowing hackers to lock you out of your house that uses smart locks. There are two fundamental challenges to preserve privacy in AI: (1) Privacy protection often stands at odds with AI's data requirements; (2) Privacy must be considered along the entire end-to-end pipeline - from data ingestion to model applications. The project will involve developing methods to preserve privacy throughout the AI workflow without compromising state-of-the-art performance.
<div  align="center">
<img src='/images/Quantization_tensor.png' width='550'>
  <img src='/images/multi_trig_key.png' width='450'>
</div>

**5. Data-Driven Methods in Power System with Physics-Constraints**
------
The project aims at developing advanced machine learning and data-driven algorithms to optimize power system operations while respecting physical constraints. The project seeks to leverage large amounts of data from various sources, including PMU, SCADA, and weather forecasts, to predict and optimize power system behavior and improve energy efficiency. The project also aims to incorporate physics-based models and constraints to ensure that the optimized solutions are safe, reliable, and stable. The ultimate goal of the project is to develop scalable and efficient data-driven methods that can help transform the power sector towards a more sustainable and resilient future.

<div  align="center">
<img src='/images/data_driven_power_grid.png' width='500'>
</div>


<!--
**Robust AI Guided by the Immune System**
------
[RAILS:](https://github.com/wangren09/RAILS) We proposed a novel deep defense framework, **Robust Adversarial Immune-inspired Learning System (RAILS)**, by emulating the key mechanisms of the mammalian immune system. Here is a brief introduction to RAILS and a demo of RAILS [Intro and Demo:](https://drive.google.com/file/d/1vnOMEo4iOHjn7bU-WWwoh6nD8Ugtd7wD/view?usp=sharing).

**Comparions Between Simplified Immune System and RAILS Computational Workflow:**
<div  align="center">
<img src='/images/bio_comp_v5.png' width='600'>
</div>

**Performance and Architecture:**
<p align="center">
  <img src="/images/RAILS_Arch.png" width="335" />
  <img src="/images/radar_new.png" width="450" /> 
</p>



**Robustness on Deep Non-Parametric Learning**
------
[ASK:](https://github.com/wangren09/ASK) We generated a novel **Adversarial Soft kNN Attack**, which has **superior attack efficiency and accuracy degradation** relative to previous kNN-based attacks. We developed an **Adversarial Soft kNN Defense** that can **improve the robustness** of both kNN-based classifiers and DNNs.

**Results and Visualization:**
<div  align="center">
<img src='/images/ASK1.png' width='335'>
<img src='/images/ASK3.jpg' width='450'>
</div>

**Robustify decision boundaries:**
<div  align="center">
<img src='/images/ASK2.png' width='500'>
</div>

**Towards Robustness in Meta-Learning Against Test Phase Attacks**
------
[MetaAdv:](https://github.com/wangren09/MetaAdv) We studied how adversarial robustness can be maintained in **few-shot learning** and proposed an **efficient adversarial few-shot learning framework**.

<div  align="center">
<img src='/images/MetaAdv.png' width='475'>
</div>
 
**Backdoor Model Detection Under Data-Scarce Regime**
------
[TrojanNet:](https://github.com/wangren09/TrojanNetDetector) We proposed **backdoor model detectors** that can effectively recognize **poisoned models** and reveal the **corresponding backdoor triggers** under the **data-limited** and **data-free** regimes.

**Trojan (backdoor) attack, frameworks, and trigger detection:**
<div  align="center">
<img src='/images/DFTND_Framework.png' width='400'>
<img src='/images/Trojan3.JPG' width='240'>
</div>


**Simultaneous Achievement of Data Privacy And Information Accuracy: Provable Privacy Protection in the Data Collection/Processing Phase**
------
We developed a **data privacy preserving framework** through quantization. We further developed an efficient data recovery method based on the nonconvex optimization and high-dimensional statistics such that the recovery error diminishes to zero. The method guarantees that any intruder accessing a small amount of data cannot reveal accurate information even with the knowledge of the quantization rule. Towards security enhancement, We developed a **distributed algorithm** such that multiple data owners could collect and process data separately and then collaboratively recover the data without sharing the raw information directly.

**Privacy protection:**
<div  align="center">
<img src='/images/Quantization_tensor.png' width='550'>
</div>

**Information extraction with prior knowledge:**
<div  align="center">
<img src='/images/DP2.png' width='330'>
</div>


**Multi-Trigger-Key: Privacy Protection in the Model Inference Phase**
------
We introduced a **Multi-Trigger-Key framework** that associates each protected task with a specifically designed trigger-key. The true information can be revealed by adding the trigger-key if the user is authorized.

**Multi-Trigger-Key Framework:**
<div  align="center">
<img src='/images/multi_trig_key.png' width='450'>
</div>



**Smart Grid Robustness and Uncertain Optimization with High-Penetration of Renewable Energy**
------
We proposed methods to **analyze the power grid robustness** and optimize the **economic dispatch** when considering highly stochastic renewable energy.

<div  align="center">
<img src='/images/smartg1.jpg' width='250'>
<img src='/images/smartg2.jpg' width='200'>
</div>

-->


<!-- 
**Twitter Sentiment Analysis with Recurrent Neural Networks**
------
We implemented a recurrent neural network (LSTM) based on TensorFlow for the task of sentiment analysis on natural language data. Sentiment analysis refers to the natural language processing task of classifying some collection of the text by its polarity. We analyzed the data from Twitter ([Sentiment140 dataset](http://www.sentiment140.com/)) and try to classify it as either "positive" or "negative". The tweets can be viewed as sequences of words in natural language and form the sequantial input to the RNN model. The goal is to understand the attitude of the person that generates the text.

<div align="center">
<img src='/images/RNN.png'>
</div>
-->
