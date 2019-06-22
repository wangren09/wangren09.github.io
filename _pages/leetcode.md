---
permalink: /leetcode/
layout: archive
title: "LeetCode"
author_profile: true
---

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
