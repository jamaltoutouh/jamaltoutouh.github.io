---
layout: page
#
# Content
#

subheadline: "We introduced our Mustangs approach to the community that accepted to live under a GANocracy"
title: "Presenting Mustangs at GANocracy"
teaser: "GANocracy focused on the promise of GANs and includeed discussion of how we can exploit their benefits while minimizing their potential harm. "
categories:
  - publications
tags:
  - publication
  - innovative teaching
  - jamal
  - GANs
  - Mustangs
#
# Styling
#
header: no
image: 
    title: ganocracy-main.png
    thumb: ganocracy-main.png
#    homepage: mediaplayer_js-home.jpg
#    caption: Photo by Corey Blaz
#    caption_url: https://blaz.photography/
mediaplayer: false
---

We presented a poster entitled **Coevolutionary GANs Training to Foster Diversity**, in which we summarized the Mustangs approach and its main results. [*Download the poster*](https://jamaltoutouh.github.io/downloads/Mustangs-GANocracy.pdf). 

### Abstract of our work
Generative adversarial networks (GANs) training may be formulated as a minmax optimization problem through the definitions of discriminator and generator loss. However, this process rarely converges to an equilibrium, since GAN training dynamics suffer from pathologies exhibiting degenerate behaviors, such as mode and discriminator collapses.

Competitive coevolutionary algorithms address optimization problems in which individuals (solutions) that belong to adversarial populations are assessed according to the interactions against their adversaries. These algorithms show pathologies similar to what is reported in GANs training, which mainly arise from a lack of diversity in their adversarial interactions. We propose the Mustangs, which uses a spatial distributed coevolutionary algorithm to evolve two populations of discriminators and generators on a spatial grid designed to foster diversity during the training. For each iteration, each network randomly picks a loss function to optimize its weights according to different objectives to increase the diversity.

Experimental analyses on image benchmarks demonstrate that Mustangs has high performance due to its inherent robustness provided by keeping diversity during the training process. This allows it to overcome often observed training pathologies. Furthermore, as the Mustangs method can be executed asynchronously, the computation is easy to distribute with low overhead.