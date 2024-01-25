Welcome to the website for the MOOMIN workshop, the first workshop on Modular and Open Multilingual NLP, to be held at [EACL 2024 in Malta](https://2024.eacl.org/) on March 21st.

<!-- **_This website is still under construction._** -->


## Workshop Topic and Content

NLP in the age of monolithic large language models starts to hit the limits in terms of size and information that can be handled. The trend goes to modularization, a necessary step into the direction of designing smaller sub-networks and components with specialized functionality. Two of the currently most debated models, GPT-4 and NLLB, successfully apply gated routing and mixture of expert models, a type of trainable modularization.

### Scalability and Language Coverage

The problems of scalability are especially prominent in the field of multilingual NLP. 
Scaling a multilingual model to a high number of languages is prone to suffer from negative interference, also known as _the curse of multilinguality_, leading to degradation in per-language performance, mainly due to the limited model capacity ([Conneau et al, 2019](https://aclanthology.org/2020.acl-main.747/), [Wang et al, 2020](https://aclanthology.org/2020.emnlp-main.359/)).
Increasing the overall model size, on the other hand, hits the ceiling in terms of trainability limited by hardware, data and training algorithms. Modularity addresses this problem by defining components that can specialize for specific tasks and languages keeping trainable parameters per language high and thus keeping the components expressive. Training can be parallelized and distributed with smart ways of routing and scheduling. Another idea is to create adapters to existing pre-trained models to add new functionalities without re-training the entire model. Sub-network selection and pruning are other techniques that extract components with special functions. 

The most popular modern large language models still offer very limited multilingual capabilities, restricted to a small set of highest-resource languages, and modularity offers a very promising set of tools towards increased multilinguality of the large models, either during their pretraining or in a post-hoc post-pretraining manner. 

### Efficiency and Re-usability

Modularity also promises efficient training, adaptation and inference through component selection, 
re-combination, aggregation, and re-use ([Pfeiffer et al, 2020](https://aclanthology.org/2020.emnlp-demos.7/)). There are huge potentials of saving computational costs and the overall carbon footprint. All of those attractive properties and ideas are subject of the workshop we propose. Stressing the re-use we also emphasize the development of open components that can be shared, deployed and widely integrated within the broader research community. Finally, we focus on multilinguality, one of the biggest remaining challenges in NLP.

## Supporting Projects

The workshop is supported by two projects:
 - **Found in Translation (FoTran)** is a project at the University of Helsinki on representation learning from multilingual data funded by the ERC. Part of FoTran is the development of a modular NMT framework with massively parallel data.
 - **GreenNLP** is a joint effort by the University of Turku, the Finnish IT Center for Science (CSC) and the University of Helsinki and aims at building resources for sustainable NLP using efficient use of data and computing resources. Modular NLP is one of its work packages.


### Workshop Topics

With this in mind, the MOOMIN workshop invites contributions related but not limited to the following topics:
 - mixture of expert models and gated routing
 - modular pre-training of multilingual language and translation models
 - effective transfer with modular architectures such as adapters and hypernetworks
 - efficient parallelization and distribution of modular model training
 - modular frameworks and architecture implementations
 - massively multilingual models with large language coverage
 - subnet selection and pruning
 - modular distillation
 - modular extensions of existing NLP models systems, especially in low-resource settings and for low-resource languages
 - evaluation of modular systems in terms of performance, efficiency, and computational costs
 - platforms for distributing, sharing, and integrating NLP components

