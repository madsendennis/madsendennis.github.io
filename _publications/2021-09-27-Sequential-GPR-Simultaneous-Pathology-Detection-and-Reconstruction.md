---
title: "Sequential Gaussian Process Regression for Simultaneous Pathology Detection and Shape Reconstruction"
collection: publications
permalink: /publication/2021-09-27-Sequential-GPR-Simultaneous-Pathology-Detection-and-Reconstruction
date: '2021-09-27'
venue: 'International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)'
authors: 'Dana Rahbani, Andreas Morel-Forster, Dennis Madsen, Jonathan Aellen, and Thomas Vetter'
paperurl: 'https://link.springer.com/chapter/10.1007%2F978-3-030-87240-3_41'
img: '/images/publications/2021_MICCAI_Dana.png'
video: 'https://www.youtube.com/watch?v=0HZWnG_ZPCw'
---

<br>

# Abstract
In this paper, we view pathology segmentation as an outlier detection task. Hence no prior on pathology characteristics is needed, and we can rely solely on a statistical prior on healthy data. Our method is based on the predictive posterior distribution obtained through standard Gaussian process regression. We propose a region-growing strategy, where we incrementally condition a Gaussian Process Morphable Model on the part considered healthy, as well as a dynamic threshold, which we infer from the uncertainty remaining in the resulting predictive posterior distribution. The threshold is used to extend the region considered healthy, which in turn is used to improve the regression results. Our method can be used for detecting missing parts or pathological growth like tumors on a target shape. We show segmentation results on a range of target surfaces: mandible, cranium and kidneys. The algorithm itself is theoretically sound, straight-forward to implement and extendable to other domains such as intensity-based pathologies. Our implementation is made open source with the publication.