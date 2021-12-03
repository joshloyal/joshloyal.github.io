---
layout: page
permalink: /research/
order: 2
title: Research
nav: true
---

My research interests include

* **Statistical inference for networks**: latent space models, community detection, dynamic and multilayer networks, Bayesian inference.

* **Statistical learning and data science**: classification, regression, dimension reduction, clustering, visualization, random forests and trees, deep learning.

* **Bayesian methodology**: Monte Carlo methods, variational inference, Bayesian nonparametrics, scalable computation.

<br>

#### Statistical Network Analysis

Modeling the dynamics of complex social systems is an essential component of many applied problems. To understand the formation and dissolution of international alliances, predict regional conflicts such as the Arab Spring and the emergence of ISIS, and forecast the trajectory of infectious disease spread throughout a community, we need models of each complex system’s dynamics. As such, my research develops statistical models that infer vital characteristics within the observed dynamics of complex systems. My work in this area focuses in addressing estimation and inference problems by exploiting low-dimensional representations using a combination of latent space models, hidden Markov models, linear dynamical systems, and Bayesian inference. I have developed new statistical models for analyzing dynamic and multilayer networks, including methodology for community detection, prediction, forecasting, and the estimation of missing data. I have also introduced widely applicable variational inference procedures that allow for estimation in large networks.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid" src="{{ '/assets/img/alliances_ls.jpeg' | relative_url }}" alt="" title="International alliance networks during the Cold War"/>
    </div>
</div>
<div class="caption">
   Inferred node embeddings and community structure for a network of international alliances during the Cold War.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid" src="{{ '/assets/img/icews_latent_color.png' | relative_url }}" alt="" title="International alliance networks during the Cold War"/>
    </div>
</div>
<div class="caption">
    Network embeddings before and during the conflict in Crimea between Ukraine and Russia
    <a href="/assests/gif/russia_ukraine.gif">[GIF 1]</a>
    <a href="/assests/gif/icews.gif">[GIF 2]</a>.
</div>

**References**

* *Loyal, J.D.*, Chen, Y. (2021). **A Bayesian nonparametric latent space approach to modeling evolving communities in dynamic networks**. Accepted at *Bayesian Analysis*.
[[preprint]](https://arxiv.org/abs/2003.07404) [[code]](https://github.com/joshloyal/dynetlsm)

* *Loyal, J.D.*, Chen, Y. (2021). **An eigenmodel for dynamic multilayer networks**. Under review.
[[preprint]](https://arxiv.org/abs/2103.12831) [[code]](https://github.com/joshloyal/multidynet)

* *Loyal, J.D.*, Chen, Y. (2020). **Statistical network analysis: A review with applications to the coronavirus 2019 pandemic**. Accepted at *International Statistical Review*.
[[article]](https://onlinelibrary.wiley.com/doi/full/10.1111/insr.12398)

<br>

#### Statistical Learning and Data Science

Modern problems in statistical learning and data science are increasingly concerned with interpreting the results of powerful black-box estimators. For example, fields such as personalized medicine, policy-making, and bioinformatics currently require flexible estimators that can infer variable importance and reduce the dimension of the problem. My past work has exploited local low-dimensional structure in the data to provide interpretable solutions without losing flexibility. Specifically, I developed new techniques to infer local variable importance by using a combination of random forests and sufficient dimension reduction. Such local variable importance measures have applications in personalized medicine where the ability to tailor medical treatment to patients based on their unique genetic makeup can drastically decrease patient mortality.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid" src="{{ '/assets/img/kernel_comp.jpeg' | relative_url }}" alt="" title=""/>
    </div>
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid" src="{{ '/assets/img/local_svi.jpeg' | relative_url }}" alt="" title=""/>
    </div>
</div>
<div class="caption">
   Induced kernel and local subspace variable importance from a dimension reduction forest.
</div>

**References**:

* *Loyal, J.D.*, Zhu, R., Cui, Y., and Zhang, X. (2021). **Dimension reduction forests: Local variable importance using structured random forests**. In revision.
[[preprint]](https://arxiv.org/abs/2103.13233) [[code]](https://github.com/joshloyal/drforest)
