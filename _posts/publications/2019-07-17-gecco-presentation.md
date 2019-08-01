---
layout: page
#
# Content
#

subheadline: "Spatial Evolutionary Generative Adversarial Networks paper presented in GECCO 2019"
title: "Mustangs presented in GECCO 2019"
teaser: "My colleagues were at GECCO 2019 presenting our last  research about evolutionary computing, including of course, Mustangs."
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
image: 
#    title: mediaplayer_js-title.jpg
    thumb: gecco2019-logo.jpg
    homepage: brussels_header.jpg
#    caption: Photo by Corey Blaz
#    caption_url: https://blaz.photography/
mediaplayer: false
---






****

Last week We [GECCO 2019](https://gecco-2019.sigevo.org/ "GECCO 2019") was held in Prague and my colleagues from ALFA went there to present some of our exiting research about evolutionary computation. 


A paper about our **Mustangs** framework, which is one of the pillars on which NeCOL is based, was accepted as full paper to be presented in this event.
Mustangs is about fostering diversity when training generative adversarial networks applying a coevolutionary method to improve the training process.   
The paper is entitled *Spatial Evolutionary Generative Adversarial Networks* and it can be downloaded from [*here*](http://alfagroup.csail.mit.edu/sites/default/files/documents/2019Spatial_Evolutionary_Generative_Adversarial_Networks.pdf "FULL PAPER").  

[Erik Hemberg](https://alfagroup.csail.mit.edu/erik "Erik") was in charge to present this work to the audience, that showed a lot of interest during the session.  We had very fruitful feedback, which would open new and excited research lines.

The *presentation* can be downloaded from [*here*](https://jamaltoutouh.github.io/downloads/GECCO-2019-Mustangs)

As we are working in this interesting project for Deep Learning community, we will be able to report new, stimulating, and remarkable results in short period of time.


---

### Spatial Evolutionary Generative Adversarial Networks
#### Abstract
Generative adversary networks (GANs) suffer from training pathologies such as instability and mode collapse. These pathologies mainly arise from a lack of diversity in their adversarial interactions. Evolutionary generative adversarial networks apply the principles of evolutionary computation to mitigate these problems. We hybridize two of these approaches that promote training diversity. One, E-GAN, at each batch, injects mutation diversity by training the (replicated) generator with three independent objective functions then selecting the resulting best performing generator for the next batch. The other, Lipizzaner, injects population diversity by training a two-dimensional grid of GANs with a distributed evolutionary algorithm that includes neighbor exchanges of additional training adversaries, performance based selection and population-based hyper-parameter tuning. We propose to combine mutation and population approaches to diversity improvement. We contribute a superior evolutionary GANs training method, Mustangs, that eliminates the single loss function used across Lipizzaner ’s grid. Instead, each training round, a loss function is selected with equiprobability, from among the three E-GAN uses. Experimental analyses on a standard benchmark, MNIST, demonstrate that Mustangs provides a statistically faster training method resulting in more accurate networks.

 
