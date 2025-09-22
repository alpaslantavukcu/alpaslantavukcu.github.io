---
title: "Examining the Portability of Deep Learning Runtime Optimization Methods"
collection: publications
category: conferences
permalink: /publication/2025-06-25-examining-the-portability-of-dl-opt-methods
excerpt: ''
date: 2025-06-25
venue: '33rd Signal Processing and Communications Applications Conference (SIU)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11111816'
citation: 'M. A. Tavukçu and A. Yılmazer-Metin, "Examining the Portability of Deep Learning Runtime Optimization Methods," 2025 33rd Signal Processing and Communications Applications Conference (SIU), Sile, Istanbul, Turkiye, 2025, pp. 1-4, doi: 10.1109/SIU66497.2025.11111816.'
---

Computational graph level optimizations are highly utilized to reduce the runtime of deep learning models. The effectiveness of these optimization methods depends on their cost (runtime) model and the target runtime environment. In this study, we analyzed the behavior of existing optimization tools cost models across different runtime environments, examining their performance portability. Our analysis demonstrates that optimizations performed using a cost model developed for a specific runtime environment cannot be directly transferred to a different runtime environment. Optimizations that yield performance improvements in one environment may result in performance degradation in another. Based on these findings, we determined that to make optimization methods viable on widely used tools such as ONNX Runtime, the cost model must be aligned with the performance characteristics of the relevant tool. To address this inconsistency, we trained Graph Neural Networks that predict the runtime of computational graphs. We established that when optimization is performed by replacing existing cost models with trained cost predictors, more consistent optimizations can be achieved.
