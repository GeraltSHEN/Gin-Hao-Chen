---
title: "Physics-informed neural networks with hard linear equality constraints"
collection: publications
category: manuscripts
#permalink: /publication/2024-02-17-paper-title-number-4
#excerpt: 'Strictly enforce hard linear equality constraints in neural network'
date: 2024-10-01
venue: 'Computers & Chemical Engineering'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0098135424001820'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
citation: 'Chen, H., Constante-Flores, G., Li, C. Physics-informed neural networks with hard linear equality constraints.Computers & Chemical Engineering 189,108764. (2024).'
---

Surrogate modeling is used to replace computationally expensive simulations. Neural networks have been widely applied as surrogate models that enable efficient evaluations over complex physical systems. Despite this, neural networks are data-driven models and devoid of any physics. The incorporation of physics into neural networks can improve generalization and data efficiency. The physics-informed neural network (PINN) is an approach to leverage known physical constraints present in the data, but it cannot strictly satisfy them in the predictions. This work proposes a novel physics-informed neural network, KKT-hPINN, which rigorously guarantees hard linear equality constraints through projection layers derived from KKT conditions. Numerical experiments on Aspen models of a continuous stirred-tank reactor (CSTR) unit, an extractive distillation subsystem, and a chemical plant demonstrate that this model can further enhance the prediction accuracy.
