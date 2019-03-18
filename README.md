# Black-box querying algorithms

A reading list of algorithms for getting insights of remote (black-box) services.

----------

This page aims at listing algorithms (with a short review) related to the following scenario:

> A user queries a service provider (through available APIs),  and tries to infer information about the algorithms in use for providing the results of those queries.

Related keywords include: `transparency`, `bias`, `inference`, `API`, `queries`, `reverse engineering`, `black-box`, `algorithmic accountability`.

## List of algorithms

| Algorithm/paper | Source | Description | Code | Test |
| --------------- | ------ | ----------- | ---- | ---- |
| [Adversarial Learning](https://dl.acm.org/citation.cfm?id=1081950) | KDD (2005) | Reverse engineering of remote linear classifiers, using membership queries |  | Experimented (locally) on mail spam classifiers |
| [Query Strategies for Evading Convex-Inducing Classifiers](http://www.jmlr.org/papers/v13/nelson12a.html) | JMLR (2012) | Evasion methods for convex classifiers. Considers evasion complexity |  |  |
| [Measuring Personalization of Web Search](https://dl.acm.org/citation.cfm?id=2488435) | WWW (2013) | Develops a methodology for measuring personalization in Web search result |  | Experimented on Google Web Search |
| [XRay: Enhancing the Web’s Transparency with Differential Correlation](https://www.usenix.org/node/184394) | USENIX Security (2014) | Audits which user profile data were used for targeting a particular ad, recommendation, or price | [ Available here](https://xray.cs.columbia.edu/) | Demonstrated using Gmail, Youtube, and Amazon recommendation services |
| [Peeking Beneath the Hood of Uber ](https://dl.acm.org/citation.cfm?id=2815681) | IMC (2015) | Infer implementation details of Uber's surge price algorithm |  | Four weeks of data from Uber (from 43  copies  of  the  Uber  app) |
| [Bias in Online Freelance Marketplaces: Evidence from TaskRabbit](http://datworkshop.org/papers/dat16-final22.pdf) | dat workshop (2016) | Measures the TaskRabbit’s search algorithm rank |  | Crawled TaskRabbit website |
| [Stealing Machine Learning Models via Prediction APIs](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/tramer) | Usenix Security (2016) | Aims at extracting machine learning models in use by remote services | [Available here](https://github.com/ftramer/Steal-ML) | Demonstrated on BigMl and Amazon Machine Learning services |
| [“Why Should I Trust You?”Explaining the Predictions of Any Classifier](https://arxiv.org/pdf/1602.04938v3.pdf) | arXiv (2016) | Explains a blackbox classifier model by sampling around data instances | [Available here](https://github.com/marcotcr/lime-experiments) | Experimented on religion newsgroup aond on multi-momain sentiment datasets |
| [Back in Black: Towards Formal, Black Box Analysis of Sanitizers and Filters](http://ieeexplore.ieee.org/document/7546497/) | Security and Privacy (2016) | Black-box analysis of  sanitizers  and  filters |  |  |
| [Algorithmic Transparency via Quantitative Input Influence: Theory and Experiments with Learning Systems](http://ieeexplore.ieee.org/document/7546525/) | Security and Privacy (2016) | Introduces measures that  capture  the  degree  of  influence  of  inputs  on  outputs  of the observed system |  | Tested inhouse on machine learning models on two datasets |
| [ Uncovering Influence Cookbooks : Reverse Engineering the Topological Impact in Peer Ranking Services](https://dl.acm.org/authorize.cfm?key=N21772) | CSCW (2017) | Aims at identifying which centrality metrics are in use in a peer ranking service |  |  |
| [ The topological face of recommendation: models and application to bias detection](https://arxiv.org/abs/1704.08991) | Complex Networks (2017)| Proposes a bias detection framework for items recommended to users |  | Tested on Youtube crawls |
| [ Membership Inference Attacks Against Machine Learning Models ](http://ieeexplore.ieee.org/document/7958568/) | Symposium on Security and Privacy (2017) | Given  a  machine  learning model and a record, determine whether this record was used as part of the model’s training dataset or not |  | Tested using Amazon ML and Google Prediction API |
| [ Adversarial Frontier Stitching for Remote Neural Network Watermarking ](https://arxiv.org/abs/1711.01894) | arXiv (2017) | Check if a remote machine learning model is a "leaked" one: through standard API requests to a remote model, extract (or not) a zero-bit watermark, that was inserted to watermark valuable models (eg, large deep neural networks) |  |  |
| [Practical Black-Box Attacks against Machine Learning](https://dl.acm.org/citation.cfm?id=3053009) | Asia CCS (2017)| Understand how vulnerable is a remote service to adversarial classification attacks |  | Tested against  Amazon and Google classification APIs |
| [Towards Reverse-Engineering Black-Box Neural Networks](https://arxiv.org/abs/1711.01768) | ICLR (2018)| Infer inner hyperparameters (eg number of layers, non-linear activation type) of a remote neural network model by analysing its response patterns to certain inputs | [Available here](https://github.com/coallaoh/WhitenBlackBox) |  |
| [Data driven exploratory attacks on black box classifiers in adversarial domains](https://www.sciencedirect.com/science/article/pii/S092523121830136X) | Neurocomputing (2018) | Reverse engineers remote classifier models (e.g., for evading a CAPTCHA test) |  | Tested on Google Cloud Prediction API  |
| [xGEMs: Generating Examplars to Explain Black-Box Models](https://arxiv.org/pdf/1806.08867.pdf) | arXiv (2018) | Searches bias in the black box model by training an unsupervised implicit generative model. Thensummarizes the black-box model behavior quantitatively by perturbing data samples along the data manifold. |  | Tested on Resnet models  |
| [Learning Networks from Random Walk-Based Node Similarities](https://arxiv.org/pdf/1801.07386) | arXiv (2018), to appear in NIPS | Reversing graphs by observing some random walk commute times. |  |  |
| [Identifying the Machine Learning Family from Black-Box Models](https://rd.springer.com/chapter/10.1007/978-3-030-00374-6_6) | CAEPIA (2018) |  Determines which kind of machine learning model is behind the returned predictions. |  |  |
| [Knockoff Nets: Stealing Functionality of Black-Box Models](https://arxiv.org/abs/1812.02766.pdf) | arXiv (2018) | ask to what extent can an adversary steal functionality of such "victim" models based solely on blackbox interactions: image in, predictions out. |  |  |
| [Stealing Neural Networks via Timing Side Channels](https://arxiv.org/pdf/1812.11720.pdf) | arXiv (2018) | Stealing/approximating a model through timing attacks usin queries |  |  |

## Related forums and conferences
* FAT 2018 (Conference on Fairness, Accountability, and Transparency) https://fatconference.org/2018/program.html
* DTL 2017 (Data Transparency Lab Conference) http://datatransparencylab.org/dtl-2017/program-dtl-2017/

## Page could be updated by adding new references, thanks !
