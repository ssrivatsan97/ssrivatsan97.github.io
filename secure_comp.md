---
layout: page
---

<h3><b>Secure Multiparty Computation</b></h3>
Project guided by [Prof. Sibiraj Pillai](https://www.ee.iitb.ac.in/~bsraj/), [Prof. Vinod Prabhakaran](http://www.tcs.tifr.res.in/~vinodmp/), [Prof. Manoj Prabhakaran](https://www.cse.iitb.ac.in/~mp/) (as B.Tech. project)

[Link to project thesis](BTP_Thesis_final.pdf)<br/>
[Link to publication](https://doi.org/10.1007/978-3-030-35423-7_11)

***Abstract*** — In an influential work aimed at understanding the communication requirements
of secure computation, Feige, Kilian and Naor introduced a minimal model of
secure computation ([STOC 1994](http://doi.acm.org/10.1145/195058.195408)). In that work, among other results, Feige et
al.\ presented a simple protocol for the 2 input AND function. It has
remained an intriguing question whether the communication and randomness
used in this protocol are optimal. While previous work of Data et al.
([CRYPTO 2014](https://doi.org/10.1007/978-3-662-44381-1\_12)) showed that the communication from the two parties with inputs
(Alice and  Bob) to the third party who gets the output is optimal, the
question of optimality for the third message in the protocol -- a common
reference string shared between Alice and Bob -- remained open. In this note
we show that in fact, this message (and hence all the randomness used in the
protocol) is also optimal in the protocol of Feige et al. This improves on a
previous result of Rajan et al. ([ISIT 2016](https://doi.org/10.1109/ISIT.2016.7541521)), which showed this optimality restricted to
protocols where Alice and Bob are deterministic. Further, our result holds even if
only a weak secrecy condition is required of the protocol.

![](secure-comp.png)
<p align="center"><em>An illustration of the three-party secure computation problem</em></p>
