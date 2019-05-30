---
layout: page
---

<h3><b>Secure Multiparty Computation</b></h3>
Project guided by [Prof. Sibiraj Pillai](https://www.ee.iitb.ac.in/~bsraj/), [Prof. Vinod Prabhakaran](http://www.tcs.tifr.res.in/~vinodmp/), [Prof. Manoj Prabhakaran](https://www.cse.iitb.ac.in/~mp/) (as B.Tech. project)

[Link to project thesis](BTP_Thesis_final.pdf)<br/>
[Link to seminar presentation](BTP_presentation_final.pdf)

The three-party secure computation problem is shown in the figure below. In this, two parties Alice (A) and Bob (B) have private data X and Y, respectively. A third party Charlie (C) needs to compute a function Z = f(X,Y). This must be done with the constraints that: 
i. Charlie must compute Z with zero probability of error.
i. Charlie must not learn anything more about X and Y than what Z reveals.
i. Alice must not learn anything more about Y than what X reveals.
i. Bob must not learn anything more about X than what Y reveals.

It is of interest to calculate lower bounds on the entropy of the messages exchanged on each of the communication channels. My research, in particular focuses on secure three-party computation of the one-bit AND function. Lower bounds have already been derived for a class of one-shot protocols ([FKN protocols](http://www.wisdom.weizmann.ac.il/~naor/PAPERS/fkn.pdf)) in previous work. I am examining a more general class of one-shot protocols where Alice and Bob are allowed to use private randomness. I have derived lower bounds on the cardinality and entropy of the shared randomness, in protocols that use private randomness. I have further linked secure multiparty computation with other problems such as distribution design.

![](secure-comp.png)
<p align="center"><em>An illustration of the three-party secure computation problem</em></p>