<div class="github-widget" data-repo="erwanlemerrer/awesome-audit-algorithms"></div>
## Awesome Audit Algorithms [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of algorithms for auditing black-box algorithms.
Nowadays, many algorithms (recommendation, scoring, classification) are operated at third party providers, without users or institutions having any insights on how they operate on their data. Audit algorithms in this list thus apply to this setup, coined the "black-box" setup, where one auditor wants to get some insight on these remote algorithms.

<img src="https://raw.githubusercontent.com/erwanlemerrer/awesome-audit-algorithms/blob/main/resources/audit.png" width="600" alt="banner" class="center">

> A user queries a remote algorithm (eg, through available APIs), to infer information about that algorithm.


## Papers
### 2024
- [LLMs hallucinate graphs too: a structural perspective](https://arxiv.org/abs/2409.00159) - (ArXiv) *Queries LLMs for known graphs and studies topological hallucinations. Proposes a structural hallucination rank.*
- [Fairness Auditing with Multi-Agent Collaboration](https://arxiv.org/pdf/2402.08522) - (ECAI) *Considers multiple
agents working together, each auditing the same platform for different tasks.*
- [Mapping the Field of Algorithm Auditing: A Systematic Literature Review
Identifying Research Trends, Linguistic and Geographical Disparities](https://arxiv.org/pdf/2401.11194) - (Arxiv) *Systematic review of algorithm
auditing studies and identification of trends in their methodological approaches.*
- [FairProof: Confidential and Certifiable Fairness for Neural Networks](https://arxiv.org/pdf/2402.12572v1.pdf) - (Arxiv) *Proposes an alternative paradigm to traditional auditing using crytographic tools like Zero-Knowledge Proofs; gives a system called FairProof for verifying fairness of small neural networks.*
- [Under manipulations, are some AI models harder to audit?](https://grodino.github.io/projects/manipulated-audits/preprint.pdf) - (SATML) *Relates the difficulty of black-box audits
to the capacity of the targeted models, using the Rademacher complexity.*
- [Improved Membership Inference Attacks Against Language Classification Models](https://arxiv.org/pdf/2310.07219.pdf) - (ICLR) *Presents a framework for running membership inference attacks against classifier, in audit mode.*
- [Auditing Fairness by Betting](https://arxiv.org/pdf/2305.17570.pdf) - (Neurips) [[Code]](https://github.com/bchugg/auditing-fairness) *Sequential methods that allows for the continuous monitoring of incoming data from a black-box classifier or regressor.*
### 2023
- [Privacy Auditing with One (1) Training Run](https://neurips.cc/virtual/2023/poster/70925) - (NeurIPS - best paper) *A scheme for auditing differentially private machine learning systems with a single training run.*
- [XAudit : A Theoretical Look at Auditing with Explanations](https://arxiv.org/pdf/2206.04740.pdf) - (Arxiv) *Formalizes the role of explanations in auditing and investigates if and how model explanations
can help audits.*
- [Keeping Up with the Language Models: Robustness-Bias Interplay in NLI Data and Models](https://arxiv.org/pdf/2305.12620.pdf) - (Arxiv) *Proposes a way to extend the shelf-life of auditing datasets by using language models themselves; also finds problems with the current bias auditing metrics and proposes alternatives -- these alternatives highlight that model brittleness superficially increased the previous bias scores.*
- [Online Fairness Auditing through Iterative Refinement](https://dl.acm.org/doi/pdf/10.1145/3580305.3599454) - (KDD) *Provides an adaptive process that automates the inference of probabilistic guarantees associated with estimating fairness metrics.*
- [Stealing the Decoding Algorithms of Language Models](https://people.cs.umass.edu/~amir/papers/CCS23-LM-stealing.pdf) - (CCS) *Steal the type and hyperparameters of the decoding algorithms of a LLM.*
- [Modeling rabbit‑holes on YouTube](https://link.springer.com/epdf/10.1007/s13278-023-01105-9?sharing_token=h-O-asHI49VUWS9FxN1Gsve4RwlQNchNByi7wbcMAY6I98PKW1PqhFQJ_JqQyk3TrB05qDb3LUzMDmKOgrupccQliViDle-rwKEi2MZ8xBViaAQhyN41oZBKLLeXchoeIW2kklVHC094I5KD8pxja4-if6-iB0uAI1FnqnYoxjU%3D) - (SNAM) *Models the trapping dynamics of users in rabbit holes in YouTube, and provides a measure of this enclosure.*
- [Auditing YouTube’s Recommendation Algorithm for Misinformation Filter Bubbles](https://dl.acm.org/doi/full/10.1145/3568392) - (Transactions on Recommender Systems) *What it takes to “burst the bubble,” i.e., revert the bubble enclosure from recommendations.*
- [Auditing Yelp’s Business Ranking and Review Recommendation Through the Lens of Fairness](https://arxiv.org/pdf/2308.02129.pdf) - (Arxiv) *Audits the fairness of Yelp’s business
ranking and review recommendation systems, with demographic parity, exposure, and statistical tests such as quantile linear and logistic regression.*
- [Confidential-PROFITT: Confidential PROof of FaIr Training of Trees](https://openreview.net/pdf?id=iIfDQVyuFD) - (ICLR) *Proposes fair decision tree learning algorithms along with zero-knowledge proof protocols to obtain a proof of fairness on the audited server.*
- [SCALE-UP: An Efficient Black-box Input-level Backdoor Detection via Analyzing Scaled Prediction Consistency](https://arxiv.org/pdf/2302.03251.pdf) - (ICLR) *Considers backdoor detection under the black-box setting in machine learning as a service (MLaaS) applications.*
### 2022
- [Two-Face: Adversarial Audit of Commercial Face Recognition Systems](https://ojs.aaai.org/index.php/ICWSM/article/view/19300/19072) - (ICWSM) *Performs an adversarial audit on multiple systems APIs and datasets, making a number of concerning observations.*
- [Scaling up search engine audits: Practical insights for algorithm auditing](https://journals.sagepub.com/doi/10.1177/01655515221093029) - (Journal of Information Science) [(Code)](https://github.com/gesiscss/WebBot) *Audits multiple search engines using simulated browsing behavior with virtual agents.*
- [A zest of lime: towards architecture-independent model distances](https://openreview.net/pdf?id=OUz_9TiTv9j) - (ICLR) *Measures the distance between two remote models using LIME.*
- [Active Fairness Auditing](https://proceedings.mlr.press/v162/yan22c/yan22c.pdf) - (ICML) *Studies of query-based auditing algorithms that can estimate the demographic parity of ML models in a query-efficient manner.*
- [Look at the Variance! Efficient Black-box Explanations with Sobol-based Sensitivity Analysis](https://proceedings.neurips.cc/paper/2021/file/da94cbeff56cfda50785df477941308b-Paper.pdf) - (NeurIPS) *Sobol indices provide an efficient way to capture higher-order interactions between image regions and their contributions to a (black box) neural network’s prediction through the lens of variance.*
- [Your Echos are Heard: Tracking, Profiling, and Ad Targeting in the Amazon Smart Speaker Ecosystem](https://arxiv.org/pdf/2204.10920.pdf) - (arxiv) *Infers a link between the Amazon Echo system and the ad targeting algorithm.*
### 2021
- [When the Umpire is also a Player: Bias in Private Label Product Recommendations on E-commerce Marketplaces](https://arxiv.org/pdf/2102.00141.pdf) - (FAccT) *Do Amazon private label products get an unfair share of recommendations and are therefore advantaged compared to 3rd party products?*
- [Everyday Algorithm Auditing: Understanding the Power of Everyday Users in Surfacing Harmful Algorithmic Behaviors](https://arxiv.org/pdf/2105.02980.pdf) - (CHI) *Makes the case for "everyday algorithmic auditing" by users.*
- [Auditing Black-Box Prediction Models for Data Minimization Compliance](https://www.cs.bu.edu/faculty/crovella/paper-archive/minimization-audit-Neurips21.pdf) - (NeurIPS) *Measures the level of data minimization satisfied by the prediction model using a limited number of queries.*
- [Setting the Record Straighter on Shadow Banning](https://arxiv.org/abs/2012.05101) - (INFOCOM)  [(Code)](https://gitlab.enseeiht.fr/bmorgan/infocom-2021) *Considers the possibility of shadow banning in Twitter (ie, the moderation black-box algorithm), and measures the probability of several hypothesis.*
- [Extracting Training Data from Large Language Models](https://arxiv.org/pdf/2012.07805.pdf) - (USENIX Security) *Extract verbatim text sequences from the GPT-2 model’s training data.*
- [FairLens: Auditing black-box clinical decision support systems](https://www.sciencedirect.com/science/article/pii/S030645732100145X?casa_token=oyjFKij269MAAAAA:w_ohScpMPNMnkDdzBqAIod5QfBgQlq5Ht9mMRSOydZpOgNG-i1yuqEmBjWN__38gOGmjNL7dVT0) - (Information Processing & Management) *Presents a pipeline to detect and explain potential fairness issues in Clinical DSS, by comparing different multi-label classification disparity measures.*
- [Auditing Algorithmic Bias on Twitter](https://dl.acm.org/doi/abs/10.1145/3447535.3462491) - (WebSci).
- [Bayesian Algorithm Execution: Estimating Computable Properties of Black-box Functions Using Mutual Information](https://proceedings.mlr.press/v139/neiswanger21a.html) - (ICML) *A budget constrained and Bayesian optimization procedure to extract properties out of a black-box algorithm.*
### 2020
- [Black-Box Ripper: Copying black-box models using generative evolutionary algorithms](https://proceedings.neurips.cc/paper/2020/file/e8d66338fab3727e34a9179ed8804f64-Paper.pdf) - (NeurIPS) *Replicates the functionality of a black-box neural model, yet with no limit on the amount of queries (via a teacher/student scheme and an evolutionary search).*
- [Auditing radicalization pathways on ](https://dl.acm.org/doi/pdf/10.1145/3351095.3372879) - (FAT*) *Studies the reachability of radical channels from each others, using random walks on static channel recommendations.*
- [Adversarial Model Extraction on Graph Neural Networks](https://arxiv.org/abs/1912.07721) - (AAAI Workshop on Deep Learning on Graphs: Methodologies and Applications) *Introduces GNN model extraction and presents a preliminary approach for this.*
- [Remote Explainability faces the bouncer problem](https://rdcu.be/b6qB4) - (Nature Machine Intelligence volume 2, pages529–539)  [(Code)](https://github.com/erwanlemerrer/bouncer_problem) *Shows the impossibility (with one request) or the difficulty to spot lies on the explanations of a remote AI decision.*
- [GeoDA: a geometric framework for black-box adversarial attacks](https://openaccess.thecvf.com/content_CVPR_2020/papers/Rahmati_GeoDA_A_Geometric_Framework_for_Black-Box_Adversarial_Attacks_CVPR_2020_paper.pdf) - (CVPR)  [(Code)](https://github.com/thisisalirah/GeoDA) *Crafts adversarial examples to fool models, in a pure blackbox setup (no gradients, inferred class only).*
- [The Imitation Game: Algorithm Selectionby Exploiting Black-Box Recommender](https://github.com/erwanlemerrer/erwanlemerrer.github.io/raw/master/files/imitation_blackbox_recommenders_netys-2020.pdf) - (Netys)  [(Code)](https://github.com/gdamaskinos/RecRank) *Parametrize a local recommendation algorithm by imitating the decision of a remote and better trained one.*
- [Auditing News Curation Systems:A Case Study Examining Algorithmic and Editorial Logic in Apple News](https://ojs.aaai.org/index.php/ICWSM/article/view/7277) - (ICWSM) *Audit study of Apple News as a sociotechnical news curation system (trending stories section).*
- [Auditing Algorithms:  On Lessons Learned and the Risks of DataMinimization](https://dl.acm.org/doi/pdf/10.1145/3375627.3375852) - (AIES) *A practical audit for a well-being recommendation app developed by Telefónica (mostly on bias).*
- [Extracting Training Data from Large Language Models](https://arxiv.org/pdf/2012.07805) - (arxiv) *Performs a training data extraction attack to recover individual training examples by querying the language model.*
### 2019
- [Adversarial Frontier Stitching for Remote Neural Network Watermarking](https://arxiv.org/abs/1711.01894) - (Neural Computing and Applications) [(Alternative implementation)](https://github.com/dunky11/adversarial-frontier-stitching) *Check if a remote machine learning model is a "leaked" one: through standard API requests to a remote model, extract (or not) a zero-bit watermark, that was inserted to watermark valuable models (eg, large deep neural networks).*
- [Knockoff Nets: Stealing Functionality of Black-Box Models](https://arxiv.org/abs/1812.02766.pdf) - (CVPR) *Ask to what extent can an adversary steal functionality of such "victim" models based solely on blackbox interactions: image in, predictions out.*
- [Opening Up the Black Box:Auditing Google's Top Stories Algorithm](https://par.nsf.gov/servlets/purl/10101277) - (Flairs-32) *Audit of the Google's Top stories panel that pro-vides insights into its algorithmic choices for selectingand ranking news publisher*
- [Making targeted black-box evasion attacks effective andefficient](https://arxiv.org/pdf/1906.03397.pdf) - (arXiv) *Investigates how an adversary can optimally use its query budget for targeted evasion attacks against deep neural networks.*
- [Online Learning for Measuring Incentive Compatibility in Ad Auctions](https://research.fb.com/wp-content/uploads/2019/05/Online-Learning-for-Measuring-Incentive-Compatibility-in-Ad-Auctions.pdf) - (WWW) *Measures the incentive compatible- (IC) mechanisms (regret) of black-box auction platforms.* 
- [TamperNN: Efficient Tampering Detection of Deployed Neural Nets](https://arxiv.org/abs/1903.00317) - (ISSRE) *Algorithms to craft inputs that can detect the tampering with a remotely executed classifier model.*
- [Neural Network Model Extraction Attacks in Edge Devicesby Hearing Architectural Hints](https://arxiv.org/pdf/1903.03916.pdf) - (arxiv) *Through the acquisition of memory access events from bus snooping, layer sequence identification bythe LSTM-CTC model, layer topology connection according to the memory access pattern, and layer dimension estimation under data volume constraints, it demonstrates one can accurately recover the a similar network architecture as the attack starting point*
- [Stealing Knowledge from Protected Deep Neural Networks Using Composite Unlabeled Data](https://ieeexplore.ieee.org/abstract/document/8851798) - (ICNN) *Composite method which can be used to attack and extract the knowledge ofa black box model even if it completely conceals its softmaxoutput.*
- [Neural Network Inversion in Adversarial Setting via Background Knowledge Alignment](https://dl.acm.org/citation.cfm?id=3354261) - (CCS) *Model inversion approach in the adversary setting based on training an inversion model that acts as aninverse of the original model. With no fullknowledge about the original training data, an accurate inversion is still possible by training the inversion model on auxiliary samplesdrawn from a more generic data distribution.*
### 2018
- [Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR](https://arxiv.org/abs/1711.00399) - (Harvard Journal of Law & Technology) *To explain a decision on x, find a conterfactual: the closest point to x that changes the decision.*
- [Distill-and-Compare: Auditing Black-Box Models Using Transparent Model Distillation](https://arxiv.org/abs/1710.06169) - (AIES) *Treats black box models as teachers, training transparent student models to mimic the risk scores assigned by black-box models.*
- [Towards Reverse-Engineering Black-Box Neural Networks](https://arxiv.org/abs/1711.01768) - (ICLR) [(Code)](https://github.com/coallaoh/WhitenBlackBox) *Infer inner hyperparameters (eg number of layers, non-linear activation type) of a remote neural network model by analysing its response patterns to certain inputs.*
- [Data driven exploratory attacks on black box classifiers in adversarial domains](https://www.sciencedirect.com/science/article/pii/S092523121830136X) - (Neurocomputing) *Reverse engineers remote classifier models (e.g., for evading a CAPTCHA test).*
- [xGEMs: Generating Examplars to Explain Black-Box Models](https://arxiv.org/pdf/1806.08867.pdf) - (arXiv) *Searches bias in the black box model by training an unsupervised implicit generative model. Thensummarizes the black-box model behavior quantitatively by perturbing data samples along the data manifold.*
- [Learning Networks from Random Walk-Based Node Similarities](https://arxiv.org/pdf/1801.07386) - (NIPS) *Reversing graphs by observing some random walk commute times.*
- [Identifying the Machine Learning Family from Black-Box Models](https://rd.springer.com/chapter/10.1007/978-3-030-00374-6_6) - (CAEPIA) *Determines which kind of machine learning model is behind the returned predictions.* 
- [Stealing Neural Networks via Timing Side Channels](https://arxiv.org/pdf/1812.11720.pdf) - (arXiv) *Stealing/approximating a model through timing attacks usin queries.*
- [Copycat CNN: Stealing Knowledge by Persuading Confession with Random Non-Labeled Data](https://arxiv.org/abs/1806.05476) - (IJCNN)  [(Code)](https://github.com/jeiks/Stealing_DL_Models) *Stealing black-box models (CNNs) knowledge by querying them with random natural images (ImageNet and Microsoft-COCO).*
- [Auditing the Personalization and Composition of Politically-Related Search Engine Results Pages](https://dl.acm.org/doi/10.1145/3178876.3186143) - (WWW) *A Chrome extension to survey participants and collect the Search Engine Results Pages (SERPs) and autocomplete suggestions, for studying personalization and composition.* 
### 2017
- [Uncovering Influence Cookbooks : Reverse Engineering the Topological Impact in Peer Ranking Services](https://dl.acm.org/authorize.cfm?key=N21772) - (CSCW) *Aims at identifying which centrality metrics are in use in a peer ranking service.*
- [The topological face of recommendation: models and application to bias detection](https://arxiv.org/abs/1704.08991) - (Complex Networks) *Proposes a bias detection framework for items recommended to users.*
- [Membership Inference Attacks Against Machine Learning Models](http://ieeexplore.ieee.org/document/7958568/) - (Symposium on Security and Privacy) *Given a machine learning model and a record, determine whether this record was used as part of the model's training dataset or not.*
- [Practical Black-Box Attacks against Machine Learning](https://dl.acm.org/citation.cfm?id=3053009) - (Asia CCS) *Understand how vulnerable is a remote service to adversarial classification attacks.*
### 2016
- [Algorithmic Transparency via Quantitative Input Influence: Theory and Experiments with Learning Systems](https://www.andrew.cmu.edu/user/danupam/datta-sen-zick-oakland16.pdf) - (IEEE S&P) *Evaluate the individual, joint and marginal influence of features on a model using shapley values.*
- [Auditing Black-Box Models for Indirect Influence](https://arxiv.org/abs/1602.07043) - (ICDM) *Evaluate the influence of a variable on a black-box model by "cleverly" removing it from the dataset and looking at the accuracy gap*
- [Iterative Orthogonal Feature Projection for Diagnosing Bias in Black-Box Models](https://arxiv.org/abs/1611.04967) - (FATML Workshop) *Performs feature ranking to analyse black-box models*
- [Bias in Online Freelance Marketplaces: Evidence from TaskRabbit](http://datworkshop.org/papers/dat16-final22.pdf) - (dat workshop) *Measures the TaskRabbit's search algorithm rank.* 
- [Stealing Machine Learning Models via Prediction APIs](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/tramer) - (Usenix Security)  [(Code)](https://github.com/ftramer/Steal-ML) *Aims at extracting machine learning models in use by remote services.*
- [“Why Should I Trust You?”Explaining the Predictions of Any Classifier](https://arxiv.org/pdf/1602.04938v3.pdf) - (arXiv)  [(Code)](https://github.com/marcotcr/lime-experiments) *Explains a blackbox classifier model by sampling around data instances.*
- [Back in Black: Towards Formal, Black Box Analysis of Sanitizers and Filters](http://ieeexplore.ieee.org/document/7546497/) - (Security and Privacy) *Black-box analysis of sanitizers and filters.*
- [Algorithmic Transparency via Quantitative Input Influence: Theory and Experiments with Learning Systems](http://ieeexplore.ieee.org/document/7546525/) - (Security and Privacy) *Introduces measures that capture the degree of influence of inputs on outputs of the observed system.*
- [An Empirical Analysis of Algorithmic Pricing on Amazon Marketplace](https://mislove.org/publications/Amazon-WWW.pdf) - (WWW) [(Code)](http://personalization.ccs.neu.edu) *Develops a methodology for detecting algorithmic pricing, and use it empirically to analyze their prevalence and behavior on Amazon Marketplace.*
### 2015
- [Certifying and Removing Disparate Impact](https://arxiv.org/abs/1412.3756) - (SIGKDD) *Proposes SVM-based methods to certify absence of bias and methods to remove biases from a dataset.*
- [Peeking Beneath the Hood of Uber](https://dl.acm.org/citation.cfm?id=2815681) - (IMC) *Infer implementation details of Uber's surge price algorithm.*
### 2014
- [A peek into the black box: exploring classifiers by randomization]() - (Data Mining and Knowledge Discovery journal) ([code](https://github.com/tsabsch/goldeneye)) *Finds groups of features that can be permuted without changing the output label of predicted samples*
- [XRay: Enhancing the Web's Transparency with Differential Correlation](https://www.usenix.org/node/184394) - (USENIX Security) *Audits which user profile data were used for targeting a particular ad, recommendation, or price.*
### 2013
- [Measuring Personalization of Web Search](https://dl.acm.org/citation.cfm?id=2488435) - (WWW) *Develops a methodology for measuring personalization in Web search result.*
- [Auditing: Active Learning with Outcome-Dependent Query Costs](https://www.cs.bgu.ac.il/~sabatos/papers/SabatoSarwate13.pdf) - (NIPS) *Learns from a binary classifier paying only for negative labels.*

### 2012
- [Query Strategies for Evading Convex-Inducing Classifiers](http://www.jmlr.org/papers/v13/nelson12a.html) - (JMLR) *Evasion methods for convex classifiers. Considers evasion complexity.*
### 2008
- [Privacy Oracle: a System for Finding Application Leakswith Black Box Differential Testing](https://dl.acm.org/citation.cfm?id=1455806) - (CCS) *Privacy Oracle: a system that uncovers applications' leaks of personal information in transmissions to remoteservers.*
### 2005
- [Adversarial Learning](https://dl.acm.org/citation.cfm?id=1081950) - (KDD) *Reverse engineering of remote linear classifiers, using membership queries.*

## Related Events

### 2024
* [1st International Conference on Auditing and Artificial Intelligence](https://www.ircg.msm.uni-due.de/ai/)
* [Regulatable ML Workshop (RegML'24)](https://regulatableml.github.io/)

### 2023
* [Supporting User Engagement in Testing, Auditing, and Contesting AI (CSCW User AI Auditing)](https://cscw-user-ai-auditing.github.io/)
* [Workshop on Algorithmic Audits of Algorithms (WAAA)](https://algorithmic-audits.github.io)
* [Regulatable ML Workshop (RegML'23)](https://regulatableml.github.io/)
