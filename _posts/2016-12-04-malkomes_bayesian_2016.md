---
title: Bayesian optimization for automated model selection
abstract: Despite the success of kernel-based nonparametric methods, kernel selection
  still requires considerable expertise, and is often described as a “black art.”
  We present a sophisticated method for automatically searching for an appropriate
  kernel from an infinite space of potential choices. Previous efforts in this direction
  have focused on traversing a kernel grammar, only examining the data via computation
  of marginal likelihood. Our proposed search method is based on Bayesian optimization
  in model space, where we reason about model evidence as a function to be maximized.
  We explicitly reason about the data distribution and how it induces similarity between
  potential model choices in terms of the explanations they can offer for observed
  data. In this light, we construct a novel kernel between models to explain a given
  dataset. Our method is capable of finding a model that explains a given dataset
  well without any human assistance, often with fewer computatio! ns of model evidence
  than previous approaches, a claim we demonstrate empirically.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: malkomes_bayesian_2016
month: 0
tex_title: Bayesian optimization for automated model selection
firstpage: 41
lastpage: 47
page: 41-47
order: 41
cycles: false
author:
- given: Gustavo
  family: Malkomes
- given: Chip
  family: Schaff
- given: Roman
  family: Garnett
date: 2016-12-04
address: 
publisher: PMLR
container-title: Proceedings of the Workshop on Automatic Machine Learning
volume: '64'
genre: inproceedings
issued:
  date-parts:
  - 2016
  - 12
  - 4
pdf: http://proceedings.mlr.press/v64/malkomes_bayesian_2016.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
