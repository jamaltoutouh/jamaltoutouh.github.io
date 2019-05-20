---
layout: page
#
# Content
#

subheadline: "See you in Prague!!!"
title: "GECCO Paper Accepted"
teaser: "We have received quite positive feedback from the reviewing process and we will present Mustangs in GECCO 2019."
categories:
  - publications
tags:
  - publication
  - gecco
  - jamal
  - gan
#
# Styling
#
header: no
#image: 
#    title: mediaplayer_js-title.jpg
#    thumb: mediaplayer_js-thumb.jpg
#    homepage: mediaplayer_js-home.jpg
#    caption: Photo by Corey Blaz
#    caption_url: https://blaz.photography/
mediaplayer: false
---

We are happy to inform that our paper *Spatial Evolutionary Generative Adversarial Networks* has been accepted as a FULL PAPER to be presented during [GECCO 2019](https://gecco-2019.sigevo.org/ "GECCO 2019"). GECCO is one of the most important conferences in the field of evolutionary computation.

### Spatial Evolutionary Generative Adversarial Networks
#### Abstract
Generative adversary networks (GANs) suffer from training pathologies such as instability and mode collapse. These pathologies mainly arise from a lack of diversity in their adversarial interactions. Evolutionary generative adversarial networks apply the principles of evolutionary computation to mitigate these problems. We hybridize two of these approaches that promote training diversity. One, E-GAN, at each batch, injects mutation diversity by training the (replicated) generator with three independent objective functions then selecting the resulting best performing generator for the next batch. The other, Lipizzaner, injects population diversity by training a two-dimensional grid of GANs with a distributed evolutionary algorithm that includes neighbor exchanges of additional training adversaries, performance based selection and population-based hyper-parameter tuning. We propose to combine mutation and population approaches to diversity improvement. We contribute a superior evolutionary GANs training method, Mustangs, that eliminates the single loss function used across Lipizzaner ’s grid. Instead, each training round, a loss function is selected with equiprobability, from among the three E-GAN uses. Experimental analyses on a standard benchmark, MNIST, demonstrate that Mustangs provides a statistically faster training method resulting in more accurate networks.

 
