---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---
 
**Few-shot parsing for biomedical texts** Sep 2022 – Feb 2023  
*supervised by Prof. [(Andrew McCallum)](https://people.cs.umass.edu/~mccallum/)*  

-Focus on few-shot constituency parsing. Work on knowledge distillation from GPT-3 to a smaller applicable language
model (i.e., T5).  
-Proposed a “usefulness” score to decide what exemplars to retrieve for prompts of GPT-3, which is proven more effective
than other methods on constituency parsing.  
-Proposed confident student training with knowledge distillation (ConST-KD). ConST-KD can reduce overconfident
mistakes in self-training due to noisy pseudo labels. With ConST-KD, the student model can outperform the teacher
model and other strong baselines in few-shot settings and reach comparable results to standard fine-tuning with ten times
more data.

