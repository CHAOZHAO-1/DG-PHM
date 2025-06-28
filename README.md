# Domain-generalization-for-fault-diagnosis-and-prognosis 领域泛化方法用于故障诊断和预测

# ![Awesome](https://img.shields.io/badge/Awesome-Yes-brightgreen) ![Last update](https://img.shields.io/badge/Last%20update-20250628-blue) ![Paper number](https://img.shields.io/badge/Paper%20Number-169-orange)

This is a repository about **Domain Generalization for PHM**, including papers, code, datasets etc. 

We will continue to update this repository and hope this repository can benefit your research.

![Image 1](https://github.com/CHAOZHAO-1/DG-PHM/blob/main/IMG2/combined_plot.png)


# Overview
- [1. Papers for Fault Diagnosis](#section-id1)

-   - [1.1 Survey](#section-id2)
-   - [1.2 Regular Paper](#section-id3)

-   -   - [1.2.1. Homogeneous Domain Generalization-based Fault Diagnosis (HDGFD)](#section-id3)
-   -   - [1.2.2. Federated Domain Generalization-based Fault Diagnosis (FedDGFD)](#section-id4)
-   -   - [1.2.3. Semisupervised Domain Generalization-based Fault Diagnosis (SemiDGFD)](#section-id5)
-   -   - [1.2.4. Open Set Domain Generalization-based Fault Diagnosis (OSDGFD)](#section-id6)
-   -   - [1.2.5. Imbalanced Domain Generalization-based Fault Diagnosis (IDGFD)](#section-id7)
-   -   - [1.2.6. Single Domain Generalization-based Fault Diagnosis (SDGFD)](#section-id8)
  
- [2. Data](#section-id9)

- [3.1. Code for Benchmark](#section-id10)

- [3.2. Code for Method Paper](#section-id13)

- [4. Papers for Prognosis](#section-id11)

- [5. Talk](#section-id14)

- [6. Related Project](#section-id12)


# Papers
> We list papers, implementation code (the unofficial code is marked with *), etc, in the order of year.
<a name="section-id1"></a>

## Survey （综述）
<a name="section-id2"></a>

### 2025

- Applications of domain generalization to machine fault diagnosis: A survey [[IEEE/CAA Journal of Automatica Sinica 2025](https://ieeexplore.ieee.org/abstract/document/10965929)] 

- Domain generalization for rotating machinery fault diagnosis: A survey [[AEI 2025](https://www.sciencedirect.com/science/article/pii/S1474034624007146)] 

### 2024

- Domain Generalization for Cross-Domain Fault Diagnosis: an Application-oriented Perspective and a Benchmark Study [[RESS 2024](https://www.sciencedirect.com/science/article/abs/pii/S0951832024000395?via%3Dihub)] （第一篇关于DGFD的综述）


### Homogeneous domain generalization-based fault diagnosis (HDGFD)
<a name="section-id3"></a>
> Basic setting:class space between mutiple source domains and unseen target domain is same.


### 2025


- A dual-perspective joint domain generalization network for bearing fault diagnosis under unseen working conditions  [[AEI 2025](https://www.sciencedirect.com/science/article/pii/S1474034625003404)]


- Specific Task-Guided Collaborative Domain Generalization Network for Intelligent Fault Diagnosis under Unseen Conditions  [[IoT 2025](https://ieeexplore.ieee.org/abstract/document/11007102)]


- Few-Shot Diffusion Domain Generalization for Diagnosing Joint Reducer Faults in Industrial Robots  [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/11023233)]


- Latent subdomain assignment based on pseudo domain labels for fault diagnosis of unseen data  [[AEI 2025](https://www.sciencedirect.com/science/article/pii/S1474034625004197)]


- A discriminator-free adversarial network for bearing fault diagnosis under unseen operating conditions  [[AA 2025](https://www.sciencedirect.com/science/article/pii/S0003682X25003494)]


- Operation Condition Assessment for Elevators Based on Multidomain Generalization and Adaptation  [[TMEC 2025](https://ieeexplore.ieee.org/abstract/document/10981655)]

- Multi-bearing fault diagnosis method based on convolutional autoencoder causal decoupling domain generalization  [[ISA 2025](https://www.sciencedirect.com/science/article/abs/pii/S0019057825002423)]


- Fault Diagnosis of Unseen Modes in Chemical Process via Fusing Invariance and Specificity  [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10994374)]

- Knowledge-informed multiplication convolution generalization network for interpretable equipment diagnosis under unknown speed domains  [[ASC 2025](https://www.sciencedirect.com/science/article/abs/pii/S1568494625005745)]


- Bearing fault diagnosis domain generalization network based on multi-scale feature alignment  [[MST 2025](https://iopscience.iop.org/article/10.1088/1361-6501/add8ac/meta)]

- A Causality-Inspired Capsule Network for Domain Generalization in Cross-Domain Fault Diagnosis of Rolling Bearing  [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/11004069)]


- Dynamic Meta-Decoupler-inspired Single-Universal Domain Generalization for Intelligent Fault Diagnosis [[ESWA 2025](https://www.sciencedirect.com/science/article/pii/S0957417425011509)]


- UDDGN: Domain-Independent Compact Boundary Learning Method for Universal Diagnosis Domain Generation [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10962449)]


- Enhancing Bearing Fault Diagnosis in Real Damages: A Hybrid Multidomain Generalization Network for Feature Comparison [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10955333)]


- Neuromorphic computing-enabled generalized machine fault diagnosis with dynamic vision [[AEI 2025](https://www.sciencedirect.com/science/article/abs/pii/S1474034625001934)]


- Domain generalization network based on inter-domain multivariate linearization for intelligent fault diagnosis [[RESS 2025](https://www.sciencedirect.com/science/article/abs/pii/S095183202500256X)]


- DG-Softmax: A new domain generalization intelligent fault diagnosis method for planetary gearboxes [[RESS 2025](https://www.sciencedirect.com/science/article/pii/S0951832025002583#cebibl1)]


- Multiple classifiers inconsistency-based deep adversarial domain generalization method for cross-condition fault diagnosis in rotating systems [[RESS 2025](https://www.sciencedirect.com/science/article/pii/S0951832025002182)]


- Cross-domain machinery fault diagnosis under unseen working conditions based on multiple auxiliary classifiers [[TIOM 2025](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003470076-82/cross-domain-machinery-fault-diagnosis-unseen-working-conditions-based-multiple-auxiliary-classifiers-rui-wang-weiguo-huang-xiao-zhang-mingkuan-shi-chuancang-ding-zhongkui-zhu)]


- Mutual Information-guided Domain Shared Feature Learning for Bearing Fault Diagnosis under Unknown Conditions [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10930619)]


- A Domain Generalization Method for Fault Diagnosis: Integrating Causal Leaming and Distributionally Robust Optimization [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10929665)]


- Dual disentanglement domain generalization method for rotating Machinery fault diagnosis [[MSSP 2025](https://www.sciencedirect.com/science/article/abs/pii/S088832702500161X)]


- Deep Causal Disentanglement Network with Domain Generalization for Cross-machine Bearing Fault Diagnosis [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10902465)]

- A Source Domain Adaptive Method for Transfer-Learning-Based Fault Diagnosis of Train Bogie Bearings at Higher Speeds [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10892004)]

- Frequency domain guided latent diffusion model for domain generalization in cross-machine fault diagnosis [[Measurement 2025](https://www.sciencedirect.com/science/article/abs/pii/S0263224125003483)]


- Invariant Feature Purification Method for Domain Generalization of Rolling Bearing Fault Diagnosis [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10816046)]

### 2024

- Domain-invariant feature exploration for intelligent fault diagnosis under unseen and time-varying working conditions [[MSSP 2024](https://www.sciencedirect.com/science/article/abs/pii/S0888327024010926)]

- Adversarial-Causal Representation Learning Networks for Machine fault diagnosis under unseen conditions based on vibration and acoustic signals [[EAAI 2024](https://www.sciencedirect.com/science/article/abs/pii/S0952197624017081)]

- A novel hybrid data-driven domain generalization approach with dual-perspective feature fusion for intelligent fault diagnosis [[EAAI 2024](https://www.sciencedirect.com/science/article/abs/pii/S095219762401772X)]

- Bearing fault diagnostic framework under unknown working conditions based on condition-guided diffusion model [[Measurement 2024](https://www.sciencedirect.com/science/article/abs/pii/S0263224124018360)]


- Utilizing Bayesian generalization network for reliable fault diagnosis of machinery with limited data [[KBS 2024](https://www.sciencedirect.com/science/article/abs/pii/S0950705124012620)]


- Self-adaptive fault diagnosis for unseen working conditions based on digital twins and domain generalization [[RESS 2024](https://www.sciencedirect.com/science/article/pii/S095183202400632X)]



- A bearing fault diagnosis method for unknown operating conditions based on differentiated feature extraction [[ISA 2024](https://www.sciencedirect.com/science/article/abs/pii/S0019057824005019)]


- Fully Simulated Data Driven Domain Generalized Method for Multiphase Converters Fault Diagnosis [[TPEL 2024](https://ieeexplore.ieee.org/abstract/document/10680356)]


- Meta-Learning-Based Domain Generalization for Cost-Effective Tool Condition Monitoring in Ultrasonic Metal Welding [[TII 2024](https://ieeexplore.ieee.org/document/10688397?denied=)]

- Deep subdomain adversarial network with self-supervised learning for aero-engine high speed bearing fault diagnosis with unknown working conditions [[Measurement 2024](https://www.sciencedirect.com/science/article/abs/pii/S0263224124015537)]

- Domain-augmented meta ensemble learning for mechanical fault diagnosis from heterogeneous source domains to unseen target domains [[ESWA 2024](https://www.sciencedirect.com/science/article/abs/pii/S0957417424022127)]

- Distance Aware Risk Minimization for Domain Generalization in Machine Fault Diagnosis [[IOT 2024](https://ieeexplore.ieee.org/abstract/document/10632096)] [[Code](https://github.com/mozhenling/doge-darm)]

- Causality-inspired multi-source domain generalization method for intelligent fault diagnosis under unknown operating conditions [[RESS 2024](https://www.sciencedirect.com/science/article/abs/pii/S0951832024005118)]

- DPICEN: Deep Physical Information Consistency Embedded Network for Bearing Fault Diagnosis under Unknown Domain [[RESS 2024](https://www.sciencedirect.com/science/article/abs/pii/S095183202400526X)]

- A domain feature decoupling network for rotating machinery fault diagnosis under unseen operating conditions [[RESS 2024](https://www.sciencedirect.com/science/article/abs/pii/S0951832024005210)]

- Domain Generalization Combining Covariance Loss With Graph Convolutional Networks for Intelligent Fault Diagnosis of Rolling Bearings [[TII 2024](https://ieeexplore.ieee.org/abstract/document/10643738)]

- CIS2N: Causal independence and sparse shift network for rotating machinery fault diagnosis in unseen domains [[RESS 2024](https://www.sciencedirect.com/science/article/abs/pii/S0951832024004538)]

- Feature Adaptive Modulation and Prototype Learning for Domain Generalization Intelligent Fault Diagnosis [[TII 2024](https://ieeexplore.ieee.org/abstract/document/10601528?casa_token=IIoGoHYjxtoAAAAA:goxoQguQmVXDeShmA3qeAvQus1xQ2UUOZGYfPOr5VKj4BXVHqpVmsFJjKPQSGy4UgdYiyprXL2c)]

- A novel causal feature learning-based domain generalization framework for bearing fault diagnosis with a mixture of data from multiple working conditions and machines [[AEI 2024](https://www.sciencedirect.com/science/article/pii/S1474034624002702)]

- Sharpness-Aware Gradient Alignment for Domain Generalization With Noisy Labels in Intelligent Fault Diagnosis [[TIM 2024](https://ieeexplore.ieee.org/abstract/document/10555403)]

- Fault vibration model driven fault-aware domain generalization framework for bearing fault diagnosis [[AEI 2024](https://www.sciencedirect.com/science/article/pii/S1474034624002684)]

- Chemical fault diagnosis network based on single domain generalization [[PROCESS SAF ENVIRON 2024](https://www.sciencedirect.com/science/article/pii/S0957582024006268)]

- Operating Condition Generalization Network for Fault Diagnosis of Brushless DC Motors [[TIE 2024](https://ieeexplore.ieee.org/abstract/document/10509661)]

- Novel Triplet Loss-Based Domain Generalization Network for Bearing Fault Diagnosis with Unseen Load Condition [[Process 2024](https://www.mdpi.com/2227-9717/12/5/882)]

- Unknown working condition fault diagnosis of rotate machine without training sample based on local fault semantic attribute [[AEI 2024](https://www.sciencedirect.com/science/article/pii/S1474034624001630)]

- Stochastic Embedding Domain Generalization Network for Rotating Machinery Fault Diagnosis under Unseen Operating Conditions [[IEEE Sensors 2024](https://ieeexplore.ieee.org/abstract/document/10495760)]

- Fault Diagnosis of Rotating Machinery Toward Unseen Working Condition: A Regularized Domain Adaptive Weight Optimization [[TII 2024](https://ieeexplore.ieee.org/abstract/document/10495728)]


- Semi-physical simulation-driven contrastive decoupling net for intelligent fault diagnosis of unseen machines under varying speed [[MST 2024](https://iopscience.iop.org/article/10.1088/1361-6501/ad36da/meta?casa_token=fpUcJcdMhY4AAAAA:VLnI2OELiNGkjiI6OWNLYsh4lXXXyprA5uZp8QX1eCVq1IfUZLU-gBxkAFVZOXXZmEcPuL8Qa4Pl7ggvGJ5s3CeTmg)]


- Dynamic Balanced Dual Prototypical Domain Generalization for Cross-Machine Fault Diagnosis [[TIM 2024](https://ieeexplore.ieee.org/abstract/document/10478588?casa_token=-G_y0OTBHNsAAAAA:0couiFmM9wFXOCrelYjrTp9gJmJbJAAlr8HwgbDQMq0AfFrdIvXe6MIdKXh1sR9RYK90XQg)]


- Novel Adversarial Unsupervised Subdomain Adaption Multi-Channel Deep Convolutional Network for Cross-Operating Fault Diagnosis of Rolling Bearings [[IEEE ACCESS 2024](https://ieeexplore.ieee.org/abstract/document/10473058)]

- PhysiCausalNet: A Causal- and Physics-Driven Domain Generalization Network for Cross-Machine Fault Diagnosis of Unseen Domain [[TII 2024](https://ieeexplore.ieee.org/document/10473208)]

- Zero-Shot Fault Diagnosis for Smart Process Manufacturing via Tensor Prototype Alignment [[TNNLS 2024](https://ieeexplore.ieee.org/document/10473210/)]

- Decoupled interpretable robust domain generalization networks: A fault diagnosis approach across bearings, working conditions, and artificial-to-real scenarios [[AEI 2024](https://www.sciencedirect.com/science/article/pii/S1474034624000934)]

- Domain generalization of chemical process fault diagnosis by maximizing domain feature distribution alignment [[PROCESS SAF ENVIRON 2024](https://www.sciencedirect.com/science/article/pii/S095758202400288X)]


- Causal Disentanglement Domain Generalization for time-series signal fault diagnosis [[NN 2024](https://www.sciencedirect.com/science/article/pii/S0893608024000133)]
  

- Industrial process fault diagnosis based on feature enhanced meta-learning toward domain generalization scenarios [[KBS 2024](https://www.sciencedirect.com/science/article/pii/S0950705124001412)]


- A Domain Generalization Network Exploiting Causal Representations and Non-causal Representations for Three-Phase Converter Fault Diagnosis [[TIM 2024](https://ieeexplore.ieee.org/abstract/document/10443913)]



- Rolling Bearing Fault Diagnosis Method Based On Dual Invariant Feature Domain Generalization [[TIM 2024](https://ieeexplore.ieee.org/abstract/document/10436117)]

- Stacked maximum independence autoencoders: A domain generalization approach for fault diagnosis under various working conditions [[MSSP 2024](https://www.sciencedirect.com/science/article/pii/S0888327023009433?casa_token=TPEkc-h1NxcAAAAA:CTnDvBy8VIOO-06cMg3z698bU0LvCCJx8H0OVGL1Qn55a8LbepeEsBso8A_VSF9CpoMXkF4f)]

- Causal explaining guided domain generalization for rotating machinery intelligent fault diagnosis [[ESA 2024](https://www.sciencedirect.com/science/article/pii/S0957417423033080?casa_token=jGBA5IXkaBoAAAAA:6cbWsTf0o2mSPLJN7QruV5wO8fzPGvuJWypOcgn1v9zEOEFqqhNraUmWm3TF8O5BkaVLnaX2)]

### 2023

- Task-Generalization-Based Graph Convolutional Network for Fault Diagnosis of Rod-Fastened Rotor System [[TII 2023](https://ieeexplore.ieee.org/abstract/document/10309830?casa_token=fG_kV9wKc4gAAAAA:rZIOZtNq7dMN_bd9U6w7SAWfSEc34tCuYtoVw_CkzsdqEm46XOSZadthe4CbIpjymucxx-w)]

- VIT-GADG: A Generative Domain Generalized Framework for Chillers Fault Diagnosis under Unseen Working Conditions [[TIM 2023](https://ieeexplore.ieee.org/abstract/document/10216370)]

- Gradient aligned domain generalization with a mutual teaching teacher-student network for intelligent fault diagnosis [[RESS 2023](https://www.sciencedirect.com/science/article/pii/S0951832023004301)]
- A novel domain generalization network with multidomain specific auxiliary classifiers for machinery fault diagnosis under unseen working conditions [[RESS 2023](https://www.sciencedirect.com/science/article/pii/S0951832023003770)]
- Fine-grained transfer learning based on deep feature decomposition for rotating equipment fault diagnosis [[MST 2023](https://iopscience.iop.org/article/10.1088/1361-6501/acc04a/meta)]

- Few-shot learning under domain shift: Attentional contrastive calibrated transformer of time series for fault diagnosis under sharp speed variation [[MSSP 2023](https://www.sciencedirect.com/science/article/abs/pii/S0888327022011396)]

- An information-induced fault diagnosis framework generalizing from stationary to unknown nonstationary working conditions [[RESS 2023](https://ieeexplore.ieee.org/abstract/document/10121353)]

- Adaptive Class Center Generalization Network: A Sparse Domain-Regressive Framework for Bearing Fault Diagnosis Under Unknown Working Conditions [[TIM 2023](https://ieeexplore.ieee.org/abstract/document/10121353)]

- Relationship transfer domain generalization network for rotating machinery fault diagnosis under different working conditions [[TII 2023](https://ieeexplore.ieee.org/document/10018483)]

- Meta-Learning Based Domain Generalization Framework for Fault Diagnosis with Gradient Aligning and Semantic Matching [[TII 2023](https://ieeexplore.ieee.org/document/10091197)]

- TinyML-enabled edge implementation of transfer learning framework for domain generalization in machine fault diagnosis [[ESWA 2023](https://www.sciencedirect.com/science/article/pii/S0957417422020346)]

- Deep causal factorization network: A novel domain generalization method for cross-machine bearing fault diagnosis [[MSSP 2023](https://www.sciencedirect.com/science/article/abs/pii/S0888327023001358)]

- Domain augmentation generalization network for real-time fault diagnosis under unseen working conditions [[RESS 2023](https://www.sciencedirect.com/science/article/abs/pii/S0951832023001035)]

- Deep mixed domain generalization network for intelligent fault diagnosis under unseen conditions [[TIE 2023](https://ieeexplore.ieee.org/document/10047970)]

- Cross-Domain Augmentation Diagnosis: An Adversarial Domain-Augmented Generalization Method for Fault Diagnosis under Unseen Working Conditions [[RESS 2023](https://www.sciencedirect.com/science/article/pii/S0951832023000868)]

### 2022

- A reliable feature-assisted contrastive generalization net for intelligent fault diagnosis under unseen machines and working conditions [[MSSP 2022](https://www.sciencedirect.com/science/article/pii/S0888327022010792)]

- Domain Transferability-based Deep Domain Generalization Method Towards Actual Fault Diagnosis Scenarios [[TII 2022](https://ieeexplore.ieee.org/document/9905947)]

- A domain generalization network combing invariance and specificity towards real-time intelligent fault diagnosis [[MSSP 2022](https://www.sciencedirect.com/science/article/pii/S0888327022001686)] [[Code](https://github.com/CHAOZHAO-1/DGNIS)]

- Domain Generalization Model of Deep Convolutional Networks Based on SAND-Mask [[algorithms 2022](https://www.mdpi.com/1999-4893/15/6/215)]

- Generalization on Unseen Domains via Model-Agnostic Learning for Intelligent Fault Diagnosis [[TIM 2022](https://ieeexplore.ieee.org/document/9715108)]

- Fault Diagnosis of Rotating Machinery Under Multiple Operating Conditions Generalization: A Representation Gradient Muting Paradigm [[TIM 2022](https://ieeexplore.ieee.org/document/9915363)]
  
- Conditional Contrastive Domain Generalization for Fault Diagnosis [[TIM 2022](https://ieeexplore.ieee.org/document/9721021)][[Code](https://github.com/mohamedr002/CCDG)]

- Sparsity-Constrained Invariant Risk Minimization for Domain Generalization With Application to Machinery Fault Diagnosis Modeling [[TCYB 2022](https://ieeexplore.ieee.org/document/9976035)]

- NTScatNet: An interpretable convolutional neural network for domain generalization diagnosis across different transmission paths [[Measurement 2022](https://www.sciencedirect.com/science/article/pii/S0263224122012374)]

- A Hybrid Matching Network for Fault Diagnosis under Different Working Conditions with Limited Data [[Computational Intelligence and Neuroscience 2022](https://www.hindawi.com/journals/cin/2022/3024590/)]

- Deep Domain Generalization Combining APriori Diagnosis Knowledge Toward Cross-Domain Fault Diagnosis of Rolling Bearing [[TIM 2022](https://ieeexplore.ieee.org/document/9174912)]

- Conditional Adversarial Domain Generalization With a Single Discriminator for Bearing Fault Diagnosis [[TIM 2022](https://ieeexplore.ieee.org/document/9399341)] [[Code](https://github.com/mohamedr002/CCDG)]

- Whitening-Net: A Generalized Network to Diagnose the Faults Among Different Machines and Conditions [[TNNLS 2022](https://ieeexplore.ieee.org/document/9411732)]



### 2021

- Causal Disentanglement: A Generalized Bearing Fault Diagnostic Framework in Continuous Degradation Mode [[TNNLS 2021](https://ieeexplore.ieee.org/document/9664454)]

- A hybrid generalization network for intelligent fault diagnosis of rotating machinery under unseen working conditions [[TIM 2021](https://ieeexplore.ieee.org/document/9452118)]

- Adversarial domain-invariant generalization: a generic domain-regressive framework for bearing fault diagnosis under unseen conditions [[TII 2021](https://ieeexplore.ieee.org/document/9428592)]

### 2020

- Intelligent Fault Identification Based on MultiSource Domain Generalization Towards Actual Diagnosis Scenario [[TIE 2020](https://ieeexplore.ieee.org/document/8643085)]

- Domain generalization in rotating machinery fault diagnostics using deep neural networks [[Neurocomputing 2020](https://www.sciencedirect.com/science/article/pii/S0925231220308092)]

- Learn Generalization Feature via Convolutional Neural Network: A Fault Diagnosis Scheme Toward Unseen Operating Conditions [[IEEE Access 2020](https://ieeexplore.ieee.org/document/9093130)]

### Federated Domain Generalization-based Fault Diagnosis (FedDGFD)
> Multi-souce data are stored in different local clients.
<a name="section-id4"></a>


### 2025

- A Gradient Alignment Federated Domain Generalization Framework for Rotating Machinery Fault Diagnosis [[IOT 2025](https://ieeexplore.ieee.org/abstract/document/10949604)]


- Federated Domain Generalization for Fault Diagnosis: Cross-Client Style Integration and Dual Alignment Representation [[IOT 2025](https://ieeexplore.ieee.org/document/10926881)]

### 2024


- Heterogeneous Federated Learning: Client-side Collaborative Update Inter-Domain Generalization Method for Intelligent Fault Diagnosis
 [[IOT 2024](https://ieeexplore.ieee.org/abstract/document/10742072)][[Code](https://github.com/JC952/P2PCHF)]

- FedITA: A cloud–edge collaboration framework for domain generalization-based federated fault diagnosis of machine-level industrial motors [[AEI 2024](https://www.sciencedirect.com/science/article/pii/S1474034624005019)]

- A blockchain-empowered secure federated domain generalization framework for machinery fault diagnosis [[AEI 2024](https://www.sciencedirect.com/science/article/abs/pii/S147403462400404X)]

- Heterogeneous Federated Domain Generalization Network With Common Representation Learning for Cross-Load Machinery Fault Diagnosis [[TSMC 2024](https://ieeexplore.ieee.org/abstract/document/10571357)][[Code](https://github.com/QinYi-team/HFDGN)]

- Decentralized federated domain generalization with cluster alignment for fault diagnosis [[Control Engineering Practice 2024](https://www.sciencedirect.com/science/article/pii/S0967066124001114?via%3Dihub)]

- Fusing consensus knowledge: A federated learning method for fault diagnosis via privacy-preserving reference under domain shift [[IF 2024](https://www.sciencedirect.com/science/article/pii/S156625352400068X)]

- A federated distillation domain generalization framework for machinery fault diagnosis with data privacy [[EAAI 2024](https://www.sciencedirect.com/science/article/pii/S0952197623019498?casa_token=tI8xLle0uTAAAAAA:G8yUEWhMpz25pJg57bcCgcSk96pKBzrqEyqpkOM_71cPJgeV4HszpOuAASSqHxuB8POGv__p)][[Code](https://github.com/CHAOZHAO-1/FDDG)]
  
### 2023

- Federated domain generalization for intelligent fault diagnosis based on pseudo‑siamese network and robust global model aggregation [[IJMLC 2023](https://link.springer.com/article/10.1007/s13042-023-01934-2)]

- Federated Domain Generalization With Global Robust Model Aggregation Strategy For Bearing Fault Diagnosis [[MST 2023](https://iopscience.iop.org/article/10.1088/1361-6501/ace841/meta)]


- Federated Domain Generalization: A Secure and Robust Framework for Intelligent Fault Diagnosis [[TII 2023]( https://ieeexplore.ieee.org/abstract/document/10196327)][[Code](https://github.com/CHAOZHAO-1/FedDGMC)]
  

- Federated adversarial domain generalization network: A novel machinery fault diagnosis method with data privacy [[KBS 2023](https://www.sciencedirect.com/science/article/pii/S095070512200973X?casa_token=cIa6MEtheM4AAAAA:MPW_GJCNCNQOuFuwA_3Gv8UvXt_PQaG6q7n6E1DijbTWQBwzf5Uk_JfEFduaIokD1sj3o4AJ)]

  
### Semisupervised Domain Generalization-based Fault Diagnosis (SemiDGFD)

> One source domain are labeled and other source domains are unlabeled.
<a name="section-id5"></a>

### 2025

- Domain knowledge guided pseudo-label generation framework for semi-supervised domain generalization fault diagnosis [[AEI 2025](https://www.sciencedirect.com/science/article/pii/S1474034625004331)]

### 2024

- An Auxiliary Branch Semi-supervised Domain Generalization Network for Unseen Working Conditions Bearing Fault Diagnosis [[IEEE SENSOR 2024](https://ieeexplore.ieee.org/abstract/document/10735114)]

- Contrast-Assisted Domain-Specificity-Removal Network for Semi-Supervised Generalization Fault Diagnosis [[TNNLS 2024](https://ieeexplore.ieee.org/document/10495144)]


### 2023

- Domain-invariant feature fusion networks for semi-supervised generalization fault diagnosis [[EAAI 2023]( https://www.sciencedirect.com/science/article/pii/S0952197623013015)]

- Domain fuzzy generalization networks for semi-supervised intelligent fault diagnosis under unseen working conditions [[MSSP 2023]( https://www.sciencedirect.com/science/article/pii/S0888327023004879)]

- Mutual-assistance semisupervised domain generalization network for intelligent fault diagnosis under unseen working conditions [[MSSP 2023](https://www.sciencedirect.com/science/article/pii/S0888327022011426)][[Code](https://github.com/CHAOZHAO-1/MSDGN)]

- A New Adversarial Domain Generalization Network Based on Class Boundary Feature Detection for Bearing Fault Diagnosis [[TIM 2023](https://ieeexplore.ieee.org/document/9745907)]

### 2020

- Deep Semisupervised Domain Generalization Network for Rotary Machinery Fault Diagnosis Under Variable Speed [[TIM 2020](https://ieeexplore.ieee.org/document/9088148)]



### Open Set Domain Generalization-based Fault Diagnosis (OSDGFD)
> Class space among multiple source domains and unseen target domain is different.
<a name="section-id6"></a>


### 2025

- Dual-contrastive Multi-view Graph Attention Network for Industrial Fault Diagnosis under Domain and Label Shift [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10891912)]


- Auxiliary-feature-embedded causality-inspired dynamic penalty networks for open-set domain generalization diagnosis scenario [[AEI 2025](https://www.sciencedirect.com/science/article/abs/pii/S1474034625001132)]


- Adaptive reconstruct feature difference network for open set domain generalization fault diagnosis [[EAAI 2025](https://www.sciencedirect.com/science/article/pii/S0952197624020542)]

- A self-improving fault diagnosis method for intershaft bearings with missing training samples [[MSSP 2025](https://www.sciencedirect.com/science/article/pii/S0888327024011592)]


### 2024

- A novel domain-private-suppress meta-recognition network based universal domain generalization for machinery fault diagnosis [[KBS 2024](https://www.sciencedirect.com/science/article/abs/pii/S0950705124014096)]


- Open-set domain generalization for fault diagnosis through data augmentation and a dual-level weighted mechanism [[AEI 2024](https://www.sciencedirect.com/science/article/abs/pii/S1474034624003513)]

- Curriculum learning-based domain generalization for cross-domain fault diagnosis with category shift [[MSSP 2024](https://www.sciencedirect.com/science/article/pii/S0888327024001936)]

### 2023

- A Novel Multidomain Contrastive-Coding-Based Open-Set Domain Generalization Framework for Machinery Fault Diagnosis [[TII 2023](https://ieeexplore.ieee.org/abstract/document/10382502?casa_token=FxKIZnqwoqgAAAAA:vvJI3TjUhHtASvVmDjK8jIGhvt0j7RO1wy0uL-kmiFSapnJOEkcm8YZJA3UpeZsnpUAeAhE)]

  
- A Customized Meta-Learning Framework for Diagnosing New Faults From Unseen Working Conditions With Few Labeled Data [[IEEE/ASME MEC 2023](https://ieeexplore.ieee.org/abstract/document/10214410?casa_token=GWKheX--CFQAAAAA:5n_rqYpoPNHdBYoSqSJJRrTiMf2jyMyO1syc5kEauCASvk9OaUXbNILADKzb-LeFuOTKidk)]

### 2022

- Adaptive open set domain generalization network: Learning to diagnose unknown faults under unknown working conditions [[RESS 2022](https://www.sciencedirect.com/science/article/pii/S0951832022003064)][[Code](https://github.com/CHAOZHAO-1/AOSDGN)]


## Imbalanced Domain Generalization-based Fault Diagnosis (IDGFD)
> Sample number for differnt classes in source domains are different.
<a name="section-id7"></a>



### 2025

- Imbalanced multidomain generalization fault diagnosis based on prototype-guided supervised contrastive learning with dynamic temperature modulation [[SHM 2025](https://journals.sagepub.com/doi/abs/10.1177/14759217251332517)]


- DRSC: Dual-Reweighted Siamese Contrastive Learning Network for Cross-Domain Rotating Machinery Fault Diagnosis With Multi-Source Domain Imbalanced Data [[IoT 2025](https://ieeexplore.ieee.org/abstract/document/10944708)]

- Imbalanced multi-domain generalization method for electro-mechanical actuator fault diagnosis under variable working conditions [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10938387)]


### 2024

- Adaptive Variational Sampling-embedded Domain Generalization Network for fault diagnosis with intra-inter-domain class imbalance[[RESS 2024](https://www.sciencedirect.com/science/article/abs/pii/S0951832024007786)]

- A two-stage learning framework for imbalanced semi-supervised domain generalization fault diagnosis under unknown operating conditions [[AEI 2024](https://www.sciencedirect.com/science/article/abs/pii/S1474034624005263)]



- Multi-domain Class-imbalance Generalization with Fault Relationship-induced Augmentation for Intelligent Fault Diagnosis [[TIM 2024](https://ieeexplore.ieee.org/document/10606303)]

- Long-tailed multi-domain generalization for fault diagnosis of rotating machinery under variable operating conditions [[SHM 2024](https://journals.sagepub.com/doi/10.1177/14759217241256690)]


### 2023

- Imbalanced Domain Generalization via Semantic-Discriminative Augmentation for Intelligent Fault Diagnosis [[AEI 2023]( https://www.sciencedirect.com/science/article/pii/S1474034623003907?via%3Dihub)][[Code](https://github.com/CHAOZHAO-1/SDAGN)]




## Single Domain Generalization-based Fault Diagnosis (SDGFD)
> source samples are only from a single domain.
<a name="section-id8"></a>


### 2025 



-Multi-style adversarial variational self-distillation in randomized domains for single-domain generalized fault diagnosis [[CII 2025](https://www.sciencedirect.com/science/article/pii/S0166361525000843)]


-A Generic Single-Source Domain Generalization Framework for Fault Diagnosis via Wavelet Packet Augmentation and Pseudo-Domain Generation [[IoT 2025](https://ieeexplore.ieee.org/abstract/document/11015920)]


- Addressing unknown faults diagnosis of transport ship propellers system based on adaptive evolutionary reconstruction metric network [[AEI 2025](https://www.sciencedirect.com/science/article/abs/pii/S1474034625001806)]



- Fault Diagnosis in Rolling Bearings Using Multi-Gaussian Attention and Covariance Loss for Single Domain Generalization [[TIM 2025](https://ieeexplore.ieee.org/abstract/document/10902562)]


- Dual adversarial and contrastive network for single-source domain generalization in fault diagnosis [[AEI 2025](https://www.sciencedirect.com/science/article/pii/S1474034625000333)]

- SDCGAN: A CycleGAN-Based Single-Domain Generalization Method for Mechanical Fault Diagnosis [[RESS 2025](https://www.sciencedirect.com/science/article/pii/S0951832025000572)]

### 2024 

- Uncertainty-guided adversarial augmented domain networks for single domain generalization fault diagnosis [[Measurement 2024](https://www.sciencedirect.com/science/article/abs/pii/S0263224124015598)]

- Prior knowledge embedding convolutional autoencoder: A single-source domain generalized fault diagnosis framework under small samples [[CII 2024](https://www.sciencedirect.com/science/article/abs/pii/S0166361524000976)][[Code](https://github.com/John-520/PKECA)]

- Simulation data-driven attention fusion network with multi-similarity metric: A single-domain generalization diagnostic method for tie rod bolt loosening of a rod-fastening rotor system [[MEASUREMENT 2024](https://www.sciencedirect.com/science/article/abs/pii/S0263224124014507)]

- Single imbalanced domain generalization network for intelligent fault diagnosis of compressors in HVAC systems under unseen working conditions [[Energy & Buildings  2024](https://www.sciencedirect.com/science/article/pii/S0378778824003086?via%3Dihub)]

- Single Source Cross-Domain Bearing Fault  Diagnosis via Multi-Pseudo Domain Augmented  Adversarial Domain-Invariant Learning [[JIOT 2024](https://ieeexplore.ieee.org/abstract/document/10577994)]

- Single domain generalization method based on anti-causal learning for rotating machinery fault diagnosis [[RESS 2024](https://www.sciencedirect.com/science/article/pii/S0951832024003247)]

- DP2Net: A discontinuous physical property-constrained single-source domain generalization network for tool wear state recognition [[MSSP 2024](https://www.sciencedirect.com/science/article/pii/S0888327024003194)]

- Gradient-based domain-augmented meta-learning single-domain generalization for fault diagnosis under variable operating conditions [[SHM 2024](https://journals.sagepub.com/doi/full/10.1177/14759217241230129)]

- HmmSeNet: A Novel Single Domain Generalization Equipment Fault Diagnosis Under Unknown Working Speed Using Histogram Matching Mixup[[TII 2024](https://ieeexplore.ieee.org/abstract/document/10417861/)]

- Support-Sample-Assisted Domain Generalization via Attacks and Defenses: Concepts, Algorithms, and Applications to Pipeline Fault Diagnosis [[TII 2024](https://ieeexplore.ieee.org/abstract/document/10384769?casa_token=dVxouWGvpSYAAAAA:PfiXfJAyfigutyUOLfRvn_OHFO_9YL8IOEl3Kd_rHodFFSEbfYJ4h9PGh5vYKBw0JkceMfw)]

### 2023

- Single domain generalizable and physically interpretable bearing fault diagnosis for unseen working conditions [[ESA 2023](https://www.sciencedirect.com/science/article/abs/pii/S0957417423029573)]

- Multi-scale style generative and adversarial contrastive networks for single domain generalization fault diagnosis [[RESS 2023](https://www.sciencedirect.com/science/article/pii/S0951832023007937?casa_token=jbSOPupOqNEAAAAA:h_9_4oxKe-zEoM0_zHNFt-b7abKR6OTdDRh-C9hEM0XWUZfj6h9DTJM_wJT-kOOITvEcRKwD)]

- An Adversarial Single-Domain Generalization Network for Fault Diagnosis of Wind Turbine Gearboxes [[J MAR SCI ENG 2023](https://www.mdpi.com/2077-1312/11/12/2384)]

### 2022

- Adversarial Mutual Information-Guided Single Domain Generalization Network for Intelligent Fault Diagnosis [[TII 2022](https://ieeexplore.ieee.org/document/9774938)]


# Data
> There are eight open-source dataset and two self-collected dataset for research of domain generalization-based fault diagnosis.
<a name="section-id9"></a>


| Index 	| Year 	| Dataset Name 	| Component 	| Generation                   	| Working Condition           	| Original data link 	| Alternate data Link 	|
|-------	|------	|--------------	|-----------	|------------------------------	|-----------------------------	|--------------------	|---------------------	|
| 1     	| 2006 	| IMS          	| bearing   	| Run to failure               	| Single working condition    	|[[data link](https://www.nasa.gov/intelligent-systems-division)]                    	| [[data link](https://pan.quark.cn/s/003c8060617d)]                    	|
| 2     	| 2013 	| JNU          	| bearing   	| artifical                    	| Multiple working conditions 	|   /                 	|              [[data link](https://pan.quark.cn/s/b2344c54c6d7)]            	|
| 3     	| 2015 	| CWRU         	| bearing   	| artifical                    	| Multiple working conditions 	|[[data link](https://csegroups.case.edu/bearingdatacenter/pages/welcome-case-western-reserve-university-bearing-data-center-website)]                    	|        [[data link](https://pan.quark.cn/s/2b0ceb12ab5a)]                 	|
| 4     	| 2016 	| PU           	| bearing   	| artifical and run to failure 	| Multiple working conditions 	|[[data link](https://mb.uni-paderborn.de/kat/forschung/datacenter/bearing-datacenter/)]                    	|                   [[data link](https://pan.quark.cn/s/98940eefefb2)]    	|
| 5     	| 2016 	| SCP          	| bearing   	| artifical                    	| Single working condition    	|      /              	|         [[data link](https://pan.quark.cn/s/6ccea2154a06)]                	| 
| 6     	| 2018 	| XJTU         	| bearing   	| Run to failure               	| Multiple working conditions 	|[[data link](http://biaowang.tech/xjtu-sy-bearing-datasets/)]                 	|        [[data link](https://pan.quark.cn/s/073484fd0bb0)]                     	|
| 7     	| 2018 	| PHM09        	| gearbox   	| artifical                    	| Multiple working conditions 	|   /                 	|        [[data link](https://pan.quark.cn/s/88180e4fccde)]               	|
| 8     	| 2021 	| LW           	| bearing   	| artifical                    	| Multiple working conditions 	|[[data link](https://github.com/ChaoyingYang/SuperGraph)]               	|        [[data link](https://pan.quark.cn/s/7e881548f5a1)]                       	|
| 9     	| 2022 	| HUSTbearing  	| bearing   	| artifical                    	| Multiple working conditions 	|     /               	|         [[data link](https://github.com/CHAOZHAO-1/HUSTbearing-dataset)]               	|       
| 10    	| 2022 	| HUSTgearbox  	| gearbox    	| artifical                    	| Multiple working conditions 	|    /                	|         [[data link](https://github.com/CHAOZHAO-1/HUSTgearbox-dataset)]              	|

# Code for Benchmark
<a name="section-id10"></a>

> Our benchmark code is released at   [[Code link](https://github.com/CHAOZHAO-1/Domain-generalization-fault-diagnosis-benchmark)]  


> Another benchmark code is released at  [[Code link](https://github.com/ShaneSpace/DGFDBenchmark)]  




# Code for Method Paper
<a name="section-id13"></a>
|  Title  |   Journal  |   Date   |   Code   |   topic   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|[**Conditional Contrastive Domain Generalization For Fault Diagnosis**](https://ieeexplore.ieee.org/abstract/document/9721021) <br> | TIM | 2022 | [Github](https://github.com/mohamedr002/CCDG) | DGFD |
|[**A domain generalization network combing invariance and specificity towards real-time intelligent fault diagnosis**](https://www.sciencedirect.com/science/article/pii/S0888327022001686) <br> | MSSP| 2022 | [Github](https://github.com/CHAOZHAO-1/DGNIS) | DGFD |
|[**Conditional-Adversarial-Domain-Generalization-with-Single-Discriminator**](https://ieeexplore.ieee.org/abstract/document/9399341/) <br> | TIM| 2022 | [Github](https://github.com/hectorLop/Conditional-Adversarial-Domain-Generalization-with-Single-Discriminator) | DGFD |
|[**A federated distillation domain generalization framework for machinery fault diagnosis with data privacy**](https://www.sciencedirect.com/science/article/pii/S0952197623019498) <br> | EAAI | 2024 | [Github](https://github.com/CHAOZHAO-1/FDDG) | FedDGFD |
|[**Federated domain generalization: A secure and robust framework for intelligent fault diagnosis**](https://ieeexplore.ieee.org/abstract/document/10196327) <br> | TII | 2023 | [Github](https://github.com/CHAOZHAO-1/FedDGMC) | FedDGFD |
|[**Imbalanced domain generalization via Semantic-Discriminative augmentation for intelligent fault diagnosis**](https://www.sciencedirect.com/science/article/pii/S1474034623003907) <br> | AEI | 2024 | [Github](https://github.com/CHAOZHAO-1/SDAGN) | IDGFD |
|[**Mutual-assistance semisupervised domain generalization network for intelligent fault diagnosis under unseen working conditions**](https://www.sciencedirect.com/science/article/pii/S0888327022011426) <br> | MSSP | 2023 | [Github](https://github.com/CHAOZHAO-1/MSDGN) | SemiDGFD |
|[**Adaptive open set domain generalization network: Learning to diagnose unknown faults under unknown working conditions**](https://www.sciencedirect.com/science/article/pii/S0951832022003064) <br> | RESS | 2022 | [Github](https://github.com/CHAOZHAO-1/AOSDGN) | OSDGFD |



# Talk
<a name="section-id14"></a>


- [苏州大学沈长青教授：从域适应到域泛化：人工智能驱动的故障诊断模型探索](https://www.bilibili.com/video/BV1V34y1q758/?spm_id_from=333.337.search-card.all.click&vd_source=ec846a76720b6da306d5919873954ab5)


# Domain Generalization-based Fault Prognosis

<a name="section-id11"></a>


### 2025


-Towards prognostic generalization: a domain conditional invariance and specificity disentanglement network for remaining useful life prediction [[Measurement 2025](https://www.sciencedirect.com/science/article/pii/S0263224124023364?casa_token=Iy9NcEz_fPAAAAAA:HMb7ec267uBNaEqhimmpzg4rbe17H_pIf39v41GWhpDN247vl04ZomLjMYStwI-nBthzUabong)]

- Contrastive domain-invariant generalization for remaining useful life prediction under diverse conditions and fault modes [[RESS 2025](https://www.sciencedirect.com/science/article/pii/S0951832024006069?casa_token=56rN4xmGmooAAAAA:yUWPSQogKbc_uAQ7nU-nKDmSSC1NmRSlT4974jC87NIeDxaoi4CpLVJW76EogdfLXLzKfD9vPA)]

- A generalized network with domain invariance and specificity representation for bearing remaining useful life prediction under unknown conditions [[KBS 2025](https://www.sciencedirect.com/science/article/pii/S0950705124015491?casa_token=YkE_7QWZliEAAAAA:IOPzRfpg-fSmtuYOXLUZBRvG3XLbtlsd2TYTx5uOC6v9M1Dt19hA6Jx4t1v6v8it5BLO5Tc62w)]




### 2024

- Towards prognostic generalization: a domain conditional invariance and specificity disentanglement network for remaining useful life prediction [[JMS 2024](https://link.springer.com/article/10.1007/s10845-023-02215-z)]

- Domain Invariant and Consistent Ordinal Representation Learning for Remaining Useful Life Prediction of Bearings [[TII 2024](https://ieeexplore.ieee.org/abstract/document/10680885)]

- Domain generalization for rotating machinery real-time remaining useful life prediction via multi-domain orthogonal degradation feature exploration [[MSSP 2024](https://www.sciencedirect.com/science/article/abs/pii/S0888327024008227)]

- Remaining useful life prediction of machinery based on performanceevaluation and online cross-domain health indicator under unknownworking conditions [[JMS 2024](https://www.sciencedirect.com/science/article/pii/S0278612524001328?casa_token=RFcpI7YJdp4AAAAA:oom_6YMx4BUDEZeAon2wrLXhtEb2xQnwkCf2ErgrKpD5nY89_Zt6ASkfA8KGEu2jkPm4BvP95Blg)]

- A Life-Stage Domain Aware Network for Bearing Health Prognosis Under Unseen Temporal Distribution Shift [[TIM 2024](https://ieeexplore.ieee.org/abstract/document/10443638)]

- Uncertainty-Weighted Domain Generalization for Remaining Useful Life Prediction of Rolling Bearings under Unseen Conditions [[IEEE Sensors 2024](https://ieeexplore.ieee.org/abstract/document/10444662)]

- An Optimal-Subdomain Generalization Method for Remaining Useful Life Prediction of Machinery Under Time-Varying Operation Conditions [[TII 2024](https://ieeexplore.ieee.org/abstract/document/10376342)]

### 2023

- Domain generalization via adversarial out-domain augmentation for remaining useful life prediction ofbearings under unseen conditions [[KBS 2023](https://www.sciencedirect.com/science/article/pii/S0950705122012953?casa_token=KeaYUYWrSOEAAAAA:sTbCUiXyakT3vc_gPsb3CDjS6hMhjL2dtQPf4UTZURoxtdHkuWl6uJ4tVqEKbVPClfEq9c2n)]

- Towards prognostic generalization: a domain conditional invariance and specificity disentanglement network for remaining useful life prediction [[JMS 2023]( https://link.springer.com/article/10.1007/s10845-023-02215-z)]

### 2022  

- Multi-source domain generalization for degradation monitoring of journal bearings under unseen conditions [[RESS 2022]( https://www.sciencedirect.com/science/article/pii/S0951832022005816?casa_token=88osNTMXjxAAAAAA:m5J55mbQMKDw5UhdtEhXsApiIi8oITCY7lWVM-9H9JGP4uf-gzPX_UFaJzzygFv4t1lRuFF2)]

- Meta domain generalization for smart manufacturing: Tool wear prediction with small data [[JMS 2022]( https://www.sciencedirect.com/science/article/pii/S0278612521002582?casa_token=OXSZPT33GkoAAAAA:M0JFmcB7vITOe80UnmE_jxlMKWGnQOnoq5TGamDxJORjh77NHL-31cl-_LJ7MGmmLcwY-2N9)]
  
- Health Assessment of Rotating Equipment With Unseen Conditions Using Adversarial Domain Generalization Toward Self-Supervised Regularization Learning [[IEEE/ASME MEC 2022]( https://ieeexplore.ieee.org/abstract/document/9759507?casa_token=-aIFB7D8tfwAAAAA:jejqlSpb1dvVY_YIL62zBkjBNGZQ8Qoz-PTpYiZyxlYFsKuqETU10mRNR4H4vwsumM-fh-I)]




# Contact

If you have any problem, please feel free to contact me.

Name: Chao Zhao

Email address: zhaochao0612@gmail.com


# BibTex Citation

If you find this paper and repository useful, please cite our paper☺️.

```
@article{Zhao2024domain,
  title={Domain Generalization for Cross-Domain Fault Diagnosis: an Application-oriented Perspective and a Benchmark Study},
  author={Zhao, Chao and Zio, Enrico and Shen, Weiming},
  journal={Reliability Engineering & System Safety},
  pages={109964},
  year={2024}
}
```
# Related Projects
<a name="section-id12"></a>
- We collect all open source mechanical failure datasets [[Link](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset)]
  
- We have sorted out the multi-modal-based fault diagnosis, including data, papers, codes and so on [[Link](https://github.com/CHAOZHAO-1/Awsome-Multi-modal-based-PHM)]
