---
permalink: /
title: "Jinjin Tian"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I just graduated with a doctorate from the joint program between the [Department of Statistics & Data Science](http://stat.cmu.edu) and the [Machine Learning Department](https://www.ml.cmu.edu/) at Carnegie Mellon University. I am very fortunate to be advised by professor [Jing Lei](http://www.stat.cmu.edu/~jinglei/) and professor [Kathryn Roeder](http://www.stat.cmu.edu/~roeder/). We worked on developing methodology and theory for high dimensional, nonparametric data analysis with a special focus on feature interaction and local structure. I have also extensively worked with professor [Aaditya Ramdas](http://www.stat.cmu.edu/~aramdas/) on online testing. Before coming to CMU, I obtained a Bacholor's degree in statistics from [School of Gifted Young](https://en.scgy.ustc.edu.cn/), [University of Science and Technology of China](http://en.ustc.edu.cn/) in 2018, where I worked with professor [Zemin Zheng](http://bs.ustc.edu.cn/english/Profile-302.html) in high-dimensional statistical inference.

Education
=======
* Ph.D. in Statistics and Machine Learning, 2018-2023
: Carnegie Mellon University, Pittsburgh, USA

* M.S. in Machine Learning, 2021-2022
: Carnegie Mellon University, Pittsburgh, USA

* B.S. in Statistics, 2014-2018
: University of Science and Technology of China, Hefei, China

Work Experience
=======
* Applied Scientist II, Now
: Search, Amazon
: Working on query recommendation for Amazon Search. 

* Applied Scientist Intern, 2022
: Alexa AI, Amazon
: Constructed a two-stage confident learning framework for label de-nosing in NLU, which has more effectiveness as well as efficiency. 

* Applied Scientist Intern, 2020
: AWS, Amazon
: Built an online experimentation platform that allows efficient trading off between revenue constrain and time constrain in E-commerce while being able to deal with unknown abrupt changes over time.

Research Interests
=======
My research interests take root in unsupervised methods and theory for complex data analysis, with a special focus on nonlinearity and local structure. I have developed methods and theories mainly on

* Statistical networks
* Robust and efficient NLP
* Self-supervised learning, representation learning
* Selective inference

<!--
Ongoing Research Projects
=======

* Signals recovery in noisy high-dim mixture via local structure learning. 
: **Jinjin Tian, Jing Lei, Kathryn Roeder**
: In this project we work on nonparametric methods of recovering signals using local structure in a high dimensional mixture model when the noises are enormous and signals are weak and sparse. We propose a statistics to capture local structure between a pair of features, which will only dominate iff the corresponding sample comes from a non-noise mixture component, in which the feature pairs are both relevant features.  
We have proved exact recovery of signals in a single non-noise mixture setting using a nonparametric estimation, under even impossible scenarios for canonical methods like sparse PCA. We are working on proofs for multiple non-noise mixture cases. 

-->

Working papers
=======

* Identifying active differentially expressed gene modules for Autism
: **Jinjin Tian, Maya Shen, Kathryn Roeder, Bernie Devlin**

* Controlling False Discovery Proportions under Dependence with the Harmonic Mean P-value
: **Xu Chen, Jinjin Tian, Aaditya Ramdas, Eugene Katsevich, Jelle Goeman**

Publications and preprints
=======
* LCA-on-the-Line: Benchmarking Out-of-Distribution Generalization with Class Taxonomies
: **NeurIPS 2023 Workshop on Distribution Shifts [Paper](https://openreview.net/forum?id=7CUutNeDDg)**
: (Jia Shi, Gautam Rajendrakumar Gare, Jinjin Tian, Siqi Chai, Zhiqiu Lin, Arun Balajee Vasudevan, Di Feng, Francesco Ferroni, Shu Kong, Deva Ramanan)
: We introduce `Least Common Ancestor (LCA)-on-the-line' as a method for predicting models' Out-of-Distribution (OOD) performance using in-distribution measurements, without the need for OOD data. Our evaluation of 75 models across five significantly shifted ImageNet-OOD datasets demonstrates the robustness of LCA-on-the-line. It reveals a strong linear correlation between in-domain ImageNet LCA distance and OOD Top-1 accuracy across various datasets, including ImageNet-S/R/A/ObjectNet. Compared to previous methods such as Accuracy-on-the-line and Agreement-on-the-line, LCA-on-the-line shows superior generalization across a wide range of models. In addition to presenting an OOD performance indicator, we also demonstrate that aligning model predictions more closely with the class hierarchy and integrating a training loss objective with soft-labels can enhance model OOD performance.

* UseClean: learning from complex noisy labels in named entity recognition. 
: **Learning with Small Dataset 2023 [Paper](https://aclanthology.org/2023.clasp-1.14/) [Package](https://github.com/JINJINT/UseClean)**
: (Jinjin Tian, Kun Zhou, Meiguo Wang, Yu Zhang, Benjamin Yao, Xiaohu Liu and Chenlei Guo)
: We investigate and refine denoising methods for NER task on data that potentially contains extremely noisy labels from multi-sources. In this paper, we first summarized all possible noise types and noise generation schemes, based on which we built a thorough evaluation system. We then pinpoint the bottleneck of current state-of-art denoising methods using our evaluation system. Correspondingly, we propose several refinements, including using a two-stage framework to avoid error accumulation; a novel confidence score utilizing minimal clean supervision to increase predictive power; an automatic cutoff fitting to save extensive hyper-parameter tuning; a warm started weighted partial CRF to better learn on the noisy tokens. Additionally, we propose to use adaptive sampling to further boost the performance in long-tailed entity settings. Our method improves F1 score by on average at least $ 5\sim10\% $ over current state-of-art across extensive experiments.

* Contrasting the landscape of contrastive and non-contrastive learning. 
: **AISTATS 2022 [Paper](https://arxiv.org/pdf/2203.15702.pdf)  [Code](https://github.com/ashwinipokle/contrastive_landscape)**
: (Ashwini Pokle, Jinjin Tian, Yuchen Li, Andrej Ristesk)
: Some recent works have shown promising results for non-contrastive learning, which does not require negative samples. However, the non-contrastive losses have obvious "collapsed" minima, in which the encoders output a constant feature embedding, independent of the input. A folk conjecture is that so long as these collapsed solutions are avoided, the produced feature representations should be good. In this project, we cast doubt on this story: we show through theoretical results and controlled experiments that even on simple data models, non-contrastive losses have a preponderance of non-collapsed bad minima. Moreover, we show that the training process does not avoid these minima.

* Large-scale simultaneous inference under dependence. 
: **Scandinavian Journal of Statistics 2022 [Paper](https://arxiv.org/abs/2102.11253)  [Package](https://github.com/annavesely/sumSome/)**
: (Jinjin Tian, Xu Chen, Eugene Katsevich, Jelle Goeman, Aaditya Ramdas)
: Simultaneous, post-hoc inference is desirable in large scale hypotheses testing as it allows people to explore the data while deciding on criteria for proclaiming discoveries. It was recently proved that all admissible post-hoc inference methods must be based on closed testing. In this paper we investigate closed testing with local tests that have a special property called separability, that is the test thresholds a function of a sum of test scores for the individual hypotheses. With separable local tests, we derive a class of novel, fast algorithms for various types of simultaneous inference. Paired with recent advances in separable global null tests, our work immediately instantiates a series of simultaneous inference methods that are sufficient to handle many complex dependence structures and signal compositions. 

* Online experimentations in E-Commerce with revenue and time regulations. 
: **Amazon Machine Learning Conference, RL workshop 2020**
: (Jinjin Tian, Lenon Minorics, Guido Imbens)
: Experimentation in E-commerce often has extra consideration of revenue constrain and time constrain. In this project, we utilize recent advances in reinforcement learning and any-time valid inference to construct an online experimentation platform that allows efficient trading off between revenue and time constraints. We also propose a new algorithm to deal with unknown abrupt changes over time, which only cost O(1) for each update and has much lower regret compared with other state-of-arts. This project happened during my internship with Amazon AWS.

* Online control of the familywise error rate. 
: **Statistical Methods in Medical Research 2021 [Paper](https://journals.sagepub.com/eprint/AYRRKZX7XMTVHKCFYBJY/full) [Code](https://github.com/JINJINT/onlineFWER)**
: (Jinjin Tian, Aaditya Ramdas)
: Biological research often involves testing a growing number of null hypotheses as new data is accumulated over time. We study the problem of online control of the familywise error rate (FWER), that is testing an apriori unbounded sequence of hypotheses one by one over time without knowing the future, such that with high probability, there are no false discoveries in the entire sequence. In this project, we unify algorithmic concepts developed for offline FWER control and online FDR control to develop a new powerful, adaptive online FWER control method. We also formally proved the substantial gains of power of the new methods and derived a closed-form of effective hyper-parameters for optimizing the power in a Gaussian sequence model.

* ADDIS: an adaptive discarding algorithm for online FDR control with conservative nulls.
: **NeurIPS, 2019 [Paper](https://papers.nips.cc/paper/9136-addis-an-adaptive-discarding-algorithm-for-online-fdr-control-with-conservative-nulls.pdf) [Code](https://github.com/JINJINT/ADDIS)**
: (Jinjin Tian, Aaditya Ramdas)
: Major internet companies routinely perform tens of thousands of A/B tests each year, and rapid data collection is making the online testing of hypotheses increasingly essential. In this project, we proposed a new online FDR control algorithm called ADDIS that adapts to both signal proportion and conservative nulls and has wide validity: it works under either independence or local-dependence; synchrony or asynchrony. ADDIS outperforms the current state of arts in terms of robustness as well as power. 

* From local to global gene co-expression estimation using single-cell RNA-seq data. 
: **Biometrics 2024 [Paper](https://arxiv.org/abs/2203.01990)  [Package](https://github.com/JINJINT/aLDG)**
: (Jinjin Tian, Jing Lei, Kathryn Roeder)
: In this paper, we explore a state-of-the-art network estimation technique that characterizes gene-gene association at the single cell level, under the name of cell-specific gene networks. We first show that averaging the cell-specific gene association over a population gives a novel univariate dependence measure that can detect any non-linear, non-monotone relationship. Together with a consistent nonparametric estimator, we establish its robustness on both the population and empirical levels. Simulations and real data analysis show that this measure outperforms existing independence measures like Pearson's, Kendall's $\tau$, $\tau^{\star}$, distance correlation, HSIC, Hoeffding's D, HHG, and MIC, for various tasks. 

* ESCO: single-cell expression simulation incorporating gene co-expression. 
: **Bioinformatics 2021 [Paper](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btab116/6149079?guestAccessKey=64c91aa4-1d5e-42da-92df-678b1b08af79)  [Package](https://github.com/JINJINT/ESCO)**
: (Jinjin Tian, Jiebiao Wang, Kathryn Roeder)
: Gene-gene co-expression networks (GCN) are of biological interest for the useful information they provide for understanding gene-gene interactions. In this project, we construct a new semiparametric scRNA-seq data simulation tool named ESCO, which ensembles current state of art in the first moment characterization, and fills in the gap of depicting higher-order gene-gene interaction using a copula model.







