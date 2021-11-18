---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

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




<!-- 
**Twitter Sentiment Analysis with Recurrent Neural Networks**
------
We implemented a recurrent neural network (LSTM) based on TensorFlow for the task of sentiment analysis on natural language data. Sentiment analysis refers to the natural language processing task of classifying some collection of the text by its polarity. We analyzed the data from Twitter ([Sentiment140 dataset](http://www.sentiment140.com/)) and try to classify it as either "positive" or "negative". The tweets can be viewed as sequences of words in natural language and form the sequantial input to the RNN model. The goal is to understand the attitude of the person that generates the text.

<div align="center">
<img src='/images/RNN.png'>
</div>
-->
