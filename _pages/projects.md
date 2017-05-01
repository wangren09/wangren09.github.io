---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

**Online Algorithm for PMU Data Processing (OLAP)**
------
We implemented OLAP by C# based on Project Alpha for the real-time application. Project Alpha is elite version of Open PDC. It provides a jump start to developing new products based on the Grid Solutions Framework's Time-Series Library (TSL) technology complete with all needed components for standalone time-series processing application. The code developed on Project Alpha can be run on Open PDC as action adapter.

<br/><img src='/images/OLAP.png'>

Publication: Pengzhi Gao, Meng Wang, Scott G. Ghiocel, Joe H. Chow, Bruce Fardanesh, and George Stefopoulos. Missing Data Recovery by Exploiting Low-dimensionality in Power Systems Synchrophasor Measurements. IEEE Trans. Power Systems, 2016, 31 (2): 1006-1013.

Patent: Patent: Meng Wang, Pengzhi Gao, and Joe H. Chow. "A low-rank-based missing PMU data recovery method." Application No.: 62/445305, Filed January 12, 2017.

[Demo is available!](https://www.youtube.com/watch?v=vHiUh4NLQgo)


**Class Project: Mobile Eye Gaze Estimation with Deep Learning**
------
We implemented a deep convolutional neural network by Python based on TensorFlow for eye gaze estimation. In this project, we focus on mobile eye gaze estimation, which is to predict the gaze position on the phone/tablet screen. The original dataset comes from the [GazeCapture project](http://gazecapture.csail.mit.edu/). Due to the limitation of the computing power, we trained our model on a much smaller dataset with 48000 trainning samples and 5000 validation samples. Each sample contains 5 items: face (64X64X3), left eye (64X64X3), right eye (64X64X3), face mask (25X25X1) and labels (x,y). Our model follows the architecture introduce in [R1], and we changed some hyper parameters due to the different image size in our trainning dataset.

<br\><img src='/images/'>
