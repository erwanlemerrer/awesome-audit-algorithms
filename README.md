# Awesome Audit Algorithms [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of algorithms for auditing black-box algorithms.
Nowadays, many algorithms (recommendation, scoring, classification, ...) are operated at third party providers, without users or institutions having any insights on how they operate on their data. Audit algorithms in this list thus apply to this setup, coined the "black-box" setup, where one auditor wants to get some insight on these remote algorithms.

<img src="https://github.com/erwanlemerrer/awesome-audit-algorithms/blob/main/resources/audit.png" width="600" alt="banner" class="center">

> A user queries a remote algorithm (eg, through available APIs), to infer information about that algorithm.

## Contents
- [Papers](#papers)

## Papers
### 2021
- [Setting the Record Straighter on Shadow Banning](https://arxiv.org/abs/2012.05101) (INFOCOM)  [(Code)](https://gitlab.enseeiht.fr/bmorgan/infocom-2021)
- [FairLens: Auditing black-box clinical decision support systems](https://www.sciencedirect.com/science/article/pii/S030645732100145X?casa_token=oyjFKij269MAAAAA:w_ohScpMPNMnkDdzBqAIod5QfBgQlq5Ht9mMRSOydZpOgNG-i1yuqEmBjWN__38gOGmjNL7dVT0) (Information Processing & Management)   
### 2020
- [Adversarial Model Extraction on Graph Neural Networks](https://arxiv.org/abs/1912.07721) (AAAI Workshop on Deep Learning on Graphs: Methodologies and Applications)   
- [Remote Explainability faces the bouncer problem](https://rdcu.be/b6qB4) (Nature Machine Intelligence volume 2, pages529–539)  [(Code)](https://github.com/erwanlemerrer/bouncer_problem)
- [GeoDA: a geometric framework for black-box adversarial attacks](https://openaccess.thecvf.com/content_CVPR_2020/papers/Rahmati_GeoDA_A_Geometric_Framework_for_Black-Box_Adversarial_Attacks_CVPR_2020_paper.pdf) (CVPR)  [(Code)](https://github.com/thisisalirah/GeoDA)
- [The Imitation Game: Algorithm Selectionby Exploiting Black-Box Recommender](https://github.com/erwanlemerrer/erwanlemerrer.github.io/raw/master/files/imitation_blackbox_recommenders_netys-2020.pdf) (Netys)  [(Code)](https://github.com/gdamaskinos/RecRank)
- [Auditing News Curation Systems:A Case Study Examining Algorithmic and Editorial Logic in Apple News](https://ojs.aaai.org/index.php/ICWSM/article/view/7277) (ICWSM)   
- [Auditing Algorithms:  On Lessons Learned and the Risks of DataMinimization](https://dl.acm.org/doi/pdf/10.1145/3375627.3375852) (AIES)   
- [Extracting Training Data from Large Language Models](https://arxiv.org/pdf/2012.07805) (arxiv)   
### 2019
- [Adversarial Frontier Stitching for Remote Neural Network Watermarking](https://arxiv.org/abs/1711.01894) (Neural Computing and Applications)  [(Alternative implementation)](https://github.com/dunky11/adversarial-frontier-stitching)
- [Knockoff Nets: Stealing Functionality of Black-Box Models](https://arxiv.org/abs/1812.02766.pdf) (CVPR)   
- [Opening Up the Black Box:Auditing Google's Top Stories Algorithm](https://par.nsf.gov/servlets/purl/10101277) (Flairs-32)  
- [Making targeted black-box evasion attacks effective andefficient](https://arxiv.org/pdf/1906.03397.pdf) (arXiv)  
- [Online Learning for Measuring Incentive Compatibility in Ad Auctions](https://research.fb.com/wp-content/uploads/2019/05/Online-Learning-for-Measuring-Incentive-Compatibility-in-Ad-Auctions.pdf) (WWW)   
- [TamperNN: Efficient Tampering Detection of Deployed Neural Nets](https://arxiv.org/abs/1903.00317) (ISSRE)   
- [Neural Network Model Extraction Attacks in Edge Devicesby Hearing Architectural Hints](https://arxiv.org/pdf/1903.03916.pdf) (arxiv)   
- [Stealing Knowledge from Protected Deep Neural Networks Using Composite Unlabeled Data](https://ieeexplore.ieee.org/abstract/document/8851798) (ICNN)   
- [Neural Network Inversion in Adversarial Setting via Background Knowledge Alignment](https://dl.acm.org/citation.cfm?id=3354261) (CCS)   
### 2018
- [Towards Reverse-Engineering Black-Box Neural Networks](https://arxiv.org/abs/1711.01768) (ICLR) [(Code)](https://github.com/coallaoh/WhitenBlackBox)
- [Data driven exploratory attacks on black box classifiers in adversarial domains](https://www.sciencedirect.com/science/article/pii/S092523121830136X) (Neurocomputing)   
- [xGEMs: Generating Examplars to Explain Black-Box Models](https://arxiv.org/pdf/1806.08867.pdf) (arXiv)   
- [Learning Networks from Random Walk-Based Node Similarities](https://arxiv.org/pdf/1801.07386) (arXiv), to appear in NIPS   
- [Identifying the Machine Learning Family from Black-Box Models](https://rd.springer.com/chapter/10.1007/978-3-030-00374-6_6) (CAEPIA)   
- [Stealing Neural Networks via Timing Side Channels](https://arxiv.org/pdf/1812.11720.pdf) (arXiv)   
- [Copycat CNN: Stealing Knowledge by Persuading Confession with Random Non-Labeled Data](https://arxiv.org/abs/1806.05476) (IJCNN)  [(Code)](https://github.com/jeiks/Stealing_DL_Models)
- [Auditing the Personalization and Composition ofPolitically-Related Search Engine Results Pages](https://dl.acm.org/doi/10.1145/3178876.3186143) (WWW)  
### 2017
- [Uncovering Influence Cookbooks : Reverse Engineering the Topological Impact in Peer Ranking Services](https://dl.acm.org/authorize.cfm?key=N21772) (CSCW)   
- [The topological face of recommendation: models and application to bias detection](https://arxiv.org/abs/1704.08991) (Complex Networks)  
- [Membership Inference Attacks Against Machine Learning Models](http://ieeexplore.ieee.org/document/7958568/) (Symposium on Security and Privacy)
- [Practical Black-Box Attacks against Machine Learning](https://dl.acm.org/citation.cfm?id=3053009) (Asia CCS)  
### 2016
- [Bias in Online Freelance Marketplaces: Evidence from TaskRabbit](http://datworkshop.org/papers/dat16-final22.pdf) (dat workshop)   
- [Stealing Machine Learning Models via Prediction APIs](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/tramer) (Usenix Security)  [(Code)](https://github.com/ftramer/Steal-ML)
- [“Why Should I Trust You?”Explaining the Predictions of Any Classifier](https://arxiv.org/pdf/1602.04938v3.pdf) (arXiv)  [(Code)](https://github.com/marcotcr/lime-experiments)
- [Back in Black: Towards Formal, Black Box Analysis of Sanitizers and Filters](http://ieeexplore.ieee.org/document/7546497/) (Security and Privacy)   
- [Algorithmic Transparency via Quantitative Input Influence: Theory and Experiments with Learning Systems](http://ieeexplore.ieee.org/document/7546525/) (Security and Privacy)   
### 2015
- [Peeking Beneath the Hood of Uber](https://dl.acm.org/citation.cfm?id=2815681) (IMC)
### 2014
- [XRay: Enhancing the Web's Transparency with Differential Correlation](https://www.usenix.org/node/184394) (USENIX Security)  
### 2013
- [Measuring Personalization of Web Search](https://dl.acm.org/citation.cfm?id=2488435) (WWW)   
### 2012
- [Query Strategies for Evading Convex-Inducing Classifiers](http://www.jmlr.org/papers/v13/nelson12a.html) (JMLR)
### 2008
- [Privacy Oracle: a System for Finding Application Leakswith Black Box Differential Testing](https://dl.acm.org/citation.cfm?id=1455806) (CCS)   
### 2005
- [Adversarial Learning](https://dl.acm.org/citation.cfm?id=1081950) (KDD)
