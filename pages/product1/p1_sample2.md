---
title: Microstates, meet Macrostate
keywords: sample
summary: "Understanding microstates and macrostates."
sidebar: product1_sidebar
permalink: p1_sample2.html
folder: product1
---

## Let's flip some coins

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

This is in fact a fallacious argument. The way we order the coins does not matter because they are identical coins, and we have merely given them *subjective* labels or names in the previous argument. No test can be performed on HT or HT to decide its microstate, because the way we order the coins is merely *subjective* and the *objective* reality, that there are two identical coins with opposing orientations, is the same for both microstates. [^electron] 

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




[^ electron]: A more physics-y example is the case of two electrons moving apart, one travelling to the left and one travelling to the right. Since electrons are *indistinguishable* i.e. identical, it is meaningless to say electron A is travelling to the left and electron B is travelling to the right, since the labels A and B are simply subjective ways of indexing the electrons; another experimentalist might call what was known as A to be B and vice versa, and it wouldn't make any difference to the objective physical reality, which is simply two electrons moving apart. 
## More sample content

Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.

The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.

There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.

{% include links.html %}
