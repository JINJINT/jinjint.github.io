---
permalink: /
title: "Jinjin Tian"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. student in the Department of [Statistics & Data Science at Carnegie Mellon University](http://stat.cmu.edu). I am very fortunate to be advised by professor [Jing Lei](http://www.stat.cmu.edu/~jinglei/) and professor [Kathryn Roeder](http://www.stat.cmu.edu/~roeder/). We work on developing statistical and machine learning methodology and theory for high dimensional, non-parametric data analysis with special focus on feature dependency. I have also extensively worked with professor [Aaditya Ramdas](http://www.stat.cmu.edu/~aramdas/) on high-dimensional testing. Before coming to CMU, I obtained a Bacholor degree in statistics from the Special Class for the Gifted Young [SCGY](http://en.scgy.ustc.edu.cn/), [USTC](http://en.ustc.edu.cn/) in 2018, where I worked with professor [Zemin Zheng](http://bs.ustc.edu.cn/english/Profile-302.html) in high-dimensional statistical inference.

Here is my [Curriculum Vitae](https://jinjint.github.io/files/cv.pdf).


Education
=======
* Ph.D. in Statistics, 2023 (expected)
: Carnegie Mellon University, Pittsburgh, USA

* B.S. in Statistics, 2018
: University of Science and Technology of China, Hefei

* Applied Scientist Intern, 2020
: AWS, Amazon


Research Interests
======
My research interests take root in methods and theory for high dimensional, nonparametric data analysis with special focus on the interaction structure and temporal nature, specifically includes

* High-dimensional Nonparametric inference

* Graphical structure recovery

* Statistical genetics

* Reinforcement Learning


Ongoing Research Projects
=======

* Non-parametric co-clustering of noisy high-dimensional mixture data based on pairwise local dependency. 
: **Jinjin Tian, Jing Lei, Kathryn Roeder**
: In this project we study the problem of clustering samples and features simulatenously in high-dimensional setting using non-parametric methods, together with inference on the dependency among features. 


* Large-scale simultaneous inference under dependence. 
: **Jinjin Tian, Xu Chen, Eugene Katsevich, Jelle Goeman, Aaditya Ramdas**
: Simultaneous, post-hoc inference is desirable in large scale hypotheses testing as it allows people to explore the data while deciding on criteria for proclaiming discoveries. It was recently proved that all admissible post-hoc inference methods must be based on closed testing. In this paper we investigate closed testing with local tests that have a special property called separability, that is the test thresholds a function of a sum of test scores for the individual hypotheses. With separable local tests, we derive a class of novel, fast algorithms forvarious types of simultaneous inference. Paired with recent advances in separable global null tests, our work immediately instantiates a series of simultaneous inference methods that are sufficient to handle many complex dependence structures and signal compositions. This work is close to be submitted.


Publications and Preprints
=======

* ESCO: single cell expression simulation incorporating gene co-expression. <small> (Bioinformatics, minor revision) [Paper](https://www.biorxiv.org/content/10.1101/2020.10.20.347211v1)  [package](https://github.com/JINJINT/ESCO)</small>
: **Jinjin Tian, Jiebiao Wang, Kathryn Roeder**
: Gene-gene co-expression networks (GCN) are of biological interest for the useful information they provide for understanding gene-gene interactions. In this project, we constructed a new semiparametric scRNA-seq data simulation tool named ESCO, which ensembles current state of art in the first moment characterization, and fills in the gap of depicting higher order gene-gene interaction using a copula model.


* Online experimentation in E-commerce with revenue and time constraints. <small>(ALMC, RL workship 2020)  [package](https://github.com/JINJINT/) </small>
: **Jinjin Tian, Lenon Minorics, Guido Imbens**
: Experimentation in E-commerce often have extra consideration of revenue constrain and time constrain. In this project we utilized recent advances in reinforcement learning and any-time valid inference to construct an online experimentation platform that allows efficient trading off between revenue constrain and time constrain in E-commerce. We also proposed new algorithm to deal with unknown abrupt changes over time, which only cost O(1) for each updates, and has much lower regret comparing with other state-of-arts.  


* Online control of the familywise error rate. <small>(SMMR) [Paper](https://journals.sagepub.com/eprint/AYRRKZX7XMTVHKCFYBJY/full)  [code](https://github.com/JINJINT/onlineFWER) </small>
: **Jinjin Tian, Aaditya Ramdas**
: Biological research often involves testing a growing number of null hypotheses as new data is accumulated over time. We study the problem of online control of the familywise error rate (FWER), that is testing an apriori unbounded sequence of hypotheses (p-values) one by one over time without knowing the future, such that with high probability there are no false discoveries in the entire sequence. In this project we unified algorithmic concepts developed for offline FWER control and online FDR control to develop new powerful, adaptive online FWER control method. We also formally proved the substantial gains of power of the new methods, and derived closed form of effective hyper-parameters for optimizing the power in a Gaussian sequence model.


* ADDIS: an adaptive discarding algorithm for online FDR control with conservative nulls. <small>(NeurIPS, 2019) [Paper](https://papers.nips.cc/paper/9136-addis-an-adaptive-discarding-algorithm-for-online-fdr-control-with-conservative-nulls.pdf) [code](https://github.com/JINJINT/ADDIS)</small>
: **Jinjin Tian, Aaditya Ramdas**
: Major internet companies routinely perform tens of thousands of A/B tests each year, and rapid data collection is making the online testing of hypotheses increasingly essential. In this project we proposed a new online FDR control algorithm called ADDIS that adapts to both signal proportion and conservative nulls and has wide validity: works under either independence or local-dependence; synchrony or asynchrony. ADDIS outperforms current state of arts in terms of robustness as well as power. 


Past Projects
=======
Some interesting projects I did in undergrad:

* Recovering  Graphical Structures with FDR control via Knockoffs. 
: **Jinjin Tian, Zemin Zheng**
: Constructed new method for structure recovering in Gaussian graphical models with FDR control using knockoff filter. Extended the method to cases with additive measurement error using CoCoLasso.

* Brain task classification with Graph Neural Network guided by region connectivity.
: **Jinjin Tian, Jing Lei, Kehui Chen**
: Proposed graphical neural network models with regularization based on brain connectivity structures, which is shown to reduce over-fitting and improve accuracy in classification of  brains signals (MEG data).











