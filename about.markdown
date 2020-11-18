---
layout: page
title: "About"
permalink: /about/
---

![image](/images/ProfilePic.png){: style="float: center"}


I am a postdoctoral researcher at California Institute of Technology (Caltech) working in the area of theoretical and computational chemistry. 

## Research Themes: 

![image](/images/Figure1_color.pdf){: style="float: center"}

# Ab-initio methods for the strong correlation problem
Single reference coupled cluster (CC) methods are severely challenged in the description of potential energy surfaces for the simultaneous dissociation of multiple bonds and in predicting the electronic structure of transition metal compounds and actinides. However certain physically motivated modifications to the general coupled cluster theory such as the distinguishable cluster (DC) method have been found to be successful at a lower computational cost.In my doctoral work, I proposed that a plausible explanation for success of these approximations is their implicit inclusion of the effect of higher excitations. We extended these internally corrected coupled cluster methodologies to include the complete effect of triples excitations by identifying exact diagrammatic cancellations that occur for any 3-electron systems. This led to approximations that improve on the performance of the parent method for molecular systems with strong correlation. Building on the success of these ground-state approaches, we formulated consistent methods for excited states, and were able to show greater accuracy than the standard EOM-CCSD method and significant improvement on the treatment of states with double excitation character.



# Tensor decomposition techniques to reduce the cost of quantum chemical methods
Higher-order CC methods are exorbitantly expensive in terms of computational resources and as a result, have been used marginally till now. Storage of higher-order tensors and the polynomial scaling due to tensor-tensor multiplications are the big hurdles. Tensor decomposition methods such as singular value decomposition (SVD) or its higher-order analog (HOSVD) and other related techniques (canonical polyadic, Tucker decomposition and matrix product states), can compress the data and help quantum chemical methods overcome the curse of dimensionality. These decomposition methods meet their true challenge in the form of higher-order coupled cluster theory as full triples (CCSDT) and quadruples (CCSDTQ), which scale as $N^{8}$ and $N^{10}$ respectively where $N$ (the number of basis functions) is indicative of the size of the system. Our work shows a general way to formally reduce the scaling of CC methods with the canonical polyadic decomposition of the density-fitted integrals. An extension of this work has led us to propose a low-rank version of full triples, CP-DF-CCSDT, which pushes the boundaries of applicability with benefits of a distributed memory massively parallel implementation. 

# Machine Learning the effect of electron correlation on molecular properties
Developing Machine learning models trained on highly accurate wave-function methods is a promising avenue of research and we seek to answer the following questions: 

1) Can supervised machine learning models reliably predict molecular properties through linear response?

2) What choice of features for the ML model would enable maximum transferability across chemical space?





I have contributed codes to quantum chemistry softwares such as [ACESII](http://www.qtp.ufl.edu/Aces/) and [MPQC](https://github.com/ValeevGroup/mpqc).

You can find the codes developed by me here:
[Github]




[Github]: https://github.com/varunrishi 
