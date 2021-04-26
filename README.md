# Awesome audit algorithms [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of audit algorithms for getting insights from black-box algorithms.

 <img src="https://github.com/erwanlemerrer/awesome-audit-algorithms/blob/main/resources/audit.png" width="600" alt="banner" class="center">

> A user queries a remote algorithm (eg, through available APIs), to infer information about that algorithm.

Table of contents
=================

<!--ts-->
   * [Papers](#papers)
<!--te-->

## Papers

| Algorithm/paper | Source | Description | Code | Test |
| --------------- | ------ | ----------- | ---- | ---- |
| [Adversarial Learning](https://dl.acm.org/citation.cfm?id=1081950) | KDD (2005) | Reverse engineering of remote linear classifiers, using membership queries |  | Experimented (locally) on mail spam classifiers |
| [Privacy Oracle: a System for Finding Application Leakswith Black Box Differential Testing](https://dl.acm.org/citation.cfm?id=1455806) | CCS (2008) |  Privacy Oracle: a system that uncovers appli-cations’ leaks of personal information in transmissions to remoteservers. |  | Experimented on evaluated 26 popular applications |
| [Query Strategies for Evading Convex-Inducing Classifiers](http://www.jmlr.org/papers/v13/nelson12a.html) | JMLR (2012) | Evasion methods for convex classifiers. Considers evasion complexity |  |  |
| [Measuring Personalization of Web Search](https://dl.acm.org/citation.cfm?id=2488435) | WWW (2013) | Develops a methodology for measuring personalization in Web search result |  | Experimented on Google Web Search |
| [XRay: Enhancing the Web’s Transparency with Differential Correlation](https://www.usenix.org/node/184394) | USENIX Security (2014) | Audits which user profile data were used for targeting a particular ad, recommendation, or price | [ Available here](https://xray.cs.columbia.edu/) | Demonstrated using Gmail, YouTube, and Amazon recommendation services |
| [Peeking Beneath the Hood of Uber ](https://dl.acm.org/citation.cfm?id=2815681) | IMC (2015) | Infer implementation details of Uber's surge price algorithm |  | Four weeks of data from Uber (from 43  copies  of  the  Uber  app) |
| [Bias in Online Freelance Marketplaces: Evidence from TaskRabbit](http://datworkshop.org/papers/dat16-final22.pdf) | dat workshop (2016) | Measures the TaskRabbit’s search algorithm rank |  | Crawled TaskRabbit website |
| [Stealing Machine Learning Models via Prediction APIs](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/tramer) | Usenix Security (2016) | Aims at extracting machine learning models in use by remote services | [Available here](https://github.com/ftramer/Steal-ML) | Demonstrated on BigMl and Amazon Machine Learning services |
| [“Why Should I Trust You?”Explaining the Predictions of Any Classifier](https://arxiv.org/pdf/1602.04938v3.pdf) | arXiv (2016) | Explains a blackbox classifier model by sampling around data instances | [Available here](https://github.com/marcotcr/lime-experiments) | Experimented on religion newsgroup aond on multi-momain sentiment datasets |
| [Back in Black: Towards Formal, Black Box Analysis of Sanitizers and Filters](http://ieeexplore.ieee.org/document/7546497/) | Security and Privacy (2016) | Black-box analysis of  sanitizers  and  filters |  |  |
| [Algorithmic Transparency via Quantitative Input Influence: Theory and Experiments with Learning Systems](http://ieeexplore.ieee.org/document/7546525/) | Security and Privacy (2016) | Introduces measures that  capture  the  degree  of  influence  of  inputs  on  outputs  of the observed system |  | Tested inhouse on machine learning models on two datasets |
| [ Uncovering Influence Cookbooks : Reverse Engineering the Topological Impact in Peer Ranking Services](https://dl.acm.org/authorize.cfm?key=N21772) | CSCW (2017) | Aims at identifying which centrality metrics are in use in a peer ranking service |  |  |
| [ The topological face of recommendation: models and application to bias detection](https://arxiv.org/abs/1704.08991) | Complex Networks (2017)| Proposes a bias detection framework for items recommended to users |  | Tested on YouTube crawls |
| [ Membership Inference Attacks Against Machine Learning Models ](http://ieeexplore.ieee.org/document/7958568/) | Symposium on Security and Privacy (2017) | Given  a  machine  learning model and a record, determine whether this record was used as part of the model’s training dataset or not |  | Tested using Amazon ML and Google Prediction API |
| [ Adversarial Frontier Stitching for Remote Neural Network Watermarking ](https://arxiv.org/abs/1711.01894) | Neural Computing and Applications (2019) | Check if a remote machine learning model is a "leaked" one: through standard API requests to a remote model, extract (or not) a zero-bit watermark, that was inserted to watermark valuable models (eg, large deep neural networks) | Alternative implementation [available here](https://github.com/dunky11/adversarial-frontier-stitching) |  |
| [Practical Black-Box Attacks against Machine Learning](https://dl.acm.org/citation.cfm?id=3053009) | Asia CCS (2017)| Understand how vulnerable is a remote service to adversarial classification attacks |  | Tested against  Amazon and Google classification APIs |
| [Towards Reverse-Engineering Black-Box Neural Networks](https://arxiv.org/abs/1711.01768) | ICLR (2018)| Infer inner hyperparameters (eg number of layers, non-linear activation type) of a remote neural network model by analysing its response patterns to certain inputs | [Available here](https://github.com/coallaoh/WhitenBlackBox) |  |
| [Data driven exploratory attacks on black box classifiers in adversarial domains](https://www.sciencedirect.com/science/article/pii/S092523121830136X) | Neurocomputing (2018) | Reverse engineers remote classifier models (e.g., for evading a CAPTCHA test) |  | Tested on Google Cloud Prediction API  |
| [xGEMs: Generating Examplars to Explain Black-Box Models](https://arxiv.org/pdf/1806.08867.pdf) | arXiv (2018) | Searches bias in the black box model by training an unsupervised implicit generative model. Thensummarizes the black-box model behavior quantitatively by perturbing data samples along the data manifold. |  | Tested on Resnet models  |
| [Learning Networks from Random Walk-Based Node Similarities](https://arxiv.org/pdf/1801.07386) | arXiv (2018), to appear in NIPS | Reversing graphs by observing some random walk commute times. |  |  |
| [Identifying the Machine Learning Family from Black-Box Models](https://rd.springer.com/chapter/10.1007/978-3-030-00374-6_6) | CAEPIA (2018) |  Determines which kind of machine learning model is behind the returned predictions. |  |  |
| [Knockoff Nets: Stealing Functionality of Black-Box Models](https://arxiv.org/abs/1812.02766.pdf) | CVPR (2019) | ask to what extent can an adversary steal functionality of such "victim" models based solely on blackbox interactions: image in, predictions out. |  |  |
| [Stealing Neural Networks via Timing Side Channels](https://arxiv.org/pdf/1812.11720.pdf) | arXiv (2018) | Stealing/approximating a model through timing attacks usin queries |  |  |
| [Copycat CNN: Stealing Knowledge by Persuading Confession with Random Non-Labeled Data](https://arxiv.org/abs/1806.05476) | IJCNN (2018) | Stealing black-box models (CNNs) knowledge by querying them with random natural images (ImageNet and Microsoft-COCO). | [Available here](https://github.com/jeiks/Stealing_DL_Models) | Tested on three problem domains (facial recognition, general object, and crosswalk classification) and Azure. |
| [Auditing the Personalization and Composition ofPolitically-Related Search Engine Results Pages](https://dl.acm.org/doi/10.1145/3178876.3186143) | WWW (2018) |  A Chrome extension to survey participants and collect the Search Engine Results Pages (SERPs) and autocomplete suggestions, for studying personalization and composition. | | Tested on Google search. |
| [Opening Up the Black Box:Auditing Google’s Top Stories Algorithm](https://par.nsf.gov/servlets/purl/10101277) | Flairs-32 (2019) | Audit of the Google’s Top stories panel that pro-vides insights into its algorithmic choices for selectingand ranking news publisher  | | Tested on Google's Top Stories. |
| [Making targeted black-box evasion attacks effective andefficient](https://arxiv.org/pdf/1906.03397.pdf) | arXiv (2019) |  Investigates how an adversary can optimally use its query budget for targeted evasion attacks against deep neural networks. | | Tested on Google Cloud Vision. |
| [Online Learning for Measuring Incentive Compatibility in Ad Auctions](https://research.fb.com/wp-content/uploads/2019/05/Online-Learning-for-Measuring-Incentive-Compatibility-in-Ad-Auctions.pdf) | WWW (2019) | Measures the incentive compatible (IC) mechanisms (regret) of black-box auction lpatforms |  |  |
| [TamperNN: Efficient Tampering Detection of Deployed Neural Nets](https://arxiv.org/abs/1903.00317) | ISSRE (2019) | Algorithms to craft inputs that can detect the tampering with a remotely executed classifier model |  | Tested on classic image classifiers available in Keras |
| [Neural Network Model Extraction Attacks in Edge Devicesby Hearing Architectural Hints](https://arxiv.org/pdf/1903.03916.pdf) | arxiv (2019) | Through the acquisition of memory access events from bus snooping, layer sequence identification bythe LSTM-CTC model, layer topology connection according to the memory access pattern, and layer dimension estimation under data volume constraints, it  demonstrates one can accurately recover the a similar network architecture as the attack starting point |  | |
| [Stealing Knowledge from Protected Deep Neural Networks Using Composite Unlabeled Data](https://ieeexplore.ieee.org/abstract/document/8851798) | ICNN (2019) | Composite  method which  can  be  used  to  attack  and  extract  the  knowledge  ofa black box model even if it completely conceals its softmaxoutput. |  | Tested on NVidia hardware |
| [Neural Network Inversion in Adversarial Setting via Background Knowledge Alignment](https://dl.acm.org/citation.cfm?id=3354261) | CCS (2019) | Model inversion approach in the adversary setting based on training an inversion model that acts as aninverse of the original model. With no fullknowledge about the original training data, an accurate inversion is still possible by training the inversion model on auxiliary samplesdrawn from a more generic data distribution. |  | Tested on Amazon Rekognition API |
| [Adversarial Model Extraction on Graph Neural Networks](https://arxiv.org/abs/1912.07721) | AAAI Workshop on Deep Learning on Graphs: Methodologies and Applications (DLGMA) (2020) | Introduces GNN model extraction and presents a preliminary approach for this. |  |  |
| [Remote Explainability faces the bouncer problem](https://rdcu.be/b6qB4) | Nature Machine Intelligence volume 2, pages529–539 (2020) | Shows the impossibility (with one request) or the difficulty to spot lies on the explanations of a remote AI decision. | [Available here](https://github.com/erwanlemerrer/bouncer_problem) |  |
| [GeoDA: a geometric framework for black-box adversarial attacks](https://openaccess.thecvf.com/content_CVPR_2020/papers/Rahmati_GeoDA_A_Geometric_Framework_for_Black-Box_Adversarial_Attacks_CVPR_2020_paper.pdf) | CVPR (2020) | Crafts adversarial examples to fool models, in a pure blackbox setup (no gradients, inferred class only). | [Available here](https://github.com/thisisalirah/GeoDA) |  |
| [The Imitation Game: Algorithm Selectionby Exploiting Black-Box Recommender](https://github.com/erwanlemerrer/erwanlemerrer.github.io/raw/master/files/imitation_blackbox_recommenders_netys-2020.pdf) | Netys (2020) | Parametrize a local recommendation algorithm by imitating the decision of a remote and better trained one. | [Available here](https://github.com/gdamaskinos/RecRank) |  |
| [Auditing News Curation Systems:A Case Study Examining Algorithmic and Editorial Logic in Apple News](https://ojs.aaai.org/index.php/ICWSM/article/view/7277) | ICWSM (2020) | Audit study of Apple News as a sociotechnical news curation system (trending stories section). |  | Tested against Apple News |
| [Auditing Algorithms:  On Lessons Learned and the Risks of DataMinimization](https://dl.acm.org/doi/pdf/10.1145/3375627.3375852) | AIES (2020) | A practical audit for a well-being   recommendation   app developed   by Telefónica (mostly on bias). |  |  |
| [Setting the Record Straighter on Shadow Banning](https://arxiv.org/abs/2012.05101) | INFOCOM (2021) | Considers the possibility of shadow banning in Twitter (ie, the moderation black-box algorithm), and measures the probability of several hypothesis. | [Available here](https://gitlab.enseeiht.fr/bmorgan/infocom-2021) |  |

