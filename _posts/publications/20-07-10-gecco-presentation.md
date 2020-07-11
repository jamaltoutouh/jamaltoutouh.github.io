---
layout: page
#
# Content
#

subheadline: "Our study about generative modelling by using Evolutionar Ensemple Learning presented in GECCO 2020"
title: "Effective ensmebles of GANs in GECCO 2020"
teaser: "During this on-line GECCO 2020, we have presented our research work about using Evolutionary Ensemble Learning to address mode collapse in GANs."
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
    title: blog/gecco2020_slide1.PNG
    thumb: gecco2019-logo.jpg
    homepage: brussels_header.jpg
#    caption: Photo by Corey Blaz
#    caption_url: https://blaz.photography/
mediaplayer: false
---

****

This year COVID-19 has not allowed us to meet in person with our colleagues of the evolutionary computing community, but this has not prevented us from organizing and assisting the amazing sessions and workshops that GECCO offers us every year.

During this on-line GECCO 2020, we have presented one of our last research works related to GANs. In this case, we have presented our paper entitled [**Re-purposing Heterogeneous Generative Ensembles with Evolutionary Computation**](https://arxiv.org/abs/2003.13532) in which we define a new way to use Evolutionary Ensemble Learning (EEL) in such kind of special machine learning approach.

![GANs](https://jamaltoutouh.github.io/images/blog/gecco2020_slide3.PNG "GANs")

The main idea behind this paper is to take advantage of already pre-trained heterogeneous generators according to a given loss function (optimization problem) to combine them (create mixtures of generators) in such a way that they are able to address a new optimization problem. In this case, we took 3,000 generators optimized according to the sample generation quality (FID score) and we optimized the diversity of the generated samples to address mode collapse.
In order to do so, we defined the **Ensemble Optimization Problem** and we addressed by using two different evolutionary approaches based on **Genetic Algorithms**.
The *presentation* can be downloaded from [*here*](https://jamaltoutouh.github.io/downloads/presentations/gecco2020_repurposing_gans.pdf)

![GANs](https://jamaltoutouh.github.io/images/blog/gecco2020_slide19.PNG "GANs")

As we are working in this interesting project for Deep Learning community, we will be able to report new, stimulating, and remarkable results in short period of time.


---

### Re-purposing Heterogeneous Generative Ensembles with Evolutionary Computation
#### Abstract
Generative Adversarial Networks (GANs) are popular tools for generative modeling. The dynamics of their adversarial learning give rise to convergence pathologies during training such as mode and discriminator collapse. In machine learning, ensembles of predictors demonstrate better results than a single predictor for many tasks. In this study, we apply two evolutionary algorithms (EAs) to create ensembles to re-purpose generative models, i.e., given a set of heterogeneous generators that were optimized for one objective (e.g., minimize Frechet Inception Distance), create ensembles of them for optimizing a different objective (e.g., maximize the diversity of the generated samples). The first method is restricted by the exact size of the ensemble and the second method only restricts the upper bound of the ensemble size. Experimental analysis on the MNIST image benchmark demonstrates that both EA ensembles creation methods can re-purpose the models, without reducing their original functionality. The EA-based demonstrate significantly better performance compared to other heuristic-based methods. When comparing both evolutionary, the one with only an upper size bound on the ensemble size is the best.



 
