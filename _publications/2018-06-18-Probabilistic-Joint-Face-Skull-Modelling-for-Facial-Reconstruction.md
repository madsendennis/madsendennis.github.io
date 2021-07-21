---
title: "Probabilistic Joint Face-Skull Modelling for Facial Reconstruction"
collection: publications
permalink: /publication/2018-06-18-Probabilistic-Joint-Face-Skull-Modelling-for-Facial-Reconstruction
date: '2018-06-18'
venue: 'Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)'
authors: 'Dennis Madsen, Marcel Lüthi, Andreas Schneider, and Thomas Vetter'
paperurl: 'http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/3236.pdf'
poster: '/files/madsen_cvpr2018_poster_rfs.pdf'
img: '/images/publications/2018_CVPR_faceskull.png'
---

[//]: <> <a href='/files/madsen_miss2018_poster_rfs.pdf'>Download MISS 2018 poster</a>
<br>

# Abstract
We present a novel method for co-registration of two independent
statistical shape models. We solve the problem of
aligning a face model to a skull model with stochastic optimization
based on Markov Chain Monte Carlo (MCMC).
We create a probabilistic joint face-skull model and show
how to obtain a distribution of plausible face shapes given
a skull shape. Due to environmental and genetic factors,
there exists a distribution of possible face shapes arising
from the same skull. We pose facial reconstruction as a conditional
distribution of plausible face shapes given a skull
shape. Because it is very difficult to obtain the distribution
directly from MRI or CT data, we create a dataset of artificial
face-skull pairs. To do this, we propose to combine
three data sources of independent origin to model the joint
face-skull distribution: a face shape model, a skull shape
model and tissue depth marker information. For a given
skull, we compute the posterior distribution of faces matching
the tissue depth distribution with Metropolis-Hastings.
We estimate the joint face-skull distribution from samples of
the posterior. To find faces matching to an unknown skull,
we estimate the probability of the face under the joint faceskull
model. To our knowledge, we are the first to provide
a whole distribution of plausible faces arising from a skull
instead of only a single reconstruction. We show how the
face-skull model can be used to rank a face dataset and
on average successfully identify the correct match in top
30%. The face ranking even works when obtaining the face
shapes from 2D images. We furthermore show how the faceskull
model can be useful to estimate the skull position in an
MR-image.