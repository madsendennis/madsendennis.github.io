---
title: "A Probabilistic Surface Registration Framework with Applications to Partial Data Analysis"
collection: publications
permalink: /publication/2021-07-12-A Probabilistic Surface Registration Framework with Applications to Partial Data Analysis
date: '2021-07-12'
venue: 'PhD Thesis'
authors: 'Dennis Madsen'
paperurl: 'https://edoc.unibas.ch/85938/1/phd_thesis_dennis-madsen_edoc.pdf'
video: 'https://www.youtube.com/watch?v=QEC_pzB3hiA'
img: '/images/publications/2021_phd.png'
slides: '/files/PhD-defense-2021.pptx'
---

<br>

# Abstract
The usage of Point Distribution Models (PDMs) is very attractive, especially in medical imaging analysis. This is due to their simplicity, robustness, and the relatively low number of data items needed for their construction. When a PDM is used to analyze a novel image one can automatically extract measures from it, the likelihood of the target shape can be estimated or it can be used to complete partial observations. The most important aspect of constructing PDMs and analyzing novel data is how to establish point-to-point correspondence. Previous work mainly relies on the underlying assumption that exactly one optimal correspondence exists. Particularly when partial data is completed, the established correspondence has a big influence and can result in incorrect reconstructions.

In this thesis, we introduce a generalized probabilistic non-rigid registration framework. We build upon the Gaussian Process Morphable Model (GPMM) framework, which clearly separates prior deformation information from the general registration algorithm. We view non-rigid surface registration as a probabilistic inference problem. This leads us to a distribution of registrations from a specific target. More importantly, the distribution does not rely on any hard correspondence assumption. Instead of settling on one specific correspondence assumption, our method takes all the different correspondence pairs into account.

The thesis is divided into 3 main parts: first we introduce GiNGR, which is a generalized iterative non-rigid surface registration framework that unifies previous algorithms such as Iterative Closest Point (ICP) and Coherent Point Drift (CPD) under the same non-rigid registration framework. We then show how we can use GiNGR to make existing registration algorithms probabilistic in comparison to their deterministic nature. We empirically show how a simple ICP method benefits from the probabilistic framework by becoming more robust and able to quantify the registration uncertainty.
  
Finally, we show several applications of the probabilistic registration framework by analyzing partial data and how PDMs can be constructed from partial data with different properties using multiple imputations.