---
permalink: /
title: "Jinjin Tian"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. student in the Department of [Statistics & Data Science at Carnegie Mellon University](http://stat.cmu.edu). I am very fortunate to be advised by professor [Jing Lei](http://www.stat.cmu.edu/~jinglei/) and professor [Kathryn Roeder](http://www.stat.cmu.edu/~roeder/). We work on developing methodology and theory for high dimensional, nonparametric data analysis with a special focus on feature interaction and local structure. I have also extensively worked with professor [Aaditya Ramdas](http://www.stat.cmu.edu/~aramdas/) on online testing. Before coming to CMU, I obtained a Bacholor's degree in statistics from [School of Gifted Young](https://en.scgy.ustc.edu.cn/), [University of Science and Technology of China](http://en.ustc.edu.cn/) in 2018, where I worked with professor [Zemin Zheng](http://bs.ustc.edu.cn/english/Profile-302.html) in high-dimensional statistical inference.

Education
=======
* Ph.D. in Statistics, 2023 (expected)
: Carnegie Mellon University, Pittsburgh, USA

* B.S. in Statistics, 2018
: University of Science and Technology of China, Hefei

Work Experience
=======
* Applied Scientist Intern, 2020
: AWS, Amazon
: Built an online experimentation platform that allows efficient trading off between revenue constrain and time constrain in E-commerce while being able to deal with unknown abrupt changes over time.

Research Interests
=======
My research interests take root in unsupervised methods and theory for complex data analysis, with a special focus on nonlinearity and local structure. I have developed methods and theories mainly on

* Statistical gene networks
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

Publications and preprints
=======
* Contrasting the landscape of contrastive and non-contrastive learning. <small> (AISTATS 2022) [Paper](https://arxiv.org/pdf/2203.15702.pdf)  [Code](https://github.com/ashwinipokle/contrastive_landscape) </small>
: **Ashwini Pokle, Jinjin Tian, Yuchen Li, Andrej Risteski**
: Some recent works have shown promising results for non-contrastive learning, which does not require negative samples. However, the non-contrastive losses have obvious "collapsed" minima, in which the encoders output a constant feature embedding, independent of the input. A folk conjecture is that so long as these collapsed solutions are avoided, the produced feature representations should be good. In this project, we cast doubt on this story: we show through theoretical results and controlled experiments that even on simple data models, non-contrastive losses have a preponderance of non-collapsed bad minima. Moreover, we show that the training process does not avoid these minima.


* From local to global gene co-expression estimation using single-cell RNA-seq data. <small> (Submitted to AOAS) [Paper](https://arxiv.org/abs/2203.01990)  [Package](https://github.com/JINJINT/aLDG)</small>
: **Jinjin Tian, Jing Lei, Kathryn Roeder**
: In this paper, we explore a state-of-the-art network estimation technique that characterizes gene-gene association at the single cell level, under the name of cell-specific gene networks. We first show that averaging the cell-specific gene association over a population gives a novel univariate dependence measure that can detect any non-linear, non-monotone relationship. Together with a consistent nonparametric estimator, we establish its robustness on both the population and empirical levels. Simulations and real data analysis show that this measure outperforms existing independence measures like Pearson's, Kendall's $\tau$, $\tau^{\star}$, distance correlation, HSIC, Hoeffding's D, HHG, and MIC, for various tasks. 


* Large-scale simultaneous inference under dependence. <small>(Scandinavian Journal of Statistics 2022, minor revision submitted) [Paper](https://arxiv.org/abs/2102.11253)  [Package](https://github.com/annavesely/sumSome/) </small>
: **Jinjin Tian, Xu Chen, Eugene Katsevich, Jelle Goeman, Aaditya Ramdas**
: Simultaneous, post-hoc inference is desirable in large scale hypotheses testing as it allows people to explore the data while deciding on criteria for proclaiming discoveries. It was recently proved that all admissible post-hoc inference methods must be based on closed testing. In this paper we investigate closed testing with local tests that have a special property called separability, that is the test thresholds a function of a sum of test scores for the individual hypotheses. With separable local tests, we derive a class of novel, fast algorithms for various types of simultaneous inference. Paired with recent advances in separable global null tests, our work immediately instantiates a series of simultaneous inference methods that are sufficient to handle many complex dependence structures and signal compositions. 


* ESCO: single-cell expression simulation incorporating gene co-expression. <small> (Bioinformatics 2021) [Paper](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btab116/6149079?guestAccessKey=64c91aa4-1d5e-42da-92df-678b1b08af79)  [Package](https://github.com/JINJINT/ESCO)</small>
: **Jinjin Tian, Jiebiao Wang, Kathryn Roeder**
: Gene-gene co-expression networks (GCN) are of biological interest for the useful information they provide for understanding gene-gene interactions. In this project, we construct a new semiparametric scRNA-seq data simulation tool named ESCO, which ensembles current state of art in the first moment characterization, and fills in the gap of depicting higher-order gene-gene interaction using a copula model.


* Online experimentations in E-Commerce with revenue and time regulations. <small> (Amazon Machine Learning Conference, RL workshop 2020) </small>
: **Jinjin Tian, Lenon Minorics, Guido Imbens**
: Experimentation in E-commerce often has extra consideration of revenue constrain and time constrain. In this project, we utilize recent advances in reinforcement learning and any-time valid inference to construct an online experimentation platform that allows efficient trading off between revenue and time constraints. We also propose a new algorithm to deal with unknown abrupt changes over time, which only cost O(1) for each update and has much lower regret compared with other state-of-arts. This project happened during my internship with Amazon AWS.


* Online control of the familywise error rate. <small>(Statistical Methods in Medical Research 2021) [Paper](https://journals.sagepub.com/eprint/AYRRKZX7XMTVHKCFYBJY/full) [Code](https://github.com/JINJINT/onlineFWER) </small>
: **Jinjin Tian, Aaditya Ramdas**
: Biological research often involves testing a growing number of null hypotheses as new data is accumulated over time. We study the problem of online control of the familywise error rate (FWER), that is testing an apriori unbounded sequence of hypotheses one by one over time without knowing the future, such that with high probability, there are no false discoveries in the entire sequence. In this project, we unify algorithmic concepts developed for offline FWER control and online FDR control to develop a new powerful, adaptive online FWER control method. We also formally proved the substantial gains of power of the new methods and derived a closed-form of effective hyper-parameters for optimizing the power in a Gaussian sequence model.


* ADDIS: an adaptive discarding algorithm for online FDR control with conservative nulls. <small>(NeurIPS, 2019) [Paper](https://papers.nips.cc/paper/9136-addis-an-adaptive-discarding-algorithm-for-online-fdr-control-with-conservative-nulls.pdf) [Code](https://github.com/JINJINT/ADDIS)</small>
: **Jinjin Tian, Aaditya Ramdas**
: Major internet companies routinely perform tens of thousands of A/B tests each year, and rapid data collection is making the online testing of hypotheses increasingly essential. In this project, we proposed a new online FDR control algorithm called ADDIS that adapts to both signal proportion and conservative nulls and has wide validity: it works under either independence or local-dependence; synchrony or asynchrony. ADDIS outperforms the current state of arts in terms of robustness as well as power. 


Past Projects
=======
Some interesting projects I did in undergrad:

* Recovering  Graphical Structures with FDR control via Knockoffs. 
: **Jinjin Tian, Zemin Zheng**
: Constructed a new method for structure recovering in Gaussian graphical models with FDR control using knockoff filter. Extended the method to cases with additive measurement error using CoCoLasso.

* Brain task classification with Graph Neural Network guided by region connectivity.
: **Jinjin Tian, Jing Lei, Kehui Chen**
: Proposed graphical neural network models with regularization based on brain connectivity structures, which is shown to reduce over-fitting and improve accuracy in the classification of brains signals (MEG data).










