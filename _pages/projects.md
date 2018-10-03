---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

**DyNet: The Dynamic Neural Network Toolkit**
------
[DyNet](https://github.com/clab/dynet) is a neural network library developed by Carnegie Mellon University, Petuum, and many others. It is written in C++ (with bindings in Python) and is designed to be efficient when run on either CPU or GPU, and to work well with networks that have dynamic structures that change for every training instance. I constantly contribute to this open sourced project.

<div  align="center">
<img src='/images/dynet_logo_bg.png'>
</div>
 
**IBM Watson Build Challenge 2017**
------
We developed a web application with IBM Watson APIs (Retrieve and Rank) based on IBM Bluemix and implemented multiple missing data recovery and event identification algorithms by Python for large scale Phasor Measurement Unit (PMU) data analysis.

<div  align="center">
<img src='/images/Watson.png' width='500' height='300'>
</div>

**Online Algorithm for PMU Data Processing (OLAP)**
------
We implemented OLAP by C# based on Project Alpha for the real-time application. Project Alpha is elite version of Open PDC. It provides a jump start to developing new products based on the Grid Solutions Framework's Time-Series Library (TSL) technology complete with all needed components for standalone time-series processing application. The code developed on Project Alpha can be run on Open PDC as action adapter.

<div  align="center">
<img src='/images/OLAP.png' width='720' height='200'>
</div>

Publication: Pengzhi Gao, Meng Wang, Scott G. Ghiocel, Joe H. Chow, Bruce Fardanesh, and George Stefopoulos. Missing Data Recovery by Exploiting Low-dimensionality in Power Systems Synchrophasor Measurements. IEEE Trans. Power Systems, 2016, 31 (2): 1006-1013.

Patent: Meng Wang, Pengzhi Gao, and Joe H. Chow. "A low-rank-based missing PMU data recovery method." Application No.: 62/445305, Filed January 12, 2017.

[Demo is available!](https://www.youtube.com/watch?v=vHiUh4NLQgo)


**Mobile Eye Gaze Estimation with Deep Learning**
------
We implemented a deep convolutional neural network based on TensorFlow for eye gaze estimation. In this project, we focus on mobile eye gaze estimation, which is to predict the gaze position on the phone/tablet screen. The original dataset comes from the [GazeCapture project](http://gazecapture.csail.mit.edu/). Due to the limitation of the computing power, we trained our model on a much smaller dataset with 48000 trainning samples and 5000 validation samples. Each sample contains 5 items: face (64 X 64 X 3), left eye (64 X 64 X 3), right eye (64 X 64 X 3), face mask (25 X 25 X 1) and labels (x,y). Our model follows the architecture introduced in [R1], and we changed and tuned the hyper parameters (listed below) due to the different image size in our trainning dataset.

<br/><img src='/images/GazeCapture.png'> 

| Layer Name | Type          | Kernel Size | Stride | Padding | Output Size  |
| --------   | ------------- | ----------- | ------ | ------- | ------------ |
| conv1      | Convolutional |  5 X 5      |   2    |  SAME   | 64 @ 32 X 32 |
| pool1      | Max Pooling   |  2 X 2      |   2    |  VALID  | 64 @ 16 X 16 |
| conv2      | Convolutional |  5 X 5      |   1    |  SAME   | 64 @ 16 X 16 |
| pool2      | Max Pooling   |  2 X 2      |   2    |  VALID  | 64 @ 8 X 8   |
| conv3      | Convolutional |  3 X 3      |   1    |  SAME   | 128 @ 8 X 8  |
| pool3      | Max Pooling   |  2 X 2      |   2    |  VALID  | 128 @ 4 X 4  |
| conv4      | Convolutional |  1 X 1      |   1    |  SAME   | 64 @ 4 X 4   |
| pool4      | Max Pooling   |  2 X 2      |   2    |  VALID  | 64 @ 2 X 2   |
| eye_fc     | Fully Connected |           |        |         | 128          |
| face_fc1   | Fully Connected |           |        |         | 128          |
| face_fc2   | Fully Connected |           |        |         | 64           |
| facegrid_fc1   | Fully Connected |           |        |         | 256      |
| facegrid_fc2   | Fully Connected |           |        |         | 128      |
| fc1   | Fully Connected |           |        |         | 128      |
| fc2   | Fully Connected |           |        |         | 2        |

[R1] K.Krafka, A. Khosla, P. Kellnhofer, H. Kannan, S. Bhandarkar, W. Matusik, and A. Torralba. Eye Tracking for Everyone. IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016.

<!-- 
**Twitter Sentiment Analysis with Recurrent Neural Networks**
------
We implemented a recurrent neural network (LSTM) based on TensorFlow for the task of sentiment analysis on natural language data. Sentiment analysis refers to the natural language processing task of classifying some collection of the text by its polarity. We analyzed the data from Twitter ([Sentiment140 dataset](http://www.sentiment140.com/)) and try to classify it as either "positive" or "negative". The tweets can be viewed as sequences of words in natural language and form the sequantial input to the RNN model. The goal is to understand the attitude of the person that generates the text.

<div align="center">
<img src='/images/RNN.png'>
</div>
-->
