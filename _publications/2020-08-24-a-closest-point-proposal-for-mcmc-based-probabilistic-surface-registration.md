---
title: "A Closest Point Proposal for MCMC-based Probabilistic Surface Registration"
collection: publications
permalink: /publication/2020-08-24-a-closest-point-proposal-for-mcmc-based-probabilistic-surface-registration
excerpt: 'We compute the posterior distribution of possible surface registrations.'
date: '2020-08-24'
venue: 'Proceedings of the European Conference on Computer Vision (ECCV)'
paperurl: 'https://arxiv.org/pdf/1907.01414v1'
citation: 'Dennis Madsen*, Andreas Morel-Forster*, Patrick Kahr, Dana Rahbani, Thomas Vetter and Marcel Lüthi'
---

<a href='https://www.youtube.com/watch?v=ge4LYNAVB2c'>ECCV2020 teaser</a>
<br>
<a href='https://www.youtube.com/watch?v=2cQkskTqdOM'>ECCV2020 presentation</a>
<br>
<a href='/files/madsen_cvpr2018_poster_rfs.pdf'>Code</a>

# Abstract
We propose to view non-rigid surface registration as a probabilistic inference problem. Given a target surface, we estimate the posterior distribution of surface registrations. We demonstrate how the posterior distribution can be used to build shape models that generalize better and show how to visualize the uncertainty in the established correspondence. Furthermore, in a reconstruction task, we show how to estimate the posterior distribution of missing data without assuming a fixed point-to-point correspondence.
We introduce the closest-point proposal for the Metropolis-Hastings algorithm. Our proposal overcomes the limitation of slow convergence compared to a random-walk strategy. As the algorithm decouples inference from modeling the posterior using a propose-and-verify scheme, we show how to choose different distance measures for the likelihood model.
All presented results are fully reproducible using publicly available data and our open-source implementation of the registration framework.