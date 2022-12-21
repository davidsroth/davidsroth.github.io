---
layout: page
title: Variations and Relaxations of Normalizing Flows
description: This paper covers model classes that emerge from relaxing invertibility contraints in normalizing flows, and  explores their relationship to VAEs, score-based diffusion and the broader family of generative models.
# img: assets/img/GraphSAGE_Model_Diagram.png
importance: 5
category: work
pdf: RelaxingNFs.pdf
---

Normalizing Flows (NFs) describe a class of models that express a complex target distribution as the composition of a series of bijective transformations over a simpler base distribution. By limiting the space of candidate transformations to diffeomorphisms (bijective, forward and reverse differentiable functions), NFs enjoy efficient, exact sampling and density evaluation, enabling them to flexibly behave as both discriminative and generative models. This survey covers a selection of recent works that combine aspects of other generative model classes, such as VAEs and diffusion, and in doing so loosen the strict bijectivity constraints of NFs to achieve a balance of expressivity, training speed, sample efficiency and likelihood tractability.