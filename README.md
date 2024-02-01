# Domain-generalization-for-fault-diagnosis-and-prognosis （updating）领域泛化方法用于故障诊断和预测 (持续更新中)

（Updated as of 27 January 2024）

This is a repository about **Domain Generalization for PHM**, including papers, code, datasets etc. 

We will continue to update this repository and hope this repository can benefit your research.

# Contents
- [Papers for fault diagnosis](#papers)
-   - [Survey](#papers)
-   - [Regular paper](#papers)

-   -   - [Homogeneous domain generalization-based fault diagnosis](#survey)
-   -   - [Federated domain generalization-based fault diagnosis](#survey)
-   -   - [Semisupervised domain generalization-based fault diagnosis](#survey)
-   -   - [Open set domain generalization-based fault diagnosis](#survey)
-   -   - [Imbalanced domain generalization-based fault diagnosis](#survey)
-   -   - [Single domain generalization-based fault diagnosis](#survey)
  
- [Data](#data)

- [Code](#code)

- [Papers for prognosis](#papers)

- [Related project](#papers)

# Papers
> We list papers, implementation code (the unofficial code is marked with *), etc, in the order of year and from journals to conferences. 

## Survey （综述）

- Domain Generalization for Cross-Domain Fault Diagnosis: an Application-oriented Perspective and a Benchmark Study [[RESS 2024](https://www.sciencedirect.com/science/article/abs/pii/S0951832024000395?via%3Dihub)]

- An Application-oriented Perspective of Domain Generalization for Cross-Domain Fault Diagnosis [[IEEE CSCWD 2023](https://ieeexplore.ieee.org/document/10152676)]


### Homogeneous domain generalization-based fault diagnosis (HDGFD)

> Class space between mutiple source domains and unseen target domain is same.



- Stacked maximum independence autoencoders: A domain generalization approach for fault diagnosis under various working conditions [[MSSP 2024](https://www.sciencedirect.com/science/article/pii/S0888327023009433?casa_token=TPEkc-h1NxcAAAAA:CTnDvBy8VIOO-06cMg3z698bU0LvCCJx8H0OVGL1Qn55a8LbepeEsBso8A_VSF9CpoMXkF4f)]

- Causal explaining guided domain generalization for rotating machinery intelligent fault diagnosis [[ESA 2024](https://www.sciencedirect.com/science/article/pii/S0957417423033080?casa_token=jGBA5IXkaBoAAAAA:6cbWsTf0o2mSPLJN7QruV5wO8fzPGvuJWypOcgn1v9zEOEFqqhNraUmWm3TF8O5BkaVLnaX2)]

- Task-Generalization-Based Graph Convolutional Network for Fault Diagnosis of Rod-Fastened Rotor System [[TII 2023](https://ieeexplore.ieee.org/abstract/document/10309830?casa_token=fG_kV9wKc4gAAAAA:rZIOZtNq7dMN_bd9U6w7SAWfSEc34tCuYtoVw_CkzsdqEm46XOSZadthe4CbIpjymucxx-w)]

- VIT-GADG: A Generative Domain - Generalized Framework for Chillers Fault Diagnosis under Unseen Working Conditions [[TIM 2023](https://ieeexplore.ieee.org/abstract/document/10216370)]

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

- A reliable feature-assisted contrastive generalization net for intelligent fault diagnosis under unseen machines and working conditions [[MSSP 2022](https://www.sciencedirect.com/science/article/pii/S0888327022010792)]

- Domain Transferability-based Deep Domain Generalization Method Towards Actual Fault Diagnosis Scenarios [[TII 2022](https://ieeexplore.ieee.org/document/9905947)]

- A domain generalization network combing invariance and specificity towards real-time intelligent fault diagnosis [[MSSP 2022](https://www.sciencedirect.com/science/article/pii/S0888327022001686)]

- Domain Generalization Model of Deep Convolutional Networks Based on SAND-Mask [[algorithms 2022](https://www.mdpi.com/1999-4893/15/6/215)]

- Generalization on Unseen Domains via Model-Agnostic Learning for Intelligent Fault Diagnosis [[TIM 2022](https://ieeexplore.ieee.org/document/9715108)]

- Fault Diagnosis of Rotating Machinery Under Multiple Operating Conditions Generalization: A Representation Gradient Muting Paradigm [[TIM 2022](https://ieeexplore.ieee.org/document/9915363)]
  
- Conditional Contrastive Domain Generalization for Fault Diagnosis [[TIM 2022](https://ieeexplore.ieee.org/document/9721021)][[Code](https://github.com/mohamedr002/CCDG)]

- Sparsity-Constrained Invariant Risk Minimization for Domain Generalization With Application to Machinery Fault Diagnosis Modeling [[TCYB 2022](https://ieeexplore.ieee.org/document/9976035)]

- NTScatNet: An interpretable convolutional neural network for domain generalization diagnosis across different transmission paths [[Measurement 2022](https://www.sciencedirect.com/science/article/pii/S0263224122012374)]

- A Hybrid Matching Network for Fault Diagnosis under Different Working Conditions with Limited Data [[Computational Intelligence and Neuroscience 2022](https://www.hindawi.com/journals/cin/2022/3024590/)]

- Deep Domain Generalization Combining APriori Diagnosis Knowledge Toward Cross-Domain Fault Diagnosis of Rolling Bearing [[TIM 2022](https://ieeexplore.ieee.org/document/9174912)]

- Conditional Adversarial Domain Generalization With a Single Discriminator for Bearing Fault Diagnosis [[TIM 2022](https://ieeexplore.ieee.org/document/9399341)]

- Whitening-Net: A Generalized Network to Diagnose the Faults Among Different Machines and Conditions [[TNNLS 2022](https://ieeexplore.ieee.org/document/9411732)]

- Causal Disentanglement: A Generalized Bearing Fault Diagnostic Framework in Continuous Degradation Mode [[TNNLS 2021](https://ieeexplore.ieee.org/document/9664454)]

- A hybrid generalization network for intelligent fault diagnosis of rotating machinery under unseen working conditions [[TIM 2021](https://ieeexplore.ieee.org/document/9452118)]

- Adversarial domain-invariant generalization: a generic domain-regressive framework for bearing fault diagnosis under unseen conditions [[TII 2021](https://ieeexplore.ieee.org/document/9428592)]


- Intelligent Fault Identification Based on MultiSource Domain Generalization Towards Actual Diagnosis Scenario [[TIE 2020](https://ieeexplore.ieee.org/document/8643085)]

- Domain generalization in rotating machinery fault diagnostics using deep neural networks [[Neurocomputing 2020](https://www.sciencedirect.com/science/article/pii/S0925231220308092)]

- Learn Generalization Feature via Convolutional Neural Network: A Fault Diagnosis Scheme Toward Unseen Operating Conditions [[IEEE Access 2020](https://ieeexplore.ieee.org/document/9093130)]

### Federated domain generalization-based fault diagnosis (FedDGFD)
> Data are stored in different local clients.

- A federated distillation domain generalization framework for machinery fault diagnosis with data privacy [[EAAI 2024](https://www.sciencedirect.com/science/article/pii/S0952197623019498?casa_token=tI8xLle0uTAAAAAA:G8yUEWhMpz25pJg57bcCgcSk96pKBzrqEyqpkOM_71cPJgeV4HszpOuAASSqHxuB8POGv__p)]
  

- Federated domain generalization for intelligent fault diagnosis based on pseudo‑siamese network and robust global model aggregation [[IJMLC 2023](https://link.springer.com/article/10.1007/s13042-023-01934-2)]

- Federated Domain Generalization With Global Robust Model Aggregation Strategy For Bearing Fault Diagnosis [[MST 2023](https://iopscience.iop.org/article/10.1088/1361-6501/ace841/meta)]


- Federated Domain Generalization: A Secure and Robust Framework for Intelligent Fault Diagnosis [[TII 2023]( https://ieeexplore.ieee.org/abstract/document/10196327)]

- Federated adversarial domain generalization network: A novel machinery fault diagnosis method with data privacy [[KBS 2023](https://www.sciencedirect.com/science/article/pii/S095070512200973X?casa_token=cIa6MEtheM4AAAAA:MPW_GJCNCNQOuFuwA_3Gv8UvXt_PQaG6q7n6E1DijbTWQBwzf5Uk_JfEFduaIokD1sj3o4AJ)]

  
### Semisupervised domain generalization-based fault diagnosis (SemiDGFD)
> One source domain are labeled and other source domains are unlabeled.

- Domain-invariant feature fusion networks for semi-supervised generalization fault diagnosis [[EAAI 2023]( https://www.sciencedirect.com/science/article/pii/S0952197623013015)]

- Domain fuzzy generalization networks for semi-supervised intelligent fault diagnosis under unseen working conditions [[MSSP 2023]( https://www.sciencedirect.com/science/article/pii/S0888327023004879)]

- Mutual-assistance semisupervised domain generalization network for intelligent fault diagnosis under unseen working conditions [[MSSP 2023](https://www.sciencedirect.com/science/article/pii/S0888327022011426)]

- A New Adversarial Domain Generalization Network Based on Class Boundary Feature Detection for Bearing Fault Diagnosis [[TIM 2023](https://ieeexplore.ieee.org/document/9745907)]

- Deep Semisupervised Domain Generalization Network for Rotary Machinery Fault Diagnosis Under Variable Speed [[TIM 2020](https://ieeexplore.ieee.org/document/9088148)]

### Open set domain generalization-based fault diagnosis (OSDGFD)
> Class space among multiple source domains and unseen target domain is different.

- A Novel Multidomain Contrastive-Coding-Based Open-Set Domain Generalization Framework for Machinery Fault Diagnosis [[TII 2023](https://ieeexplore.ieee.org/abstract/document/10382502?casa_token=FxKIZnqwoqgAAAAA:vvJI3TjUhHtASvVmDjK8jIGhvt0j7RO1wy0uL-kmiFSapnJOEkcm8YZJA3UpeZsnpUAeAhE)]

  
- A Customized Meta-Learning Framework for Diagnosing New Faults From Unseen Working Conditions With Few Labeled Data [[IEEE/ASME MEC 2023](https://ieeexplore.ieee.org/abstract/document/10214410?casa_token=GWKheX--CFQAAAAA:5n_rqYpoPNHdBYoSqSJJRrTiMf2jyMyO1syc5kEauCASvk9OaUXbNILADKzb-LeFuOTKidk)]

- Adaptive open set domain generalization network: Learning to diagnose unknown faults under unknown working conditions [[RESS 2022](https://ieeexplore.ieee.org/abstract/document/10214410?casa_token=GWKheX--CFQAAAAA:5n_rqYpoPNHdBYoSqSJJRrTiMf2jyMyO1syc5kEauCASvk9OaUXbNILADKzb-LeFuOTKidk)]


## Imbalanced domain generalization-based fault diagnosis (IDGFD)
> Sample number for differnt class in source domains are different.

- Imbalanced Domain Generalization via Semantic-Discriminative Augmentation for Intelligent Fault Diagnosis [[AEI 2023]( https://www.sciencedirect.com/science/article/pii/S1474034623003907?via%3Dihub)]

## Single domain generalization-based fault diagnosis (SDGFD)
> source samples are only from a single domain.

- Support-Sample-Assisted Domain Generalization via Attacks and Defenses: Concepts, Algorithms, and Applications to Pipeline Fault Diagnosis [[TII 2024](https://ieeexplore.ieee.org/abstract/document/10384769?casa_token=dVxouWGvpSYAAAAA:PfiXfJAyfigutyUOLfRvn_OHFO_9YL8IOEl3Kd_rHodFFSEbfYJ4h9PGh5vYKBw0JkceMfw)]

- Single domain generalizable and physically interpretable bearing fault diagnosis for unseen working conditions [[ESA 2023](https://www.sciencedirect.com/science/article/abs/pii/S0957417423029573)]

- Multi-scale style generative and adversarial contrastive networks for single domain generalization fault diagnosis [[RESS 2023](https://www.sciencedirect.com/science/article/pii/S0951832023007937?casa_token=jbSOPupOqNEAAAAA:h_9_4oxKe-zEoM0_zHNFt-b7abKR6OTdDRh-C9hEM0XWUZfj6h9DTJM_wJT-kOOITvEcRKwD)]

- An Adversarial Single-Domain Generalization Network for Fault Diagnosis of Wind Turbine Gearboxes [[J MAR SCI ENG 2023](https://www.mdpi.com/2077-1312/11/12/2384)]

- Adversarial Mutual Information-Guided Single Domain Generalization Network for Intelligent Fault Diagnosis [[TII 2022](https://ieeexplore.ieee.org/document/9774938)]

# Data
> There are eighet open-source dataset and two self-collected dataset for research of domain generalization-based fault diagnosis.



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
| 9     	| 2022 	| HUSTbearing  	| bearing   	| artifical                    	| Multiple working conditions 	|     /               	|         [[data link](https://pan.quark.cn/s/9b5740119910)]               	|       
| 10    	| 2022 	| HUSTgearbox  	| gearbox    	| artifical                    	| Multiple working conditions 	|    /                	|         [[data link](https://pan.quark.cn/s/a23f59edfd3a)]              	|

# Code

> Our code is released at   [[Code link](https://github.com/CHAOZHAO-1/Domain-generalization-fault-diagnosis-benchmark)]   

# Domain generalization-based fault prognosis


- Domain generalization via adversarial out-domain augmentation for remaining useful life prediction ofbearings under unseen conditions [[KBS 2023](https://www.sciencedirect.com/science/article/pii/S0950705122012953?casa_token=KeaYUYWrSOEAAAAA:sTbCUiXyakT3vc_gPsb3CDjS6hMhjL2dtQPf4UTZURoxtdHkuWl6uJ4tVqEKbVPClfEq9c2n)]

- Towards prognostic generalization: a domain conditional invariance and specificity disentanglement network for remaining useful life prediction [[JMS 2023]( https://link.springer.com/article/10.1007/s10845-023-02215-z)]
  
- Multi-source domain generalization for degradation monitoring of journal bearings under unseen conditions [[RESS 2022]( https://www.sciencedirect.com/science/article/pii/S0951832022005816?casa_token=88osNTMXjxAAAAAA:m5J55mbQMKDw5UhdtEhXsApiIi8oITCY7lWVM-9H9JGP4uf-gzPX_UFaJzzygFv4t1lRuFF2)]

- Meta domain generalization for smart manufacturing: Tool wear prediction with small data [[JMS 2022]( https://www.sciencedirect.com/science/article/pii/S0278612521002582?casa_token=OXSZPT33GkoAAAAA:M0JFmcB7vITOe80UnmE_jxlMKWGnQOnoq5TGamDxJORjh77NHL-31cl-_LJ7MGmmLcwY-2N9)]
  
- Health Assessment of Rotating Equipment With Unseen Conditions Using Adversarial Domain Generalization Toward Self-Supervised Regularization Learning [[IEEE/ASME MEC 2022]( https://ieeexplore.ieee.org/abstract/document/9759507?casa_token=-aIFB7D8tfwAAAAA:jejqlSpb1dvVY_YIL62zBkjBNGZQ8Qoz-PTpYiZyxlYFsKuqETU10mRNR4H4vwsumM-fh-I)]


# Related projects

- We collate all open source mechanical failure datasets [[Link](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset)]
  
- We have sorted out the molti-modal-based fault diagnosis, including data, papers, codes and so on [[Link](https://github.com/CHAOZHAO-1/Awsome-Multi-modal-based-PHM)]

# Contact

If you have any problem, please feel free to contact me.

Name: Chao Zhao

Email address: zhaochao734@hust.edu.cn


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
