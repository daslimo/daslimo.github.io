---
title: "TraNCE: Transformative Nonlinear Concept Explainer for CNNs"
collection: publications
category: manuscripts
permalink: /publication/2025-06-05-TRANCE
excerpt: 'This paper addresses limitations in concept-based explainability with the novel transformative nonlinear concept explainer (TraNCE) for CNN explanation.'
date: 2025-06-05
paperurl: 'https://ieeexplore.ieee.org/document/10966440?source=authoralert'
codeurl: 'https://github.com/daslimo/TrANCE'
citation: 'U. E. Akpudo, Y. Gao, J. Zhou and A. Lewis, "TraNCE: Transformative Nonlinear Concept Explainer for CNNs," in IEEE Transactions on Neural Networks and Learning Systems, vol. 36, no. 6, pp. 10156-10170, June 2025, doi: 10.1109/TNNLS.2025.3556019.'
---

Convolutional neural networks (CNNs) have succeeded remarkably in various computer vision tasks. However, they are not intrinsically explainable. While feature-level understanding of CNNs reveals where the models looked, concept-based explainability methods provide insights into what the models saw. However, their assumption of linear reconstructability of image activations fails to capture the intricate relationships within these activations. Their fidelity-only approach to evaluating global explanations also presents a new concern. For the first time, we address these limitations with the novel transformative nonlinear concept explainer (TraNCE) for CNNs. Unlike linear reconstruction assumptions made by existing methods, TraNCE captures the intricate relationships within the activations. This study presents three original contributions to the CNN explainability literature:

* An automatic concept discovery mechanism based on variational autoencoders (VAEs). This transformative concept discovery process enhances the identification of meaningful concepts from image activations; 

* A visualization module that leverages the Bessel function to create a smooth transition between prototypical image pixels, revealing not only what the CNN saw but also what the CNN avoided, thereby mitigating the challenges of concept duplication as documented in previous works; and 

* a new metric, the faith score, integrates both coherence and fidelity for comprehensive evaluation of explainer faithfulness and consistency. 

Based on the investigations on publicly available datasets, we prove that a valid decomposition of a high-dimensional image activation should follow a nonlinear reconstruction, contributing to the explainer’s efficiency. We also demonstrate quantitatively that, besides accuracy, consistency is crucial for the meaningfulness of concepts and human trust. The code is available at [https://github.com/daslimo/TrANCE](https://github.com/daslimo/TrANCE)
