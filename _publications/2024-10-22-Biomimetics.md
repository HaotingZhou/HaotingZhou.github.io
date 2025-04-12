---
title: "A Computationally Efficient Neuronal Model for Collision Detection with Contrast Polarity-Specific Feed-Forward Inhibition"
collection: publications
category: article
permalink: /publication/2024-10-22-olgmd
excerpt: 'This paper introduces an optimized LGMD model with contrast-polarity-specific inhibition to improve collision detection efficiency in embedded robotics.'
date: 2024-10-22
venue: 'Biomimetics'
paperurl: 'https://www.mdpi.com/2313-7673/9/11/650'
slidesurl: ''
bibtexurl: ''
---

## Abstract
Animals utilize their well-evolved dynamic vision systems to perceive and evade collision threats. Driven by biological research, bio-inspired models based on lobula giant movement detectors (LGMDs) address certain gaps in constructing artificial collision-detecting vision systems with robust selectivity, offering reliable, low-cost, and miniaturized collision sensors across various scenes. Recent progress in neuroscience has revealed the energetic advantages of dendritic arrangements presynaptic to the LGMDs, which receive contrast polarity-specific signals on separate dendritic fields. Specifically, feed-forward inhibitory inputs arise from parallel ON/OFF pathways interacting with excitation. However, none of the previous research has investigated the evolution of a computational LGMD model with feed-forward inhibition (FFI) separated by opposite polarity. This study fills this vacancy by presenting an optimized neuronal model where FFI is divided into ON/OFF channels, each with distinct synaptic connections. To align with the energy efficiency of biological systems, we introduce an activation function associated with neural computation of FFI and interactions between local excitation and lateral inhibition within ON/OFF channels, ignoring non-active signal processing. This approach significantly improves the time efficiency of the LGMD model, focusing only on substantial luminance changes in image streams. The proposed neuronal model not only accelerates visual processing in relatively stationary scenes but also maintains robust selectivity to ON/OFF-contrast looming stimuli. Additionally, it can suppress translational motion to a moderate extent. Comparative testing with state-of-the-art based on ON/OFF channels was conducted systematically using a range of visual stimuli, including indoor structured and complex outdoor scenes. The results demonstrated significant time savings in silico while retaining original collision selectivity. Furthermore, the optimized model was implemented in the embedded vision system of a micro-mobile robot, achieving the highest success ratio of collision avoidance at 97.51% while nearly halving the processing time compared with previous models. This highlights a robust and parsimonious collision-sensing mode that effectively addresses real-world challenges.
## Keywords: 
collision detection; ON/OFF channels; feed-forward inhibition; computing efficiency; optimized LGMD; bio-robotics
