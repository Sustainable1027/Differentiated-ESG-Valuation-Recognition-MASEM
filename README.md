Repository Overview

This repository provides the complete empirical infrastructure for the study, “Disentangling the Differentiated Valuation Relevance of ESG Dimensions: Global Evidence from Meta-Analytic Structural Equation Modeling.” It is designed to ensure methodological transparency, analytical traceability, and full computational replicability of the two-stage Meta-Analytic Structural Equation Modeling (MASEM) framework implemented in the paper.

The repository follows the sequential logic of the research design. It begins with systematic literature identification and effect-size extraction, proceeds to the construction of the meta-analytic correlation matrix, and culminates in multivariate structural estimation and robustness validation. Rather than functioning as a supplementary archive, the repository serves as the structured empirical backbone of the study.

Rather than serving as a supplementary archive, the repository constitutes the structured empirical backbone of the study’s differentiated ESG valuation analysis.

Repository Structure

The repository is organized into three interrelated components corresponding to the main stages of the empirical workflow.

1. Meta-Analytic Literature Database

  This component contains the master dataset underlying the systematic review and quantitative synthesis. Each primary study is assigned a unique Research ID to ensure consistent linkage across coding records, extracted effect sizes, and subsequent diagnostic procedures.
  The database documents bibliographic information, ESG dimensional operationalization, valuation measures, and sample characteristics. Only peer-reviewed empirical studies reporting standalone environmental, social, and governance indicators in relation to firm-level market valuation were retained. Studies relying exclusively on composite ESG scores without dimensional decomposition were excluded in order to preserve the structural independence required to identify differentiated valuation effects across ESG dimensions.
  Following PRISMA-guided screening and eligibility assessment, 219 primary studies were included, contributing 1,445 independent effect sizes. These effect sizes constitute the empirical basis for the subsequent meta-analytic synthesis and structural modeling.

2. Main Meta-Analytic Structural Equation Modeling (MASEM) Analysis

  This component contains the analytical files necessary to reproduce the two-stage structural estimation.
In Stage 1, effect sizes were transformed using Fisher’s z and synthesized under a random-effects specification to construct the integrated meta-analytic correlation matrix. The pooled matrix captures the associations among the environmental, social, and governance dimensions, firm market valuation, and firm-level covariates. A harmonic mean sample size was used to ensure statistical compatibility across heterogeneous primary samples.
  In Stage 2, a structural equation model was estimated to identify the independent net effects of each ESG dimension on firm market valuation while explicitly accounting for cross-dimensional interdependence and controlling for firm size, firm age, and leverage. This multivariate design allows the study to disentangle dimension-specific valuation pathways that are obscured in conventional bivariate analyses due to the high covariance among ESG components.
  All reported structural coefficients, model fit indices, and explained variance statistics can be reproduced directly using the scripts and correlation matrices provided in this section.

3. Robustness and Validation Procedures

This component documents the stability of the structural findings under alternative specifications and bias diagnostics.
The robustness materials include:
(1)Sensitivity analyses using the Sample-Adjusted Meta-Analytic Deviancy (SAMD) statistic to identify influential effect sizes and re-estimate the structural model following their removal. 
(2)Publication bias diagnostics, including Egger regression tests. 
(3)Rosenthal’s fail-safe N calculations. 
(4)Trim-and-Fill adjustments for potential small-study effects. 
Across all validation procedures, the core asymmetric valuation structure remains substantively stable: governance maintains the strongest positive association 
with firm market valuation, environmental performance exhibits a negative average association, and social performance does not display consistent independent pricing power once cross-dimensional correlations are modeled.
These results confirm that the differentiated valuation configuration is not driven by influential observations or publication-related distortions.

 4.Replicability Statement

All datasets are organized at the study level and linked through unique Research IDs, enabling full reconstruction of the empirical workflow. Using the materials provided in this repository, researchers can replicate:

the PRISMA-based literature screening and final study selection process;
the coding and organization of the study-level meta-analytic database;
the extraction and transformation of effect sizes into Fisher’s z metrics;
the construction of the pooled random-effects meta-analytic correlation matrix;
the two-stage MASEM estimation of the differentiated net effects of environmental, social, and governance dimensions on firm market valuation; and
the full set of robustness checks, sensitivity analyses, and publication-bias diagnostics reported in the study.

Taken together, these materials provide a transparent and reproducible empirical foundation for evaluating the differentiated valuation relevance of ESG dimensions in global capital markets.

By providing pooled correlation matrices, effective sample size specifications, and executable structural scripts, this repository ensures computational transparency and full reproducibility of the disentangled ESG valuation framework developed in the study.
