Repository Overview

This repository provides the complete empirical infrastructure supporting the study “Disentangling the Valuation Effects of ESG Dimensions: Evidence from Meta-Analytic Structural Equation Modeling.”

The repository is designed to ensure methodological transparency, analytical traceability, and full computational replicability of the two-stage Meta-Analytic Structural Equation Modeling (MASEM) framework employed in the paper. It mirrors the sequential logic of the research design, beginning with systematic literature identification and effect-size extraction, proceeding to correlation matrix construction, and culminating in multivariate structural estimation and robustness validation.

Rather than serving as a supplementary archive, the repository constitutes the structured empirical backbone of the study’s differentiated ESG valuation analysis.

Repository Structure

The repository is organized into three interconnected components corresponding to the core stages of the empirical workflow.
1. Meta-Analytic Literature Database
This component contains the structured master dataset underlying the systematic review and quantitative synthesis. Each primary study is assigned a unique Research ID to ensure consistent linkage across coding records, extracted effect sizes, and subsequent diagnostics.
The database records bibliographic information, ESG dimensional operationalization, valuation proxies, and sample characteristics. Only peer-reviewed empirical studies reporting standalone environmental, social, and governance indicators in relation to firm-level market valuation were retained. Studies relying exclusively on composite ESG scores without dimensional decomposition were excluded to preserve the structural independence necessary for disentangling valuation effects across ESG components.
Following PRISMA-guided screening and eligibility assessment, 219 primary studies were included, contributing 1,445 independent effect sizes. These effect sizes form the quantitative basis for the meta-analytic integration and structural modeling procedures.

2. Main Meta-Analytic Structural Equation Modeling (MASEM) Analysis
This component contains the analytical infrastructure required to reproduce the two-stage structural estimation.
In Stage 1, effect sizes were transformed using Fisher’s Z and synthesized under a random-effects specification to construct the integrated meta-analytic correlation matrix. The pooled matrix incorporates associations among environmental, social, and governance dimensions, firm market valuation, and firm-level covariates. A harmonic mean sample size was applied to ensure statistical compatibility across heterogeneous primary samples.
In Stage 2, a structural equation model was estimated to isolate the independent net effects of each ESG dimension on corporate market valuation while explicitly modeling cross-dimensional interdependencies and controlling for firm size, firm age, and leverage. This multivariate framework enables the disentangling of dimension-specific valuation pathways that are obscured in bivariate analyses due to high covariance among ESG components.
All reported structural coefficients, model fit indices, and explained variance statistics can be replicated directly using the scripts and correlation matrices provided in this folder.

3. Robustness and Validation Procedures
This component documents the stability of the structural findings under alternative specifications and bias diagnostics.
The robustness materials include:
(1)Sensitivity analyses using the Sample-Adjusted Meta-Analytic Deviancy (SAMD) statistic to identify influential effect sizes and re-estimate the structural model following their removal
(2)Publication bias diagnostics, including Egger regression tests
(3)Rosenthal’s fail-safe N calculations
(4)Trim-and-Fill adjustments for potential small-study effects
Across all validation procedures, the core asymmetric valuation structure remains substantively stable: governance maintains the strongest positive association 
with firm market valuation, environmental performance exhibits a negative average association, and social performance does not display consistent independent pricing power once cross-dimensional correlations are modeled.
These results confirm that the differentiated valuation configuration is not driven by influential observations or publication-related distortions.

Replicability Statement
All datasets are organized at the study level and linked through unique Research IDs, enabling full reconstruction of the empirical workflow. Researchers can replicate:

Systematic literature screening and eligibility filtering

Effect-size extraction and Fisher’s Z transformation

Random-effects meta-analytic synthesis

Construction of the integrated correlation matrix

Two-stage structural equation modeling estimation

Outlier diagnostics and publication bias correction

By providing pooled correlation matrices, effective sample size specifications, and executable structural scripts, this repository ensures computational transparency and full reproducibility of the disentangled ESG valuation framework developed in the study.
