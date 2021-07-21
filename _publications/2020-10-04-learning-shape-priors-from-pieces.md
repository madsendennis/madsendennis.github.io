---
title: "Learning Shape Priors from Pieces"
collection: publications
permalink: /publication/2020-10-04-learning-shape-priors-from-pieces
date: '2020-10-04'
venue: 'ShapeMi: Shape in Medical Imaging (MICCAI workshop)'
authors: 'Dennis Madsen, Jonathan Aellen, Andreas Morel-Forster, Thomas Vetter and Marcel Lüthi'
paperurl: 'http://gravis.dmi.unibas.ch/publications/2020/2020_Madsen_LearningShapePriorsFromPieces.pdf'
code: 'https://github.com/unibas-gravis/shape-priors-from-pieces'
video: 'https://www.youtube.com/watch?v=YqFhwr8VFOs'
img: '/images/publications/2020_SHAPEMI_imputations.png'
---

<br>

# Abstract
Point Distribution Models (PDM) require a dataset in which point-to-point correspondence between the individual shapes has been established. However, in the medical domain, minimising radiation exposure and pathological deformations are reasons why healthy anatomies are often only available as partial observations. To exploit the partial shapes for learning shape models, previous methods required at least a few complete shapes and, either a robust registration method or a robust learning algorithm. Our proposed method implements the idea of multiple imputations from Bayesian statistics. We learn a PDM from a dataset consisting of only incomplete shapes and a single full template. For this, we first estimate the posterior distribution of point-to-point registrations for each partial observation. Then we construct the PDM from the set of registration distributions. We quantitatively evaluate our method on a 2D dataset of hands and a 3D dataset of femurs with known ground-truth. Furthermore, we showcase how to use our method on only partial clinical data to build a 3D statistical model of the human skull. The code is made open-source and the synthetic dataset publicly available.