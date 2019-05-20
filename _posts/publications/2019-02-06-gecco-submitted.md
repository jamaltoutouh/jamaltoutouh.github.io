---
layout: page
#
# Content
#

subheadline: "Spatial Evolutionary Generative Adversarial Networks submitted to GECCO 2019"
title: "Paper Submitted to GECCO"
teaser: "We have finished writing a nice paper about fosterring diversity in coevolutionary algorithms to train GANs."
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

We are glad to inform that we have been able to prepare and show some interesting results about our research in fostering diversity when training genertive adversarial networks applying a coevolutionary mehtod. In this case, we have increased the diversity by applying different mutation operators (loss functions) during the trainig process. The proposed framework is named **Mustangs** and the paper is entitled *Spatial Evolutionary Generative Adversarial Networks*. We will be really happy if we are able to present the paper during [GECCO 2019](https://gecco-2019.sigevo.org/ "GECCO 2019"). 

---

### Spatial Evolutionary Generative Adversarial Networks
#### Abstract
Generative adversary networks (GANs) suffer from training pathologies such as instability and mode collapse. These pathologies mainly arise from a lack of diversity in their adversarial interactions. Evolutionary generative adversarial networks apply the principles of evolutionary computation to mitigate these problems. We hybridize two of these approaches that promote training diversity. One, E-GAN, at each batch, injects mutation diversity by training the (replicated) generator with three independent objective functions then selecting the resulting best performing generator for the next batch. The other, Lipizzaner, injects population diversity by training a two-dimensional grid of GANs with a distributed evolutionary algorithm that includes neighbor exchanges of additional training adversaries, performance based selection and population-based hyper-parameter tuning. We propose to combine mutation and population approaches to diversity improvement. We contribute a superior evolutionary GANs training method, Mustangs, that eliminates the single loss function used across Lipizzaner ’s grid. Instead, each training round, a loss function is selected with equiprobability, from among the three E-GAN uses. Experimental analyses on a standard benchmark, MNIST, demonstrate that Mustangs provides a statistically faster training method resulting in more accurate networks.

 
