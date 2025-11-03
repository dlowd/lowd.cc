---
title: "Research"
aliases: ["research.html"]
ShowToc: true
---

My research spans multiple facets of machine learning, united by the goal of creating reliable, trustworthy, and efficient models.

### Adversarial Machine Learning

I study how machine learning systems can be attacked and how to defend them. Early work with Chris Meek at Microsoft Research showed how a determined adversary can subvert spam filters by sprinkling in ``good'' words, a strategy that generalizes to many other classifiers ([CEAS 2005](/files/ceas05lowd.pdf), [KDD 2005](/files/kdd05lowd.pdf)).  

More recent projects explore robustness for structured prediction and collective inference. We developed CACC, a collective classification algorithm that maintains accuracy even when features are adversarially manipulated ([ICML 2013](/files/icml13torkamani.pdf)), and proved that adversarial robustness and regularization are two sides of the same coin for structured prediction ([ICML 2014](/files/icml14torkamani.pdf)). Our group continues to build certified defenses for modern learning systems, including recent work on robust regression ([SaTML 2023](/files/hammoudeh-satml23.pdf)) and influence estimation ([CCS 2022](/files/hammoudeh-ccs22.pdf)).

### Learning for Efficient Inference

Exact inference in graphical models is typically intractable, but with the right structure we can make learning and inference tractable without sacrificing accuracy. I have developed algorithms that learn tractable models directly, from mixtures of naïve Bayes networks ([ICML 2005](/files/icml05lowd.pdf)) to arithmetic circuits ([UAI 2008](/files/uai08lowd.pdf), [AISTATS 2013](/files/aistats13lowd-fixed.pdf))).  

Our work with sum-product networks shows how to combine structured learning with circuit representations to outperform many traditional Bayesian network approaches ([ICML 2014](/files/icml14rooshenas.pdf)). We also study how to approximate intractable models using tractable surrogates while preserving predictive power ([NeurIPS 2010](/files/nips10lowd.pdf)).

### Statistical Relational Learning

Many real-world problems involve networks, uncertain relationships, and richly structured data. Statistical relational learning merges first-order logic with probability to tackle these settings. I have helped design new representations such as Recursive Random Fields ([IJCAI 2007](/files/ijcai07lowd.pdf)) and efficient weight-learning algorithms for Markov logic networks ([PKDD 2007](/files/pkdd07lowd-fixed2.pdf))).  

Collaborations with students and colleagues continue to push relational learning forward, including applying quadratic optimization to inference and leveraging causal independence for richer models.

## Software

- [Libra toolkit](https://libra.cs.uoregon.edu) — Exact and approximate inference for Bayesian and Markov networks, plus structure learning.  
- [NBE](https://www.cs.washington.edu/ai/nbe/) — Efficient probability estimation using mixture models.  
- Code and supplementary material for many publications are linked directly from the [publications page](/publications/).

## Collaborations and Support

My group works closely with researchers across AI, security, and data science. Projects are supported by agencies such as DARPA, NSF, ARO, and industry partners including Google and Microsoft. I am always interested in new collaborations that explore reliable and responsible machine learning.
