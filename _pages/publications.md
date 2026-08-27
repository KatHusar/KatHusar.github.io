---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %} You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u> {% endif %}

## Publications and Preprints

-   **Husar, K.**, Pittman, D. C., Rajala, J., Mostafa, F., & Allen, L. J. (2024). Lyme Disease Models of Tick-Mouse Dynamics with Seasonal Variation in Births, Deaths, and Tick Feeding. *Bulletin of Mathematical Biology, 86*(3), 1-38, [Link](https://pubmed.ncbi.nlm.nih.gov/38294562/).

-   **Husar, K.**, Volfovsky, A. (2026). DARTS: Targeting Prognostic Covariates in Budget-Constrained Sequential Experiments. *Under review.* [arXiv:2605.06608](https://arxiv.org/abs/2605.06608).

-   **Husar, K.**, Pandey, M., Larsen, I. G., Pliego San Martin, J., Purohit, S., Hamelsky, J., Tang, B., Tackett, M., & Schramm-Sapyta, N. L. The Intersection of Cash Bail Reform, Serious Mental Illness, and Substance Use Disorders in a Southern County Jail. *Under review.*

-   **Husar, K.**, Volfovsky, A. Rerandomization with Missing Data (in preparation).

## Research Experience

-   **Research Science Intern**, Amazon, *Summer 2026–Present*\\
    **Team:** *Supply Chain Optimization Technologies (SCOT)*

    -   Analyzed the production impact of design-stage stratification within the SCOT A/B testing platform to evaluate variance reduction and inform baseline experimental strategies.
    -   Proposed a novel, easily implementable causal estimator that resolves zero-coverage degradation caused by subgroup unit depletion during concurrent experiments, while maintaining the production baseline under no depletion.
    -   Built and launched an internal user-interface application that tracks treatment and control arm convergence after experiment rollouts and rollbacks, surfacing resource conflicts and identifying when units can re-enter the sampling pool; now being integrated into the primary experimentation platform.

-   **Research Assistant**, Duke University, *October 2025–Present*\\
    **Topic:** *DARTS: Targeting prognostic covariates in budget-constrained sequential experiments*\\
    **Advisor:** Alexander Volfovsky

    -   Developed a sequential experimental design method for trials where pre-treatment data must be collected under a fixed budget, learning across batches which covariates best predict the outcome and spending the budget on those.
    -   Established that adapting data collection to earlier batches preserves randomization validity, so estimates and confidence intervals retain their guarantees, and that the budget is allocated near-optimally.
    -   Across 11 simulation settings, reduced MSE by up to 72% (median 34%) over standard randomized designs, outperforming competing adaptive methods and closing much of the gap to the oracle design.

-   **Bass Connections Project**, Duke University, *Fall 2025–Spring 2026*\\
    **Topic:** *Cash bail reform, serious mental illness, and substance use disorders in a county jail*\\
    **Faculty leads:** Nicole L. Schramm-Sapyta, Maria Tackett

    -   First author on a study of a county cash bail policy change, linking jail detention records to health system data and applying interrupted time series and matched difference-in-differences analyses.
    -   Showed that the reform largely formalized an existing trend toward release on recognizance, and that defendants with co-occurring mental illness and substance use disorders saw significantly higher rebooking rates after release.

-   **Research Assistant**, Duke University, *Spring 2024–Present*\\
    **Topic:** *Rerandomization with missing data*\\
    **Advisor:** Alexander Volfovsky

    -   Established theoretical guarantees showing that enhanced randomization strategies (rerandomization) improve the efficiency of treatment-effect estimation even when participant data are partially missing.
    -   Ran large-scale simulation studies in R using cluster computing, covering 62+ experimental setups to assess real-world performance and achieved up to a 60% reduction in MSE compared to standard RCT designs.

-   **MARS Project**, Duke University, *Spring 2024*\\
    **Topic:** *Causal effect of migraine medication on retinal stroke risk*\\
    **Investigators:** Jay B. Lusk, Brian Mac Grory, Fan Li, Lauren Wilson, Natalie Smith, Alonso M. Guerrero Castañeda, **Kat Husar**

    -   Collaborated with a 7-member multidisciplinary team (including clinicians) on a study evaluating the effect of abortive migraine medication exposure on retinal stroke risk.
    -   Used the Snowflake platform to clean, structure, and run complex SQL queries on 1M+ insurance and clinical records to create analysis-ready datasets.

-   **REU Program**, Texas Tech University, *Summer 2021*\\
    **Topic:** *Lyme Disease Models of Tick-Mouse Dynamics with Seasonal Variation in Births, Deaths, and Tick Feeding*\\
    **Advisor:** Linda J. Allen

-   **Knots and Graphs Program**, The Ohio State University, *Summer 2019*, *Summer 2020*\\
    **Topic:** *Signed posets and a B-symmetric generalization of Stanley’s acyclicity theorem*\\
    **Advisor:** Sergei Chmutov

## Conference Talks and Posters

-   **ISBA World Meeting**, Poster, *Summer 2026*\\
    *DARTS: Targeting Prognostic Covariates in Budget-Constrained Sequential Experiments.*

-   **Electronic Conference on Teaching Statistics (eCOTS)**, Breakout Talk, *Summer 2026*\\
    *Breaking the Syntax Barrier: Empowering Students to Code in Any Language.*\\
    with Marie Neubrander

-   **American Causal Inference Conference**, Poster, *Spring 2026*\\
    *DARTS: Targeting Prognostic Covariates in Budget-Constrained Sequential Experiments.*

-   **American Causal Inference Conference**, Poster, *Spring 2025*\\
    *Rerandomization with Missing Data in Pre-Treatment Covariates.*
    
-   **Duke StatSci Research Alumni Symposium**, Poster, *Fall 2024*\\
    *Rerandomization and Regression Adjustment in Studies with Missing Values in Pre-Treatment Covariates.*

-   **Society for Mathematical Biology**, Talk, *Summer 2023*\\
    *Lyme Disease Models of Tick-Mouse Dynamics with Seasonal Variation in Births, Deaths, and Tick Feeding.*

-   **Young Mathematicians Conference**, Talk, *Summer 2021*\\
    *Lyme Disease Models of Tick-Mouse Dynamics with Seasonal Variation in Births, Deaths, and Tick Feeding.*

-   **Young Mathematicians Conference**, Talk, *Summer 2020*\\
    *Signed posets and a B-symmetric generalization of Stanley's acyclicity theorem.*
