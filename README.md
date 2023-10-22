# Awesome Physical Adversarial Examples [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repo collects papers about **Physical Adversarial Examples** for anyone who wants to do research on it. We are continuously improving the project. Welcome to PR the works (papers, repositories) that are missed by the repo. Special thanks to the [**Researchers**](#Contributors) who have contributed to this project!



## Table of Contents

- [Surveys](#Surveys)
- [Papers-Physical Adversarial Attacks](#Papers-Physical-Adversarial-Attacks)
  - [Manufacturing Oriented Attacks](#Manufacturing-Oriented-Attacks)
    - [Touchable Attacks](#Touchable-Attacks)
    - [Untouchable Attacks](#Untouchable-Attacks)
  - [Resampling Oriented Attacks](#Resampling-Oriented-Attacks)
    - [Environment-oriented Attacks](#Environment-oriented-Attacks)
    - [Sampler-oriented Attacks](#Sampler-oriented-Attacks)
  - [Other PAEs](#Other-PAEs)
    - [The Natural Physical Adversarial Attacks](#The-Natural-Physical-Adversarial-Attacks)
    - [The Transferable Physical Adversarial Attacks](#The-Transferable-Physical-Adversarial-Attacks)
    - [The Generalized Physical Adversarial Attacks](#The-Generalized-Physical-Adversarial-Attacks)
- [Papers-Adversarial Defense Methods](#Papers-Adversarial-Defense-Methods)
  - [Data-end Defense](#Data-end-Defense)
    - [Adversarial Detecting](#Adversarial-Detecting)
    - [Adversarial Denoising](#Adversarial-Denoising)
    - [Adversarial Prompting](#Adversarial-Prompting)
  - [Model-end Defense](#Model-end-Defense)
    - [Adversarial Training](#Adversarial-Training)
    - [Model Modification](#Model-Modification)
    - [Certified Robustness](#Certified-Robustness)
- [Our\_Team](#our_team)
  - [Current Members](#current-members)
  - [Alumnus](#alumnus)
  - [Publications](#publications)



## Surveys

- \[**`2023`**\][[CoRR](https://arxiv.org/pdf/2211.01671.pdf)] Physically adversarial attacks and defenses in computer vision: A survey
- \[**`2023`**\][[arXiv](https://arxiv.org/pdf/2209.14262.pdf)] A survey on physical adversarial attack in computer vision
- \[**`2023`**\][[arXiv](https://arxiv.org/pdf/2209.15179.pdf)] Physical adversarial attack meets computer vision: A decade survey

- \[**`2021`**\][[IJMLC](https://link.springer.com/article/10.1007/s13042-020-01242-z)] Adversarial examples: attacks and defenses in the physical world
- \[**`2021`**\][[IEEE Access](https://ieeexplore.ieee.org/document/9614158)] Advances in adversarial attacks and defenses in computer vision: A survey

- \[**`2018`**\][[cybersecurity](https://cybersecurity.springeropen.com/articles/10.1186/s42400-018-0012-9)] A survey of practical adversarial example attacks



## Papers-Physical Adversarial Attacks

### Manufacturing Oriented Attacks

#### Touchable Attacks

- \[**`2023`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_Physically_Adversarial_Infrared_Patches_With_Learnable_Shapes_and_Locations_CVPR_2023_paper.pdf)] Physically adversarial infrared patches with learnable shapes and locations [**`2D`**]
- \[**`2023`**\][[AAAI](https://arxiv.org/pdf/2212.05709.pdf)] Hotcold block: Fooling thermal infrared detectors with a novel wearable design [**`2D`**]

- \[**`2022`**\][[TPAMI](https://arxiv.org/pdf/2212.12995.pdf)] Simultaneously optimizing perturbations and positions for black-box adversarial patch attacks [**`2D`**]
- \[**`2022`**\][[TPAMI](https://ieeexplore.ieee.org/abstract/document/9779913)] Adversarial Sticker: A Stealthy Attack Method in the Physical World [**`2D`**]
- \[**`2022`**\][[NIPS](https://arxiv.org/abs/2210.15291)] Isometric 3D Adversarial Examples in the Physical World [**`3D`**]

#### Untouchable Attacks

- \[**`2023`**\][[ICCV](https://arxiv.org/pdf/2307.07653.pdf)] RFLA: A Stealthy Reflected Light Adversarial Attack in the Physical World [**`Lighting`**]
- \[**`2023`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Physical-World_Optical_Adversarial_Attacks_on_3D_Face_Recognition_CVPR_2023_paper.pdf)] Physical-world optical adversarial attacks on 3d face recognition [**`Lighting`**]

- \[**`2022`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Shadows_Can_Be_Dangerous_Stealthy_and_Effective_Physical-World_Adversarial_Attack_CVPR_2022_paper.pdf)] Shadows can be dangerous: Stealthy and effective physical-world adversarial attack by natural phenomenon [**`Lighting`**]
- \[**`2022`**\][[arXiv](https://arxiv.org/pdf/2209.02430.pdf)] Adversarial color film: Effective physical-world attack to dnns [**`Lighting`**]
- \[**`2022`**\][[ICLR](https://arxiv.org/pdf/2112.07076.pdf)] Real-time neural voice camouflage [**`Audio/Speech`**]



### Resampling Oriented Attacks

#### Environment-oriented Attacks

- \[**`2022`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Suryanto_DTA_Physical_Camouflage_Attacks_Using_Differentiable_Transformation_Network_CVPR_2022_paper.pdf)] Dta: Physical camouflage attacks using differentiable transformation network

- \[**`2021`**\][[AAAi](https://cdn.aaai.org/ojs/16211/16211-13-19705-1-2-20210518.pdf)] Towards Universal Physical Attacks on Single Object Tracking

#### Sampler-oriented Attacks

- \[**`2022`**\][[NIPS](https://arxiv.org/pdf/2210.03895.pdf)] Viewfool: Evaluating the robustness of visual recognition to adversarial viewpoints

- \[**`2021`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Zolfi_The_Translucent_Patch_A_Physical_and_Universal_Attack_on_Object_CVPR_2021_paper.pdf)] The translucent patch: A physical and universal attack on object detectors



### Other PAEs

#### The Natural Physical Adversarial Attacks

- \[**`2023`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Towards_Benchmarking_and_Assessing_Visual_Naturalness_of_Physical_World_Adversarial_CVPR_2023_paper.pdf)] Towards benchmarking and assessing visual naturalness of physical world adversarial attacks [**`Optimization-based`**]

- \[**`2022`**\][[NIPS](https://arxiv.org/pdf/2210.06871.pdf)] Adv-attribute: Inconspicuous and transferable adversarial attack on face recognition [**`Generative`**]

#### The Transferable Physical Adversarial Attacks

- \[**`2023`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_T-SEA_Transfer-Based_Self-Ensemble_Attack_on_Object_Detection_CVPR_2023_paper.pdf)] T-sea: Transferbased self-ensemble attack on object detection [**`Optimization-based`**]

- \[**`2022`**\][[IEEE TIFS](https://ieeexplore.ieee.org/document/9856683)] TnT Attacks! Universal Naturalistic Adversarial Patches Against Deep Neural Network Systems [**`Generative`**]

#### The Generalized Physical Adversarial Attacks

- \[**`2021`**\][[IEEE TIP](https://ieeexplore.ieee.org/document/9632406)] Universal adversarial patch attack for automatic checkout using perceptual and attentional bias [**`Generative`**]

- \[**`2020`**\][[ECCV](https://arxiv.org/pdf/1910.14667.pdf)] Making an invisibility cloak: Real world adversarial attacks on object detectors [**`Optimization-based`**]



## Papers-Adversarial Defense Methods

### Data-end Defense

#### Adversarial Detecting

- \[**`2023`**\][[WACV](https://arxiv.org/pdf/2207.01795.pdf)] Patchzero: Defending against adversarial patch attacks by detecting and zeroing the patch

#### Adversarial Denoising

- \[**`2023`**\][[WACV](https://arxiv.org/pdf/2207.01795.pdf)] Patchzero: Defending against adversarial patch attacks by detecting and zeroing the patch

#### Adversarial Prompting

- \[**`2023`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Si_Angelic_Patches_for_Improving_Third-Party_Object_Detector_Performance_CVPR_2023_paper.pdf)] Angelic patches for improving third-party object detector performance



### Model-end Defense

#### Adversarial Training

- \[**`2023`**\][[arXiv](https://arxiv.org/pdf/2301.13487.pdf)] Adversarial Training of Self-supervised Monocular Depth Estimation against Physical-World Attacks

#### Model Modification

- \[**`2023`**\][[IEEE FG](https://ieeexplore.ieee.org/abstract/document/10042500)] Unified detection of digital and physical face attacks

#### Certified Robustness

- \[**`2022`**\][[arXiv](https://arxiv.org/pdf/2209.05980.pdf)] Certified Defences Against Adversarial Patch Attacks on Semantic Segmentation



## Our_Team

Our team is suuported by the **ZGC Lab** and the **DIG group** of the **State Key Laboratory of Software Development Environment** ([SKLSDE](https://ev.buaa.edu.cn/info/1035/1862.htm)), supervised Prof. [Xianglong Liu](https://xlliu-beihang.github.io/). The main research goals of our team is Security and Trustworthy AI.

### Current Members


**Haojie Hao**

- 

**Zhengquan Sun**

-



**Jin Hu**

- 

**Siyang wu**

- 

### Alumnus

**Zixin Yin**

-

### Collaborators

**Donghua Wang**

-

[**Tingsong Jiang**]

-

### Supervisors

[**Jiakai Wang**](https://jiakaiwangcn.github.io/)(<font color=red>**Primary**</font>)

- Jiakai is now a Research Scientist in **ZGC Lab**, Beijing, China. He received the Ph.D. degree in 2022 from [Beihang University](https://www.buaa.edu.cn/) (*Summa Cum Laude*), supervised by Prof. [Wei Li](http://sites.nlsde.buaa.edu.cn/~liwei/) and Prof. [Xianglong Liu](https://xlliu-beihang.github.io/). Before that, he obtained my BSc degree in 2018 from [Beihang University](https://www.buaa.edu.cn/) (*Summa Cum Laude*). His research interests are **Trustworthy AI** in **Computer Vision** (mainly) and **Multimodal Machine Learning**, including *Physical Adversarial Attacks and Defense*, *Transferable Adversarial Examples*, and *Security of Practical AI*.



[**Xianglong Liu**](https://xlliu-beihang.github.io/)

-Xianglong Liu is a Full Professor in School of Computer Science and Engineering at Beihang University. He received BS and Ph.D degrees under supervision of Prof. Wei Li, and visited DVMM Lab, Columbia University as a joint Ph.D student supervised by Prof. Shih-Fu Chang. His research interests include fast visual computing (e.g., large-scale search/understanding) and robust deep learning (e.g., network quantization, adversarial attack/defense, few shot learning). He received NSFC Excellent Young Scientists Fund, and was selected into 2019 Beijing Nova Program, MSRA StarTrack Program, and 2015 CCF Young Talents Development Program.





[**Aishan Liu**](https://liuaishan.github.io/)

-Aishan is an Assistant Professor in the State Key Laboratory of Software Development Environment, Department of Computer Science and Engineering at Beihang University. His research interestes are centered around AI Safety and Security, with broad interests in the areas of Adversarial Examples, Backdoor Attacks, Interpretable Deep Learning , Model Robustness, Fairness Testing, AI Testing and Evaluation, and their applications in real-world scenarios.

### Contributors

Waiting for your contribution ! 😄😄😄

