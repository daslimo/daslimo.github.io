---
title: "CoPISan: Contrastive Perceptual Inference and Sanity Checks for Concept-Based CNN Explanations"
collection: publications
category: manuscripts
permalink: /publication/2025-09-05-CoPISan
excerpt: 'This paper addresses limitations in concept-based explainability with principles of cognition. CoPISan is a plug-in module designed to work seamlessly with unsupervised concept-based CNN explanation methods'
date: 2025-09-05
paperurl: 'https://ieeexplore.ieee.org/document/11024161'
codeurl: 'https://github.com/daslimo/CoPISan'
citation: 'U. E. Akpudo, Y. Gao, J. Zhou and A. Lewis, "CoPISan: Contrastive Perceptual Inference and Sanity Checks for Concept-Based CNN Explanations," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 47, no. 9, pp. 8193-8212, Sept. 2025, doi: 10.1109/TPAMI.2025.3576755.'
---

Despite the effectiveness of convolutional neural networks (CNNs) in visual cate-gorization, the logic behind their predictions is not human-understandable. While existing concept-based explainability methods reveal what a CNN sees, there is a need to understand how a specific concept is chosen (rather than another concept) for a prediction, aligning more closely with human perception. To address this challenge, we propose a novel contrastive paradigm to bridge the critical gap in global concept discovery by leveraging contrasts from cognitive sciences for discriminative concept retrieval. A new multiple-case concept retrieval method is proposed for improved local understanding of (dis)similar classification cases. We argue that a contrastive paradigm for concept retrieval and sanity checks is essential to an explainer’s trust-worthiness and integrate these missing ingredients into state-of-the-art concept-based explanation frameworks to foster a better human understanding through contrast. The proposed Contrastive Perceptual Inference and Sanity Checks for Concept-based CNN Explanations (CoPISan) framework accelerates salient concept retrieval. It evaluates explainer trustworthiness via sanity checks conducted under Frontdoor and Poisoning adversarial attacks. Experimental results demonstrate CoPISan’s encouraging 
performance, mitigating issues related to duplication, entan-glement, diminishing returns, and ambiguity of concept explanations. CoPISan is motivated by cognition and perception, offers theoretical justification and resilience, and is computationally efficient. This study presents three original contributions to the CNN explainability literature:

* We introduce the Contrastive Perceptual Inference and Sanity Checks (CoPISan) for enhanced concept-based CNN explanations, pioneering a breakthrough in contrastive concept retrieval for multi-class local explanation cases. CoPISan is a plug-in module designed to work seamlessly with unsupervised concept-based
CNN explanation methods;

* We introduce a quantitative approach for evaluating the degree of sanity of an explainer based on its resilience to adversarial attacks. The results show that our approach can broaden the area of concept-based explainability by enhancing the quality of, and trust in, the concept explanations produced. These discoveries
underscore the significance of scrutinizing intuitions during the development and adoption of concept-based explainers.; and 

* We demonstrate CoPISan’s effectiveness in case studies, addressing issues related to concept duplication, diminishing returns, and ambiguity. The resulting
explanations better align with human perception, categorizing prototypes into contrasting and noncontrasting concepts. CoPISan addresses the diminishing return problem by retrieving the optimal number of concepts for each local explanation task, offering significant computational advantages and providing fewer but more human-understandable concepts without compromising performance.
