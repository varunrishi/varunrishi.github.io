---
layout: page
title: "About"
permalink: /about/
---

![image](/images/ProfilePic.png){: style="float: center"}


I am a postdoctoral researcher at Sandia National Labs working in the area of theoretical and computational chemistry. 

## Research Themes: 

![image](/images/PastnFutureResearch.png){: style="float: center"}


# Tracking light-induced chemical transformations at ultrafast timescale
Tracking chemical reactions as they happen is a big challenge for both experiment and theory. Probing at the ultrafast timescale, broadly defined to be in femtoseconds to picoseconds range, provides us with immense opportunities to understand these reactions. Furthermore, Modeling light-induced chemical reactions on an ultrafast timescale poses a rigorous test for quantum chemical methods. In our collaborative experimental-theoretical study on the ultrafast photofragmentation of dimethyl disulphide, a model for exploring protein stability under UV light, I address challenges hindering a predictive understanding of photochemical processes by developing an approach to accurately model the dynamics over energy landscape.

# Ab-initio methods for the strong correlation problem
Single reference coupled cluster (CC) methods are severely challenged in the description of potential energy surfaces for the simultaneous dissociation of multiple bonds and in predicting the electronic structure of transition metal compounds and actinides. However certain physically motivated modifications to the general coupled cluster theory such as the distinguishable cluster (DC) method have been found to be successful. In my doctoral work, I proposed that a plausible explanation for success of these 'internally corrected coupled cluster methodologies' is their implicit inclusion of the effect of higher excitations. Our work has led to development of excited state approaches based on these methods which show improved estimates of excitation energies. I further proposed a general extension to include the effect of higher excitations. 



# Tensor decomposition techniques to reduce the cost of quantum chemical methods

Tensor decomposition methods such as singular value decomposition (SVD) or its higher-order analog (HOSVD, canonical polyadic, Tucker decomposition and matrix product states), can compress the data and help quantum chemical methods overcome the curse of dimensionality. These decomposition methods meet their true challenge in the form of higher-order coupled cluster theory as full triples (CCSDT) and quadruples (CCSDTQ), which scale as N<sup>8</sup> and N<sup>10</sup> respectively where N (the number of basis functions) is indicative of the size of the system. Our work shows a general way to formally reduce the scaling of CC methods with the canonical polyadic decomposition of the density-fitted integrals. An extension of this work has led us to propose a low-rank version of full triples, CP-DF-CCSDT, which pushes the boundaries of applicability with benefits of a distributed memory massively parallel implementation. 

# Machine Learning the effect of electron correlation on molecular properties
Developing Machine learning models trained on highly accurate wave-function methods is a promising avenue of research and we seek to answer the following questions: 1) Can supervised machine learning models reliably predict molecular properties through linear response? and 2) What choice of features for the ML model would enable maximum transferability across chemical space?


<br/>
<br/>


I have contributed codes to quantum chemistry softwares such as [ACESII](http://www.qtp.ufl.edu/Aces/) and [MPQC](https://github.com/ValeevGroup/mpqc). You can find the codes developed by me [here](https://github.com/varunrishi)




