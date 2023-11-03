---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:

- /about/
- /about.html

---
I am looking for PhD positions for 24 fall!  

I am currently a Master's student in Computer Science at UMass Amherst where I am lucky to be advised by Professor [Andrew McCallum](https://people.cs.umass.edu/~mccallum/) and Professor [Hong Yu](https://www.cics.umass.edu/faculty/directory/hong_yu). I finished my undergraduate study in Computer Science at HKUST in 2022. In the past, I was a research assistant at [SMART lab](https://hkustsmartlab.netlify.app/) working on medical image analysis with Professor [Hao Chen](https://cse.hkust.edu.hk/~jhc/) and an NLP research intern at [IDEA](https://www.idea.edu.cn/en/about-team.html).  

**Research Interests**. I am especially interested in label-efficient learning / weakly-supervised learning and improving the robustness and interpretability of neural networks. I am particularly enthusiastic about applying the implication to biology and medicine where labeled data are scarce and trustworthiness is valued. Correspondingly, I have worked on various tasks with diverse kinds of data involving texts, images and videos. I am also broadly interested in explainability,  multimodality, and neural science.  I am currently working on large language models with a special interest in memorization and generalization.

Apart from research, I am also interested in entrepreneurship which helps me consider my future research area. I took a minor in entrepreneurship at HKUST. My internship at the CTO lab of [IDEA](https://www.idea.edu.cn/en) was also about collaborating with a unicorn startup. In my spare time, I love photography and architecture. Check my instagram ([*zzzh_nick*](https://instagram.com/zzzh_nick?igshid=YmMyMTA2M2Y=)).  

## Publications  
### 2023  
- **Learning and Forgetting Unsafe Examples in Large Language Models**   
**_Jiachen Zhao_**, Zhun Deng, David Madras, James Zou, Mengye Ren\
Under review.  


- **Mist-KD: Multi-stage Knowledge Distillation from Large Language Models**\
**_Jiachen Zhao_**, Wenlong Zhao\*,  Andrew Drozdov\*，Benjamin Rozonoyer, Jay-Yoon Lee, Mohit Iyyer, Andrew McCallum\
In preparation.  
`[TL;DR]` *We investigate knowledge distillation from LLMs in low-data regimes. We find that the student model whose predictions have matched sufficient teacher labels during KD
can outperform the teacher on held-out data. We propose Mist-KD, a novel variant of knowledge distillation for few-shot settings. Empirically, students trained by Mist-KD achieve significant error
reduction compared to the teacher LLM, while being significantly faster.*

- **SELF-EXPLAIN: Teaching Large Language Models to Reason Complex Questions by Themselves**  
**_Jiachen Zhao_**, Zonghai Yao, Zhichao Yang, Hong Yu  
In preparation.  
Workshop on robustness of zero/few-shot learning in foundation models @ `NIPS 23`.  
`[TL;DR]` *Inspired by encoding specificity in humans' memory system, we find LLMs themselves can produce explanations of complex questions given an answer, which we refer to SELF-EXPLAIN. Prompting with self-explanation through in-context learning can make LLMs more confident and more calibrated as well. Prompting with self-explanation can even outperform prompting with human-crafted CoT on challenging knowledge-intensive reasoning tasks.*

- **Student as an Inherent Denoiser of Noisy Teacher**\
**_Jiachen Zhao_**\
3rd Workshop on Efficient Natural Language and Speech Processing @ `NIPS 23`.  
`[TL;DR]` *We provide new insights in the learning process of knowledge distillation (KD).
We unveil the inherent denoising effect in KD that at the early stage of KD,
the student model can generate better predictions than teacher labels used to train it.  We identify that this phenomenon can be attributed to the discrepancies in learning teacher labels.
Motivated by our findings, we propose peer-advised KD to optimize vanilla KD.  While this work focuses on parsing, a more comprehensive version that has validated the same findings across eight datasets covering different tasks is in preparation.*  


- **In-Context Exemplars as Clues to Retrieving from Large Associative Memory**\
**_Jiachen Zhao_**\
Neural Conversational AI @ `ICML 23`. Associative Memory & Hopfield Networks @ `NIPS 23`.  
[[code](https://github.com/andotalao24/ICL-as-retrieval-from-associative-memory)]  [[pdf](_data/_arxiv__ICL_as_retrieval.pdf)]   
`[TL;DR]` *We reinterpret In-Context Learning (ICL) of LLMs as contextual retrieval from associative memory motivated by the fact that no gradients update occurs in ICL and
analyze error bounds of retrieval errors. We relate ICL to humans' memory systems to show some phenomenon-level biological plausibility. We also discuss the implication of our theory to exemplar selection.*

### 2022   
- **Adaptive Fusion of Deep Learning with Statistical Anatomical Knowledge for Robust Patella Segmentation from CT Images**\
**_Jiachen Zhao_**, Tianshu Jiang, Yi Lin, Justin Chan, Ping-Keung Lewis Chan, Chunyi Wen, Hao Chen\
Under review, JBHI.  
[[code](https://github.com/andotalao24/PatellaSeg)] [[pdf](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4026021) to an early preprint version]  
`[TL;DR]` *Neural networks (NNs) for medical image segmentation are vulnerable to corrupted images and require sufficient labeled training data. To handle such issues, we propose to combine neural networks with statistical shape models (SSMs) and our method can automatically determine the contribution of NNs and SSMs during combination by leveraging proposed statistical methods.  Our approach can be attached to mainstream deep learning methods to improve the robustness and data efficiency.*

- **Trigger-free Event Detection via Derangement Reading Comprehension**\
**_Jiachen Zhao_**, Haiqin Yang\
arXiv.  
[[pdf](https://arxiv.org/pdf/2208.09659.pdf)]    
`[TL;DR]` *This work tries to improve the performance of event detection when human-labeled ``triggers'' are not available (the word in a sentence that is the most representative of the sentence and, thus very costly to annotate).  We reformulate this event classification problem into a multiple-choice QA task to better leverage self-attention. We also propose a token derangement module to tackle the imbalanced learning issue.  Our trigger-free method can reach SOTA performance and even outperform approaches relying on triggers.*






