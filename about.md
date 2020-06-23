---
layout: page
title: Projects
permalink: /projects
---

## **Publications** ##
1. Sibi Raj B. Pillai, Manoj Prabhakaran, Vinod M. Prabhakaran, Srivatsan Sridhar (in alphabetical order)<br/>
“ Optimality of a Protocol by Feige-Kilian-Naor for Three-Party Secure Computation ”<br/>
[20th International Conference on Cryptology in India](https://www.isical.ac.in/~indocrypt2019/#/), Hyderabad, India, December 15–18, 2019, Proceedings<br/>
[Link to publication](https://doi.org/10.1007/978-3-030-35423-7_11)

1. K. Subramani, S. Sridhar (equal contribution) , Rohit M. A., and P. Rao<br/>
“ Energy-Weighted Multi-Band Novelty Functions for Onset Detection in Piano Music ”<br/>
Proc. of [National Communications Conference 2018](https://www.iith.ac.in/~ncc2018/), Hyderabad, India.<br/>
[Read more](/onset_detection)<br/>
[Link to publication](https://www.ee.iitb.ac.in/student/~daplab/publications/2018/p154-subramani.pdf)

## **Preprints** ##
1.  Srivatsan Sridhar, Mert Pilanci, Ayfer Ozgur <br/>
" Lower Bounds and a Near-Optimal Shrinkage Estimator for Least Squares using Random Projections "<br/>
(Submitted to the [IEEE Journal on Selected Areas in Information Theory (JSAIT)](https://www.itsoc.org/publications/journal-on-selected-areas-in-information-theory-jsait) - Special Issue on Estimation and Inference, and is awaiting review. <br/>
[Link to preprint](https://arxiv.org/abs/2006.08160)

1. Shubham Chandak, Kedar Tatwawadi, Srivatsan Sridhar, Tsachy Weissman <br/>
" Impact of lossy compression of nanopore raw signal data on basecall and consensus accuracy "<br/>
[Link to preprint](https://www.biorxiv.org/content/10.1101/2020.04.19.049262v1)


## **Other Projects** ##
#### 2019 ####
<!-- 1. **Compression of Genomic Data**<br/>
We studied lossless and lossy compression methods for raw current signals from the Nanopore genome sequencing method. Using state-of-the-art lossy compressors, we achieve as much as 40-50% reduction in the compressed size of the raw signal with negligible impact on basecalling and consensus accuracy.<br/> 
[Link to preprint](https://www.biorxiv.org/content/10.1101/2020.04.19.049262v1) -->

1. **AdvAE and FlowAE : Sampling Arbitrary Latent Variable Distributions in an Autoencoder** <br/>
*Deep Generative Models project in Stanford University* <br/>
In the traditional variational autoencoder (VAE), the latent variable is sampled from a simple prior distribution which is usually Gaussian. The simple prior makes the sampled latent variable less expressive, and the prior may not fit the data distribution well. We propose to learn an arbitrarily distributed latent space using an autoencoder and then use a generative model to learn the arbitrary distribution for the latent variable.
For this, we propose two types of architectures. One is the AdvAE where a generator network will be adversarially trained to generate latent variable samples similar to an arbitrary latent space learned by an autoencoder. The second is FlowAE which uses a normalizing flow model which will be trained to generate latent variable samples from the same arbitrary latent space.<br/>
[Read more](/advae)

#### 2018 ####
1. **Secure Multiparty Computation**<br/>
*Project guided by [Prof. Sibiraj Pillai](https://www.ee.iitb.ac.in/~bsraj/), [Prof. Vinod Prabhakaran](http://www.tcs.tifr.res.in/~vinodmp/), [Prof. Manoj Prabhakaran](https://www.cse.iitb.ac.in/~mp/) (as B.Tech. project)*<br/>
In this problem, two parties Alice (A) and Bob (B) have private data X and Y, respectively. A third party Charlie (C) needs to compute a function Z = f(X,Y). This must be done in such a way that each party does not learn anything more about other parties' private data than what they already know. We analyze lower bounds on the amount of randomness and communication required to achieve this. In particular, we proved the optimality of a well known protocol of three-party secure computation of AND. We prove this under a more general weak secrecy requirement. The proof uses a novel set-theoretic approach which we believe can be extended to other security problems.<br/>
[Read more](/secure_comp)

1. **See in the Dark**<br/>
*Image Processing project in IIT Bombay*<br/>
See in the dark is a method to reconstruct bright images from dark (low light, low exposure) images. The goal is to have such a reconstruction without increasing the noise in the resulting image. We have presented an end-to-end system for this purpose using a cGAN (Conditional Generative Adversarial Network). This project was partly inspired by [Learning to See in the Dark](https://arxiv.org/abs/1805.01934) (Chen et. al.)<br/>
[Read more](/see_in_the_dark)

1. **RF Fingerprinting Based Authentication for Bluetooth Low Energy**<br/>
*Internship project in Massachusetts Institute of Technology*<br/>
This project is an attempt to authenticate Bluetooth Low Energy (BLE) transmitters by identifying them through features extracted from their transmitted signals. This classification of transmitters based on features from their signals is RF Fingerprinting. The objective for such authentication in this project is to prevent battery drainage attacks on ultra-low power bluetooth receivers for IoT networks. My contribution was in developing a feature extraction pipeline and neural network for RF Fingerprinting, and reducing the energy consumption of this system.<br/>

1. **Voice Conversion**<br/>
*Machine Learning project in IIT Bombay*<br/>
The Voice Conversion task involves converting speech from one speaker’s (source) voice to another speaker’s (target) voice. Machine learning methods can be made to perform better than plain signal processing techniques as they can take into account multiple features of speech which cannot be characterized easily by signal processing techniques. In this 
project, we have explored the use of Recurrent Neural Networks (RNNs) for Voice Conversion. We have explored multiple variations of RNNs using LSTMs and GRUs and observed the effects of changing various parameters of the models. Our approach uses two independently trained neural networks - one which converts source speech to phonemes and another which converts phonemes to target speech. We will present the results achieved by both the networks for these different parameters.<br/>
[Read more](/voice_conversion)

1. **Digitally Programmable Analog Computer**<br/>
*Electronics Design project in IIT Bombay*<br/>
The goal of this project was to design an analog computer that can simulate linear dynamical systems for real-time simulations. We designed the analog computer to solve systems modeled by upto 5th order coupled linear differential equations. It was made digitally programmable by using an on-board microcontroller which can be programmed via a serial interface. The entire circuit was pabricated on a PCB with on-board power management, and was tested extensively to accurately simulate the given systems in real time. This project was supported by the Prof. Mukul Chandorkar, dept. of Electrical Engg. IIT Bombay for hardware-in-loop simulations in the power electronics lab.<br/>
[Read more](/dpac)
