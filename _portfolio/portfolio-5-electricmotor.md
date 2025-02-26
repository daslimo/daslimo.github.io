---
title: "Fault Diagnosis of Electal motor"
excerpt: "The project aimed at developiing fault disgnostic frameworks for electrical motors. Supervised by Prof. Hur Jang Wook and spearheaded by myself, the team designed test beds, conducted experiments and authored a journal articles. <br/><img src='/images/okw_exp.webp' style='width:200px'> "
collection: portfolio
---

<!-- ![solenoid pumps](/images/gear.png){: .align-right width = "200px}  -->
This project focused on developing a data-driven fault diagnostic framework for squirrel cage induction motors (SCIM), which are widely used in industry due to their affordability, durability, and minimal maintenance needs. Early fault detection in SCIMs, especially under low-load conditions, is critical to reducing maintenance costs and preventing unexpected equipment failures.<br/><img src='/images/okw_exp.webp'>

The research leveraged motor current signature analysis (MCSA) to extract spectral features from motor signals for fault detection and isolation (FDI). The proposed framework utilized intelligent classification models to diagnose faults (see figure below) based on these extracted features. <br/><img src='/images/okw_exp2.webp'>

Experimental results demonstrated that the extracted features accurately reflected various SCIM fault conditions. Among the tested models, the random forest (RF) classifier achieved the highest accuracy of 79.25%, though it had the highest computational cost of 3.66 seconds. Conversely, the Naive Bayes classifier (NBC) exhibited the lowest computational cost at 0.003 seconds. Additional empirical assessments validated the effectiveness of the proposed FDI technique, highlighting its potential for intelligent monitoring, reduced downtime, and improved operational efficiency in industrial settings.

**Grants**
* Grand Information Technology Research support (IITP-2020-2020-0-01612) provided by the MSIT (Ministry of Science and ICT) South Korea (2020 -2021)

**Journal Publication from the project**
* Okwuosa, C.N.; **Akpudo, U.E.**; Hur, J.-W. A Cost-Efficient MCSA-Based Fault Diagnostic Framework for SCIM at Low-Load Conditions. Algorithms 2022, 15, 212. https://doi.org/10.3390/a15060212

