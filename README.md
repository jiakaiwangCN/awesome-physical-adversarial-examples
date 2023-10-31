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
- [Collaborators](#collaborators)
- [Contributors](#contributors)

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
- \[**`2022`**\][[NIPS](https://arxiv.org/pdf/2210.15291.pdf)] Isometric 3D Adversarial Examples in the Physical World [**`3D`**]
- \[**`2022`**\][[AAAI](https://arxiv.org/pdf/2109.07193.pdf)] FCA: Learning a 3D Full-coverage Vehicle Camouflage for Multi-view Physical Adversarial Attack [**`3D`**]
- \[**`2021`**\][[TCYB](https://arxiv.org/pdf/1902.02067.pdf)] Daedalus: Breaking Non-Maximum Suppression in Object Detection via Adversarial Examples [**`2D`**]
- \[**`2021`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Dual_Attention_Suppression_Attack_Generate_Adversarial_Camouflage_in_Physical_World_CVPR_2021_paper.pdf)] Dual Attention Suppression Attack: Generate Adversarial Camouflage in Physical World [**`3D`**]<iframe src="[https://github.com/nlsde-safety-team](https://ghbtns.com/github-btn.html?user=nlsde-safety-team)&repo=DualAttentionAttack&type=star&count=true&size=small" frameborder="0" scrolling="0" width="120px" height="20px"></iframe>
- \[**`2020`**\][[CVPR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tu_Physically_Realizable_Adversarial_Examples_for_LiDAR_Object_Detection_CVPR_2020_paper.pdf)] Physically Realizable Adversarial Examples for LiDAR Object Detection [**`3D`**]
- \[**`2020`**\][[ECCV](https://arxiv.org/pdf/1910.11099.pdf)] Adversarial T-shirt! Evading Person Detectors in A Physical World [**`3D`**]
- \[**`2019`**\][[ACM TOPS](https://arxiv.org/pdf/1801.00349.pdf)] A General Framework for Adversarial Examples with Objectives [**`2D`**]
- \[**`2019`**\][[CVPR Workshop](https://openaccess.thecvf.com/content_CVPRW_2019/papers/CV-COPS/Thys_Fooling_Automated_Surveillance_Cameras_Adversarial_Patches_to_Attack_Person_Detection_CVPRW_2019_paper.pdf)] Fooling automated surveillance cameras: adversarial patches to attack person detection [**`2D`**]
- \[**`2019`**\][[ICML Workshop](https://arxiv.org/pdf/1906.11897.pdf)] On Physical Adversarial Patches for Object Detection [**`2D`**]
- \[**`2019`**\][[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xiao_MeshAdv_Adversarial_Meshes_for_Visual_Recognition_CVPR_2019_paper.pdf)] MeshAdv: Adversarial Meshes for Visual Recognition [**`3D`**]
- \[**`2018`**\][[USENIX Workshop](https://arxiv.org/pdf/1807.07769.pdf)] Physical Adversarial Examples for Object Detectors [**`2D`**]
- \[**`2018`**\][[CVPR](https://openaccess.thecvf.com/content_cvpr_2018/papers/Eykholt_Robust_Physical-World_Attacks_CVPR_2018_paper.pdf)] Robust Physical-World Attacks on Deep Learning Visual Classification [**`2D`**]
- \[**`2018`**\][[ICLR](https://arxiv.org/pdf/1607.02533.pdf)] Adversarial examples in the physical world [**`2D`**]
- \[**`2018`**\][[ICML](https://arxiv.org/pdf/1707.07397.pdf)] Synthesizing Robust Adversarial Examples [**`3D`**]
- \[**`2017`**\][[arXiv](https://arxiv.org/pdf/1712.02494.pdf)] Adversarial Examples that Fool Detectors [**`2D`**]
- \[**`2016`**\][[ACM CCS](https://dl.acm.org/doi/10.1145/2976749.2978392)] Accessorize to a Crime: Real and Stealthy Attacks on State-of-the-Art Face Recognition [**`2D`**]

#### Untouchable Attacks

- \[**`2023`**\][[ICCV](https://arxiv.org/pdf/2307.07653.pdf)] RFLA: A Stealthy Reflected Light Adversarial Attack in the Physical World [**`Lighting`**]
- \[**`2023`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Physical-World_Optical_Adversarial_Attacks_on_3D_Face_Recognition_CVPR_2023_paper.pdf)] Physical-world optical adversarial attacks on 3d face recognition [**`Lighting`**]
- \[**`2022`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Shadows_Can_Be_Dangerous_Stealthy_and_Effective_Physical-World_Adversarial_Attack_CVPR_2022_paper.pdf)] Shadows can be dangerous: Stealthy and effective physical-world adversarial attack by natural phenomenon [**`Lighting`**]
- \[**`2022`**\][[arXiv](https://arxiv.org/pdf/2209.02430.pdf)] Adversarial color film: Effective physical-world attack to dnns [**`Lighting`**]
- \[**`2022`**\][[arXiv](https://arxiv.org/pdf/2206.12251.pdf)] Adversarial Zoom Lens: A Novel Physical-World Attack to DNNs [**`Lighting`**]
- \[**`2022`**\][[VR](https://arxiv.org/pdf/2012.05858.pdf)] SPAA: Stealthy Projector-based Adversarial Attacks on Deep Image Classifiers [**`Lighting`**]
- \[**`2022`**\][[WACV](https://arxiv.org/pdf/2110.11525.pdf)] Digital and Physical-World Attacks on Remote Pulse Detection [**`Lighting`**]
- \[**`2022`**\][[ICLR](https://arxiv.org/pdf/2112.07076.pdf)] Real-time neural voice camouflage [**`Audio/Speech`**]
- \[**`2022`**\][[NIPS](https://papers.nips.cc/paper_files/paper/2022/file/c204d12afa0175285e5aac65188808b4-Paper-Conference.pdf)] VoiceBlock: Privacy through Real-Time Adversarial Attacks with Audio-to-Audio Models [**`Audio/Speech`**]
- \[**`2021`**\][[USENIX Security Symposium](https://arxiv.org/pdf/2007.04137.pdf)] SLAP: Improving Physical Adversarial Examples with Short-Lived Adversarial Perturbations [**`Lighting`**]
- \[**`2021`**\][[ICCV Workshop](https://arxiv.org/pdf/2108.06247.pdf)] Optical Adversarial Attack [**`Lighting`**]
- \[**`2021`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Pony_Over-the-Air_Adversarial_Flickering_Attacks_Against_Video_Recognition_Networks_CVPR_2021_paper.pdf)] Over-the-Air Adversarial Flickering Attacks against Video Recognition Networks [**`Lighting`**]
- \[**`2021`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Duan_Adversarial_Laser_Beam_Effective_Physical-World_Attack_to_DNNs_in_a_CVPR_2021_paper.pdf)] Adversarial Laser Beam: Effective Physical-World Attack to DNNs in a Blink [**`Lighting`**]
- \[**`2021`**\][[AAAI](https://arxiv.org/pdf/2101.08154.pdf)] Fooling thermal infrared pedestrian detectors in real world using small bulbs [**`Lighting`**]
- \[**`2021`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Sayles_Invisible_Perturbations_Physical_Adversarial_Examples_Exploiting_the_Rolling_Shutter_Effect_CVPR_2021_paper.pdf)] Invisible Perturbations: Physical Adversarial Examples Exploiting the Rolling Shutter Effect [**`Lighting`**]
- \[**`2021`**\][[arXiv](https://arxiv.org/pdf/2106.09908.pdf)] Light Lies: Optical Adversarial Attack [**`Lighting`**]
- \[**`2021`**\][[ICASSP](https://arxiv.org/pdf/2105.09022.pdf)] Attack on practical speaker verification system using universal adversarial perturbations [**`Audio/Speech`**]
- \[**`2020`**\][[NIPS](https://arxiv.org/pdf/2002.03500.pdf)] Watch out! Motion is Blurring the Vision of Your Deep Neural Networks [**`Lighting`**]
- \[**`2020`**\][[USENIX Security Symposium](https://arxiv.org/pdf/2006.11946.pdf)] Light Commands: Laser-Based Audio Injection Attacks on Voice-Controllable Systems [**`Audio/Speech`**]
- \[**`2020`**\][[ICASSP](https://arxiv.org/pdf/2003.02301.pdf)] Real-time, Universal, and Robust Adversarial Attacks Against Speaker Recognition Systems [**`Audio/Speech`**]
- \[**`2020`**\][[HotMobile](https://dl.acm.org/doi/abs/10.1145/3376897.3377856)] Practical Adversarial Attacks Against Speaker Recognition Systems [**`Audio/Speech`**]
- \[**`2020`**\][[USENIX Security Symposium](https://www.usenix.org/system/files/sec20summer_chen-yuxuan_prepub.pdf)] Devil’s Whisper: A General Approach for Physical Adversarial Attacks against Commercial Black-box Speech Recognition Devices [**`Audio/Speech`**]
- \[**`2019`**\][[S&P](https://www.ieee-security.org/TC/SP2019/posters/hotcrp_sp19posters-final28.pdf)] Poster: Perceived Adversarial Examples [**`Lighting`**]
- \[**`2019`**\][[NIPS](https://arxiv.org/pdf/1911.00126.pdf)] Adversarial Music: Real World Audio Adversary Against Wake-word Detection System [**`Audio/Speech`**]
- \[**`2019`**\][[IJCAI](https://arxiv.org/pdf/1810.11793.pdf)] Robust Audio Adversarial Example for a Physical Attack [**`Audio/Speech`**]
- \[**`2019`**\][[ICML](https://arxiv.org/pdf/1903.10346.pdf)] Imperceptible, Robust, and Targeted Adversarial Examples for Automatic Speech Recognition [**`Audio/Speech`**]
- \[**`2019`**\][[arXiv](https://arxiv.org/pdf/1906.06355.pdf)] Perceptual Based Adversarial Audio Attacks [**`Audio/Speech`**]
- \[**`2018`**\][[AAAI Symposium](https://arxiv.org/pdf/1810.10337.pdf)] Projecting Trouble: Light Based Adversarial Attacks on Deep Learning Classifiers [**`Lighting`**]
- \[**`2018`**\][[S&P Workshop](https://arxiv.org/pdf/1801.01944.pdf)] Audio Adversarial Examples: Targeted Attacks on Speech-to-Text [**`Audio/Speech`**]



### Resampling Oriented Attacks

#### Environment-oriented Attacks

- \[**`2022`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Suryanto_DTA_Physical_Camouflage_Attacks_Using_Differentiable_Transformation_Network_CVPR_2022_paper.pdf)] Dta: Physical camouflage attacks using differentiable transformation network
- \[**`2021`**\][[AAAI](https://cdn.aaai.org/ojs/16211/16211-13-19705-1-2-20210518.pdf)] Towards Universal Physical Attacks on Single Object Tracking
- \[**`2021`**\][[WACV](https://arxiv.org/pdf/2108.11765.pdf)] Physical Adversarial Attacks on an Aerial Imagery Object Detector
- \[**`2021`**\][[ICASSP](https://arxiv.org/pdf/2105.09022.pdf)] Attack on practical speaker verification system using universal adversarial perturbations
- \[**`2020`**\][[ICASSP](https://arxiv.org/pdf/2003.02301.pdf)] Real-time, Universal, and Robust Adversarial Attacks Against Speaker Recognition Systems
- \[**`2020`**\][[HotMobile](https://dl.acm.org/doi/abs/10.1145/3376897.3377856)] Practical Adversarial Attacks Against Speaker Recognition Systems
- \[**`2019`**\][[NIPS](https://arxiv.org/pdf/1911.00126.pdf)] Adversarial Music: Real World Audio Adversary Against Wake-word Detection System
- \[**`2019`**\][[ICML](https://arxiv.org/pdf/1903.10346.pdf)] Imperceptible, Robust, and Targeted Adversarial Examples for Automatic Speech Recognition

#### Sampler-oriented Attacks

- \[**`2022`**\][[NIPS](https://arxiv.org/pdf/2210.03895.pdf)] Viewfool: Evaluating the robustness of visual recognition to adversarial viewpoints
- \[**`2022`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Hu_Adversarial_Texture_for_Fooling_Person_Detectors_in_the_Physical_World_CVPR_2022_paper.pdf)] Adversarial Texture for Fooling Person Detectors in the Physical World
- \[**`2021`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Zolfi_The_Translucent_Patch_A_Physical_and_Universal_Attack_on_Object_CVPR_2021_paper.pdf)] The Translucent Patch: A Physical and Universal Attack on Object Detectors
- \[**`2020`**\][[ECCV](https://arxiv.org/pdf/1910.11099.pdf)] Adversarial T-shirt! Evading Person Detectors in A Physical World
- \[**`2019`**\][[ICML](https://arxiv.org/pdf/1903.10346.pdf)] Imperceptible, Robust, and Targeted Adversarial Examples for Automatic Speech Recognition
- \[**`2019`**\][[arXiv](https://arxiv.org/pdf/1906.06355.pdf)] Perceptual Based Adversarial Audio Attacks
- \[**`2019`**\][[NIPS](https://arxiv.org/pdf/1911.00126.pdf)] Adversarial Music: Real World Audio Adversary Against Wake-word Detection System
- \[**`2018`**\][[USENIX Workshop](https://arxiv.org/pdf/1807.07769.pdf)] Physical Adversarial Examples for Object Detectors
- \[**`2018`**\][[CVPR](https://openaccess.thecvf.com/content_cvpr_2018/papers/Eykholt_Robust_Physical-World_Attacks_CVPR_2018_paper.pdf)] Robust Physical-World Attacks on Deep Learning Visual Classification
- \[**`2018`**\][[ICML](https://arxiv.org/pdf/1707.07397.pdf)] Synthesizing Robust Adversarial Examples



### Other PAEs

#### The Natural Physical Adversarial Attacks

- \[**`2023`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Towards_Benchmarking_and_Assessing_Visual_Naturalness_of_Physical_World_Adversarial_CVPR_2023_paper.pdf)] Towards benchmarking and assessing visual naturalness of physical world adversarial attacks [**`Optimization-based`**]
- \[**`2022`**\][[NIPS](https://arxiv.org/pdf/2210.06871.pdf)] Adv-attribute: Inconspicuous and transferable adversarial attack on face recognition [**`Generative`**]
- \[**`2022`**\][[IEEE TIFS](https://ieeexplore.ieee.org/document/9856683)] TnT Attacks! Universal Naturalistic Adversarial Patches Against Deep Neural Network Systems [**`Generative`**]

#### The Transferable Physical Adversarial Attacks

- \[**`2023`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_T-SEA_Transfer-Based_Self-Ensemble_Attack_on_Object_Detection_CVPR_2023_paper.pdf)] T-sea: Transferbased self-ensemble attack on object detection [**`Optimization-based`**]
- \[**`2023`**\][[Pattern Recognition](https://dl.acm.org/doi/abs/10.1016/j.patcog.2023.109435)] Boosting transferability of physical attack against detectors by redistributing separable attention [**`Optimization-based`**]
- \[**`2022`**\][[IEEE TIFS](https://ieeexplore.ieee.org/document/9856683)] TnT Attacks! Universal Naturalistic Adversarial Patches Against Deep Neural Network Systems [**`Generative`**]
- \[**`2021`**\][[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Dual_Attention_Suppression_Attack_Generate_Adversarial_Camouflage_in_Physical_World_CVPR_2021_paper.pdf)] Dual Attention Suppression Attack: Generate Adversarial Camouflage in Physical World [**`Optimization-based`**]

#### The Generalized Physical Adversarial Attacks

- \[**`2023`**\][[ICCV](https://arxiv.org/pdf/2308.07009.pdf)] ACTIVE: Towards Highly Transferable 3D Physical Camouflage for Universal and Robust Vehicle Evasion [**`Optimization-based`**]
- \[**`2022`**\][[IEEE TIFS](https://ieeexplore.ieee.org/document/9856683)] TnT Attacks! Universal Naturalistic Adversarial Patches Against Deep Neural Network Systems [**`Generative`**]
- \[**`2021`**\][[IEEE TIP](https://ieeexplore.ieee.org/document/9632406)] Universal adversarial patch attack for automatic checkout using perceptual and attentional bias [**`Generative`**]
- \[**`2020`**\][[ECCV](https://arxiv.org/pdf/1910.14667.pdf)] Bias-based Universal Adversarial Patch Attack for Automatic Check-out [**`Generative`**]
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

### Supervisors

[**Jiakai Wang**](https://jiakaiwangcn.github.io/)(<font color=red>**Primary**</font>)

- Jiakai is now a Research Scientist in **ZGC Lab**, Beijing, China. He received the Ph.D. degree in 2022 from [Beihang University](https://www.buaa.edu.cn/) (*Summa Cum Laude*), supervised by Prof. [Wei Li](http://sites.nlsde.buaa.edu.cn/~liwei/) and Prof. [Xianglong Liu](https://xlliu-beihang.github.io/). Before that, he obtained my BSc degree in 2018 from [Beihang University](https://www.buaa.edu.cn/) (*Summa Cum Laude*). His research interests are **Trustworthy AI** in **Computer Vision** (mainly) and **Multimodal Machine Learning**, including *Physical Adversarial Attacks and Defense*, *Transferable Adversarial Examples*, and *Security of Practical AI*.


[**Aishan Liu**](https://liuaishan.github.io/)

- Aishan is an Assistant Professor in the State Key Laboratory of Software Development Environment, Department of Computer Science and Engineering at Beihang University. His research interestes are centered around AI Safety and Security, with broad interests in the areas of Adversarial Examples, Backdoor Attacks, Interpretable Deep Learning , Model Robustness, Fairness Testing, AI Testing and Evaluation, and their applications in real-world scenarios.

[**Xianglong Liu**](https://xlliu-beihang.github.io/)

- Xianglong Liu is a Full Professor in School of Computer Science and Engineering at Beihang University. He received BS and Ph.D degrees under supervision of Prof. Wei Li, and visited DVMM Lab, Columbia University as a joint Ph.D student supervised by Prof. Shih-Fu Chang. His research interests include fast visual computing (e.g., large-scale search/understanding) and robust deep learning (e.g., network quantization, adversarial attack/defense, few shot learning). He received NSFC Excellent Young Scientists Fund, and was selected into 2019 Beijing Nova Program, MSRA StarTrack Program, and 2015 CCF Young Talents Development Program.


## Collaborators

**Donghua Wang**

- 

[**Tingsong Jiang**]

- 


## Contributors

Waiting for your contribution ! 😄😄😄

