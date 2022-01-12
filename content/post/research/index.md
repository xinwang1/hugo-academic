---
title: Research Overview
subtitle: The main focus of my research is to better understand the limits of information processing with quantum systems and the power of quantum artificial intelligence.

# Summary for listings and search engines
summary: The main focus of my research is to better understand the limits of information processing with quantum systems and the power of quantum artificial intelligence. I also aim to explore new applications of quantum computing and new approaches to overcome theatrical challenges in realizing quantum technologies.

# Link this post with a project
projects: []

# Date published
date: "2021-12-28T00:00:00Z"

# Date updated
lastmod: "2021-12-28T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
#   focal_point: ""
#   placement: 2
#   preview_only: false

authors:
- admin


tags:
- research
- overview

categories:
- research
- overview
---

The main focus of my research is to better understand the limits of information processing with quantum systems and the power of quantum artificial intelligence. I also aim to explore new applications of quantum computing and new approaches to overcome theatrical challenges in realizing quantum technologies.

My Ph.D. thesis **Semidefinite Optimization for Quantum Information** ([pdf](https://xinwangonline.files.wordpress.com/2018/10/dissertation-v1.pdf)) aims to contribute to the development of quantum Shannon theory, entanglement theory, and zero-error information theory. It explores the fundamental properties of quantum entanglement and establishes efficiently computable approximations for elementary tasks in quantum information theory by using semidefinite optimization, matrix analysis, and information measures.

#### **QUANTUM SHANNON THEORY**

Quantum Shannon theory is the study of the ultimate performance of communication with quantum systems. One of my primary topics is to investigate the communication capabilities of quantum channels under both finite blocklength and asymptotic regime. The asymptotic regime focuses on the ultimate limits of communication, while the finite blocklength regime focuses on a more practical scenario involving only small and medium number of bits or qubits. Good examples of my results in this area are as follows:

- **X. Wang**, W. Xie, and R. Duan, “*Semidefinite programming strong converse bounds for classical capacity*,” IEEE Transactions on Information Theory, 2018 [[link](https://xinwangonline.files.wordpress.com/2018/03/sdp-c-capacity.pdf)]. (**QIP 2017 talk**).
  <!--This work establishes SDP strong converse rates for channel coding and provides the best known upper bound for the classical capacity of amplitude damping channel.-->
- **X. Wang**, K. Fang, and R. Duan, “*Semidefinite programming converse bounds for quantum communication*,” IEEE Transactions on Information Theory, 2019 [[link](https://arxiv.org/abs/1709.00200)]. (**QIP 2018 talk**).
  <!--This work determines efficiently computable upper bounds for quantum communication in both the non-asymptotic and asymptotic regime.-->
- **X. Wang**, K. Fang, and M. Tomamichel, “*On converse bounds for classical communication over quantum channels*,” IEEE Transactions on Information Theory, 2019 [[link](https://arxiv.org/abs/1709.05258)]. (**QIP 2018 talk**).
  <!--This work introduces the constant-bounded subchannels and its application to a new meta-converse on channel coding and establishes a finite resource analysis of quantum erasure channels.-->

#### **QUANTUM ENTANGLEMENT**

Quantum entanglement is a key ingredient in many quantum information processing tasks, including teleportation, superdense coding, and quantum cryptography. I am interested in exploring the fundamental structure and the resource theory of entanglement. For example, I demonstrate the irreversibility of asymptotic entanglement manipulation under quantum operations that completely preserve the positivity of partial transpose (PPT), resolving a major [**open problem**](https://qig.itp.uni-hannover.de/qiproblems/Reversible_entanglement_manipulation) in quantum information theory.

- **X. Wang** and R. Duan, “*Irreversibility of Asymptotic Entanglement Manipulation Under Quantum Operations Completely Preserving Positivity of Partial Transpose*,” Physical Review Letters, 2017 [[link](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.119.180506)], (**QIP 2017 talk**).

I also established single-letter formulas to efficiently quantify the quantum entanglement required for quantum state preparation and quantum channel implementation:

- **X. Wang** and M. M. Wilde, “*Exact entanglement cost of quantum states and channels under PPT-preserving operations*,” arXiv:1809.09592 [[link](https://scirate.com/arxiv/1809.09592)], (**QIP 2019 talk**).
- **X. Wang** and M. M. Wilde, “*Cost of quantum entanglement simplified*,” Physical Review Letters, 2020 [[link](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.125.040502)]. Check "Healing an Achilles' heel of quantum entanglement " at [phys.org](https://phys.org/news/2020-07-achilles-heel-quantum-entanglement.html) for more details.

Notably, the above work introduces the first entanglement measure that is efficiently computable while possessing a direct operational meaning for general bipartite states, thus solving a question that has remained open since the inception of entanglement theory over two decades ago. This unique feature helps us better understand the fundamental structure and power of entanglement.

#### **FAULT-TOLERANT QUANTUM COMPUTATION**

Magic state manipulation is a crucial component in the leading approaches to realizing scalable, fault-tolerant, and universal quantum computation. Related to magic state manipulation is the resource theory of magic states, for which one of the goals is to characterize and quantify quantum “magic.” In the following two papers, we develop *resource-theoretic approaches* to study the non-stabilizer resources in fault-tolerant quantum computation. We, in particular, introduce efficiently computable magic measures to quantify the magic of quantum states as well as noisy quantum circuits and explore their applications in magic state distillation, gate synthesis, and classical simulation of noisy circuits.

- **X. Wang**, M. M. Wilde, and Y. Su, “Efficiently computable bounds for magic state distillation,” Physical Review Letters, 2020 [[link](http://arxiv.org/abs/1812.10145)], (**AQIS 2019 long talk**).  
- **X. Wang**, M. M. Wilde, and Y. Su, “Quantifying the magic of quantum channels,” New Journal of Physics, 21 (10), 103002, 2019 [[link](https://iopscience.iop.org/article/10.1088/1367-2630/ab451d)], (**QIP 2020 talk**).

#### Quantum Resource Theory

Quantum resource theory (QRT) offers a powerful framework for studying different phenomena in quantum physics. It aims to capture and quantify the desirable quantum effect, and optimize its use for particular quantum applications. My interests in this area lie in the mathematical analysis and characterization of quantum resources, as well as the applications of QRT for other quantum technologies. Good examples of my results are as follows:

- **X. Wang** and M. M. Wilde, “Resource theory of asymmetric distinguishability,” [Physical Review Research]( https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.1.033170), (**QIP 2020 talk**).

In particular, I was invited to deliver a keynote on *Quantum Channel’s Resource Theory* [[slides](https://www.xinwang.info/files/slides/QRT_channel.pdf)] at **[TQC 2020](http://tqc2020.lu.lv/welcome-to-tqc-2020-website/)**.


#### **Zero-error Information Theory**

heorythe ordinary Shannon theory studies communication with asymptotically vanishing errors, Shannon also investigated the information theory when errors are required to be strictly zero, which is known as the zero-error information theory.  In this area, the communication problem reduces to the study of the so-called confusability graph (non-commutative graph) of a classical channel (quantum channel). A good example of my research in this area is proving the separation between the quantum Lovász number and the entanglement-assisted zero-error capacity:

- **X. Wang** and R. Duan, “Separation Between Quantum Lovász Number and Entanglement-Assisted Zero-Error Classical Capacity,” IEEE Transactions on Information Theory, 64 (3), 1454–1460, 2018 [[link](https://xinwangonline.files.wordpress.com/2018/03/separation-between-c0e-and-lovasz.pdf)]. (Contributed talk at AQIS 2017).