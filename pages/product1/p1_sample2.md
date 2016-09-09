---
title: Microstates, meet Macrostate
keywords: sample
toc: false
summary: "Understanding microstates and macrostates."
sidebar: product1_sidebar
permalink: p1_sample2.html
folder: product1
---

Consider a coin flipping machine capable of flipping two *identical and *fair* coins; in a single run, the machine flips the coins and outputs the state of the coins, say, HT. The entire set of output is HH, HT, TH, HH. 

We perform an experiment to record the frequency of different outputs for 1000000000 runs. The following results are obtained:

| Output | Probability |
| :-: | :-: |
| HH | $1/4$ |
| HT | $1/4$ |
| TH | $1/4$ |
| TT | $1/4$ |
| -- | ----- |

Notice how these outputs all have the same probability. These configurations of individual coins are called the *microstates* of the coins.

{% include callout.html content="The *microstates* of a system specifies the individual properties of every element of the system. The system could fall into any microstate with equal probability. " type="info" %} 

Another scientists walks into our lab and asks the following question: given that the two coins are identical, is it possible to perform a test to distinguish between microstates HT and TH? One might be tempted to say yes, because you could simply do this by looking at the order of Hs and Ts in the microstate. In microstate HT, the coin on the left hand side is H; in microstate TH, the same coin is now T, and vice versa for the coin on the right hand side. Hence we could tell the difference between HT and TH. 

This is in fact a fallacious argument. The way we order the coins does not matter because they are identical coins, and we have merely given them *subjective* labels or names in the previous argument. No test can be performed on HT or HT to decide its microstate, because the way we order the coins is merely *subjective* and the *objective* reality, that there are two identical coins with opposing orientations, is the same for both microstates. 

A more physics-y example is the case of two electrons moving apart, one travelling to the left and one travelling to the right. Since electrons are *indistinguishable* i.e. identical, it is meaningless to say electron A is travelling to the left and electron B is travelling to the right, since the labels A and B are simply subjective ways of indexing the electrons; another experimentalist might call what was known as A to be B and vice versa, and it wouldn't make any difference to the objective physical reality, which is simply two electrons moving apart horizontally. 

It might be helpful to let this point sink in and slowly digest this idea. HT and TH, despite being distinct microstates, describe the same objective fact. 

This might be a more objective way of tabulating the results:

| $h$ | prob($h$) | $\Omega(h)$ |
| :--: :--: | :--: |
| 2H0T | $1/4$ | 1 |
| 1H1T | $1/2$ | 2 |
| 0H2T | $1/4$ | 1 |
| ------- |

where $\Omega(h)$ denotes the number of microstates corresponding to each $h$, or *macrostate*. 

{% include callout.html content="The *macrostates* of a system expresses the objective facts of the system. Unlike microstates, macrostates need not have the same probability, because multiple microstates could correspond to the same macrostate. The macrostate with the largest number of corresponding microstates is the most likely macrostate of the system." type="info" %} 









{% include links.html %}
