---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---
 
**Few-shot parsing for biomedical texts** Sep 2022 – Current
*supervised by Prof. [Andrew McCallum](https://people.cs.umass.edu/~mccallum/)*  

-Focus on few-shot constituency parsing. Work on knowledge distillation from GPT-3 to a smaller applicable language
model (i.e., T5).  
-Proposed a “usefulness” score to decide what exemplars to retrieve for prompts of GPT-3, which is proven more effective
than other methods on constituency parsing.  
-Proposed confident student training with knowledge distillation (ConST-KD). ConST-KD can reduce overconfident
mistakes in self-training due to noisy pseudo labels. With ConST-KD, the student model can outperform the teacher
model and other strong baselines in few-shot settings and reach comparable results to standard fine-tuning with ten times
more data.

**Deep learning in time series forecasting for epidemics** Dec 2021 – May 2022  
*Final year project, supervised by Prof. [Dit-Yan YEUNG](https://sites.google.com/view/dyyeung)*  

-Worked on zero-shot and few-shot time series prediction to forecast the spread of a local pandemic at its early stage.
Designed and built a meta-learning framework for time-series to leverage history data across regions to tackle the scarcity
of data.  

**Patella segmentation for the early detection of osteoarthritis** June 2021 – October 2021  
*Supervised by Prof. [Hao Chen](https://cse.hkust.edu.hk/~jhc/)*  

-Worked independently on increasing the robustness and data-efficiency of Convolutional Neural Networks (CNN) by
leveraging Statistical Shape Model (SSM) for Patella segmentation.  
-Implemented automated sampling and image registration to generate SSM. Proposed a metric for predicting whether
CNN or SSM performs better with no access to ground truth. Proposed a fuzzy nearest-neighbor framework to integrate
prior anatomical knowledge into CNN-based segmentation. It can improve the robustness and accuracy of segmentation
in the case of limited or corrupted data.  
-The proposal can increase the Dice coefficient of various mainstream CNN frameworks by around 1.7% on blind tests.
The tested models can achieve a much better performance when only half of the training data are given.  

**Implicit discourse relation classification** February 2021 – May 2021  
*Supervised by Prof. [Yangqiu Song](https://www.cse.ust.hk/~yqsong/)*  

-Applied BERT to the classification of implicit discourse relations. Proposed to focus on the long-tail recognition to
improve the classification performance.  
-Experimented with various methods including data augmentation, loss function modification (e.g., Focal Loss), transfer
learning and multi-task learning to improve the performance on minority class. The F1 score of the base model can be at
best increased by 2.1%.  

**Video analysis for the management of crowds** April 2020 – August 2020  
*Supervised by Prof. [Shueng-Han Gary Chan](https://www.cse.ust.hk/~gchan/)*  

-Applied YOLO and deepSORT to realize real-time indoor crowds detection and tracking on a single camera. Developed
algorithms to analyze indoor crowds’ staying time and monitor social distancing.  
-Further developed a naive framework on multi-camera multi-target tracking, which was an open research topic by then.  
