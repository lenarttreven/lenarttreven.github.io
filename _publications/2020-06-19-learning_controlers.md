---
title: "Learning Controllers for Unstable Linear Quadratic Regulators from a Single Trajectory"
authors: "L. Treven, S. Curi, M. Mutny, A. Krause"
collection: publications
permalink: /publication/2020-06-19-learning_controllers.md
excerpt: 'We present the first approach for learning -- from a single trajectory -- a linear quadratic regulator (LQR), even for unstable systems, without knowledge of the system dynamics and without requiring an initial stabilizing controller. Our central contribution is an efficient algorithm -- emph(eXploration) -- that quickly identifies a stabilizing controller. Our approach utilizes robust System Level Synthesis (SLS), and we prove that it succeeds in a constant number of iterations. Our approach can be used to initialize existing algorithms that require a stabilizing controller as input. When used in this way, it yields a method for learning LQRs from a single trajectory and even for unstable systems, while suffering at most O(sqrt(T)) regret.'
date: 2020-06-19
journal: 'arxiv'
localfile: 'papers/learning_controllers.pdf'
bibtex: 'papers/learning_controllers.bib'
officialurl: 'https://arxiv.org/abs/2006.11022'
citation: 'Treven, L., Curi, S., Mutny, M. and Krause, A., 2020. Learning Controllers for Unstable Linear Quadratic Regulators from a Single Trajectory. arXiv preprint arXiv:2006.11022'
---

## Abstract

We present the first approach for learning -- from a single trajectory -- a linear quadratic regulator (LQR), even for unstable systems, without knowledge of the system dynamics and without requiring an initial stabilizing controller. Our central contribution is an efficient algorithm -- emph(eXploration) -- that quickly identifies a stabilizing controller. Our approach utilizes robust System Level Synthesis (SLS), and we prove that it succeeds in a constant number of iterations. Our approach can be used to initialize existing algorithms that require a stabilizing controller as input. When used in this way, it yields a method for learning LQRs from a single trajectory and even for unstable systems, while suffering at most O(sqrt(T)) regret.