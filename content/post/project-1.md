---
date: 2022-06-20T10:58:08-04:00
description: "Master's Thesis in Statistics and Machine Learning - Linköpings Universitet"
featured_image: "/images/antennas.jpg"
tags: ["MIMO", "Variational Autoencoders", "PPCA", "Deep Learning", "Machine Learning", "Channel Prediction Wireless", "AI"]
title: "ML-aided Cross-Band Channel prediction in MIMO systems | Alejo Pérez"
---
# Abstract

The wireless communications technologies have experienced an exponential development
during the last decades. 5G is a prominent exponent whose one of its crucial
components is the Massive MIMO technology. By supporting multiple streams of signals
it allows a revamped signal reconstruction in terms of mobile traffic size, data rate,
latency and reliability. In this thesis work, we isolated this technology into a SIMO
approach (Single-Input Multiple-Output) to explore a Machine Learning modeling to address
the so-called Channel Prediction problem. Generally, the algorithms available to
perform Channel Estimation in FDD and TDD deployments incur computational complexity
downsides and require explicit feedback from client devices, which is typically
prohibitive.
{{< figure src="/images/vae-gaussian.png" >}}

[Link to Thesis](https://liu.diva-portal.org/smash/record.jsf?pid=diva2:1673803)

[Link to Repository](https://github.com/alejo-perez-upc-77/CrossBand_ChannelPrediction_MasterThesis)

This thesis work focuses on Channel Prediction by aims of employing Machine and
Deep Learning models in order to reduce the computational complexity by further relying
in statistical modeling/learning. We explored the cross-Frequency Subband prediction
intra-TTI (Transmission Time Interval) by means of proposing 3 three models. These
intended to leverage frequency Multipath Components dependencies along TTIs. The
first two ones are Probabilistic Principal Components Analysis (PPCA) and its Bayesian
counterpart, Bayesian Principal Components Analysis (BPCA). Then, we implemented
a Deep Learning Variational Encoder-Decoder (VED) architecture. These three models
intended to deal with the hugely high-dimensional space of the 4 datasets used by its
intrinsic dimensionality reduction. The PPCA method was in average five times better
than the VED alternative in terms of MSE accounting for all the datasets used.

