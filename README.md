<h1 align="center">APT-36K: A Large-scale Benchmark for Animal Pose Estimation and Tracking</h1>
<p align="center">
<a href="https://arxiv.org/abs/2206.05683"><img  src="https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg" ></a>

<h4 align="center">This is the official repository of the paper <a href="https://arxiv.org/abs/2206.05683">APT-36K: A Large-scale Benchmark for Animal Pose Estimation and Tracking</a>.</h4>
<h5 align="center"><em>Yuxiang Yang, Junjie Yang, Yufei Xu, Jing Zhang, Long Lan, Dacheng Tao</em></h5>

<p align="center">
  <a href="#introduction">Introduction</a> |
  <a href="#refmatte">RefMatte</a> |
  <a href="#results">Results</a> |
  <a href="#statement">Statement</a>
</p>



## Introduction
<p align="justify"><strong>Animal pose estimation and tracking (APT)</strong> is a fundamental task for detecting and tracking animal keypoints from a sequence of video frames. Previous animal-related datasets focus either on animal tracking or single-frame animal pose estimation, and never on both aspects. To fill this gap, we make the first step and propose <strong>APT-36K</strong>, i.e., the first large-scale benchmark for animal pose estimation and tracking. Specifically, APT-36K consists of 2,400 video clips collected and filtered from 30 animal species with 15 frames for each video, resulting in 36,000 frames in total. After manual annotation and careful double-check, high-quality keypoint and tracking annotations are provided for all the animal instances. Based on APT-36K, we benchmark several representative models on the following three tracks: (1) supervised animal pose estimation on a single frame under intra- and inter-domain transfer learning settings, (2) inter-species domain generalization test for unseen animals, and (3) animal pose estimation with animal tracking. Based on the experimental results, we gain some empirical insights and show that APT-36K provides a valuable animal pose estimation and tracking benchmark, offering new challenges and opportunities for future research.</p>




## Results
We show some examples of our test results on RefMatte test set and RefMatte-RW100 by our CLIPIMat given text inputs and the images under both prompt- and expression- based setting.

<img src="demo1.jpg" width="50%">
