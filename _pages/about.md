---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:

- /about/
- /about.html

---
Update: I am a scholar in the [MATS](https://www.matsprogram.org/) program this summer, working on reasoning at Prof. [Dawn Song](https://dawnsong.io/)'s Lab. 

I am a PhD student at Northeastern University. I am advised by Prof. [Weiyan Shi](https://wyshi.github.io/) and working closely with Prof. [David Bau](https://baulab.info/). I obtained my Master's degree in Computer Science at UMass Amherst where I was lucky to be advised by Prof. [Andrew McCallum](https://people.cs.umass.edu/~mccallum/) and Prof. [Hong Yu](https://www.cics.umass.edu/faculty/directory/hong_yu). I finished my undergraduate study in Computer Science at HKUST, where I was a research assistant at [SMART lab](https://hkustsmartlab.netlify.app/) working on medical image analysis with Professor [Hao Chen](https://cse.hkust.edu.hk/~jhc/) and an NLP research intern at [IDEA](https://www.idea.edu.cn/en/about-team.html).  

**Research Interests**. I am especially interested in label-efficient learning / weakly-supervised learning and improving the robustness and interpretability of neural networks. I am particularly enthusiastic about applying the implication to biology and medicine where labeled data are scarce and trustworthiness is valued.  

I currently work on large language models, especially safety alignment and interpretation. I also have experience of knowledge distillation from LLMs and reasoning.



## Publications  
### 2025  
- **LLMs Encode Harmfulness and Refusal Separately**  
**_Jiachen Zhao_**, Jing Huang, Zhengxuan Wu, David Bau, Weiyan Shi  
Preprint.  
[[pdf](https://arxiv.org/abs/2507.11878)]  

### 2024  
- **Large Language Models are In-context Teachers for Knowledge Reasoning**  
**_Jiachen Zhao_**, Zonghai Yao, Zhichao Yang, Hong Yu  
EMNLP 24 Findings.  
[[pdf](https://arxiv.org/pdf/2311.06985v2)]
  
- **Learning and Forgetting Unsafe Examples in Large Language Models**   
**_Jiachen Zhao_**, Zhun Deng, David Madras, James Zou, Mengye Ren\
ICML 24.  
[[pdf](https://arxiv.org/pdf/2312.12736.pdf)]


- **Multistage Collaborative Knowledge Distillation from a Large Language Model for Semi-Supervised Sequence Generation**\
**_Jiachen Zhao_**, Wenlong Zhao\*,  Andrew Drozdov\*, Benjamin Rozonoyer, Md Arafat Sultan, Jay-Yoon Lee, Mohit Iyyer, Andrew McCallum\
ACL 24.      
[[pdf](https://arxiv.org/pdf/2311.08640.pdf)]  
<!--`[TL;DR]` *We study a challenging scenario where labeled data are too few to finetune a model and few-shot prompted LLMs also have suboptimal performance.  We find that a student model that has memorized sufficient teacher labels during knowledge distillation can outperform the teacher model on held-out data by correcting teacher's mistakes instead of repeating them.  We then propose Multistage Collaborative Knowledge Distillation (MCKD). On challenging biomedical parsing, 3-stage MCKD with 50 labeled examples matches the performance of supervised finetuning with 500 examples and outperforms the prompted LLM and vanilla KD by 7.5% and 3.7% parsing F1, respectively.*-->

- **Adaptive Fusion of Deep Learning with Statistical Anatomical Knowledge for Robust Patella Segmentation from CT Images**\
**_Jiachen Zhao_**, Tianshu Jiang, Yi Lin, Justin Chan, Ping-Keung Lewis Chan, Chunyi Wen, Hao Chen\
Journal of Biomedical & Health Informatics.  
[[code](https://github.com/andotalao24/PatellaSeg)] [[pdf](https://ieeexplore.ieee.org/abstract/document/10461000)]  
<!--`[TL;DR]` *Neural networks (NNs) for medical image segmentation are vulnerable to corrupted images and require sufficient labeled training data. To handle such issues, we propose to combine neural networks with statistical shape models (SSMs) and our method can automatically determine the contribution of NNs and SSMs during combination by leveraging proposed statistical methods.  Our approach can be attached to mainstream deep learning methods to improve the robustness and data efficiency.*-->

### 2023  
- **SELF-EXPLAIN: Teaching Large Language Models to Reason Complex Questions by Themselves**  
**_Jiachen Zhao_**, Zonghai Yao, Zhichao Yang, Hong Yu  
Workshop on robustness of zero/few-shot learning in foundation models @ `NIPS 23`.  
[[pdf](https://arxiv.org/pdf/2311.06985v1)]  
<!--`[TL;DR]` *It remains unclear the principles to craft Chain-of-Thought examples for few-shot prompting. The style and expression of in-context exemplars can influence the prompting performance. Inspired by encoding specificity in humans' memory systems, we propose SELF-EXPLAIN to elicit LLMs' explanations of complex questions by themselves. Prompting with self-explanations through in-context learning can make LLMs more confident and more calibrated as well. Prompting with self-explanation can even outperform prompting with human-crafted CoT on reasoning tasks in both medical and general domains.*-->

- **Student as an Inherent Denoiser of Noisy Teacher**\
**_Jiachen Zhao_**\
3rd Workshop on Efficient Natural Language and Speech Processing @ `NIPS 23`.   
[[pdf](https://andotalao24.github.io/files/nips23__efficient_nlp_workshop.pdf)]   
<!--`[TL;DR]` *We provide new insights into the learning process of knowledge distillation (KD).
We unveil the inherent denoising effect in KD that at the early stage of KD,
the student model can generate better predictions than teacher labels used to train it.  We identify that this phenomenon can be attributed to the discrepancies in learning teacher labels. Motivated by our findings, we propose peer-advised KD to optimize vanilla KD.  While this work focuses on parsing, a more comprehensive version covering different tasks is in preparation.*  -->


- **In-Context Exemplars as Clues to Retrieving from Large Associative Memory**\
**_Jiachen Zhao_**\
Neural Conversational AI @ `ICML 23`. Associative Memory & Hopfield Networks @ `NIPS 23`.  
 [[pdf](https://arxiv.org/pdf/2311.03498.pdf)]     
<!--`[TL;DR]` *We reinterpret In-Context Learning (ICL) of LLMs as contextual retrieval from associative memory motivated by the fact that no gradients update occurs in ICL and
analyze error bounds of retrieval errors. We relate ICL to humans' memory systems to show some phenomenon-level biological plausibility. We also discuss the implication of our theory to exemplar selection.*-->

### 2022   
- **Trigger-free Event Detection via Derangement Reading Comprehension**\
**_Jiachen Zhao_**, Haiqin Yang\
arXiv.  
[[pdf](https://arxiv.org/pdf/2208.09659.pdf)]    
<!--`[TL;DR]` *This work tries to improve the performance of event detection when human-labeled ``triggers'' are not available (the word in a sentence that is the most representative of the sentence and, thus very costly to annotate).  We reformulate this event classification problem into a multiple-choice QA task to better leverage self-attention. We also propose a token derangement module to tackle the imbalanced learning issue.  Our trigger-free method can reach SOTA performance and even outperform approaches relying on triggers.*-->


## Academic service  
Reviewer for ICML, Neurips, CoNLL



