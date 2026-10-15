Repository Overview

This repository provides the data and analytical materials supporting the study, “Why capital markets recognize ESG dimensions unevenly: Global evidence from meta-analytic structural equation modeling.” It is designed to support methodological transparency, analytical traceability, and computational reproducibility of the reported two-stage Meta-Analytic Structural Equation Modeling (MASEM) analyses.

The repository follows the sequential logic of the research design. It begins with systematic literature identification and effect-size extraction, proceeds to the construction of the meta-analytic correlation matrix, and culminates in multivariate structural estimation and robustness assessment. The materials document the empirical basis and analytical procedures underlying the study's differentiated ESG–valuation findings.

Repository Structure

The repository is organized into three interrelated components corresponding to the main stages of the empirical workflow.

1. Meta-Analytic Literature Database

  This component contains the study-level database underlying the systematic review and quantitative synthesis. Each primary study is assigned a unique Research ID to facilitate linkage across coding records, extracted effect sizes, and subsequent diagnostic procedures. The database documents bibliographic information, ESG dimensional operationalization, valuation measures, and sample characteristics.

  The analysis focuses on English-language, peer-reviewed empirical studies in ABS-listed journals reporting separately identifiable environmental, social, or governance indicators in relation to firm-level market valuation. Studies relying exclusively on composite ESG scores without dimensional decomposition were excluded to preserve the interpretability of dimension-level associations.

  Following PRISMA-guided screening and eligibility assessment, 219 primary studies were included, contributing 1,486 eligible effect-size entries. Because individual studies could contribute evidence to multiple correlation cells, these entries should not be treated as statistically independent observations.

2. Main Meta-Analytic Structural Equation Modeling (MASEM) Analysis

  This component contains analytical materials supporting the two-stage MASEM estimation. In Stage 1, extracted correlations were transformed using Fisher's z and pooled under random-effects models to construct the meta-analytic correlation matrix. The matrix summarizes 21 bivariate associations among environmental, social, and governance dimensions, firm market valuation, firm size, firm age, and leverage.

  The harmonic mean of the 21 cell-specific cumulative sample sizes (60,958) served as the Stage 2 working sample size rather than a count of independent observations.

  In Stage 2, the pooled correlation matrix was used to estimate the conditional associations of ESG dimensions with firm market valuation while accounting for their intercorrelations and selected firm-level covariates. This multivariate approach enables comparison of dimension-specific valuation associations within a joint correlation structure. The resulting estimates represent pooled conditional relationships rather than firm-level causal effects or independently identified valuation-recognition mechanisms.

The archived matrices, model inputs, and outputs document the reported structural estimates, model fit statistics, and explained variance..

3. Robustness and Validation Procedures

This component documents the sensitivity of the reported findings to alternative analytical specifications, influential observations, and potential publication-related biases.

The robustness materials cover (1) outlier analyses using the Sample-Adjusted Meta-Analytic Deviancy (SAMD) statistic and subsequent model re-estimation; (2) Egger regression tests for funnel-plot asymmetry; (3) Rosenthal's fail-safe N calculations; and (4) Trim-and-Fill adjustments and the corresponding sensitivity analyses.

Across the reported specifications, governance retains a positive conditional association with market valuation, whereas environmental performance retains a negative association. The social coefficient is more sensitive to outlier treatment, becoming small and positive after influential observations are excluded. These diagnostics provide evidence on the sensitivity of the estimates but do not eliminate concerns about underlying heterogeneity or dimension-specific publication selection.

Replicability Statement：

The repository provides study-level documentation, pooled correlation matrices, and analytical files intended to facilitate independent examination and replication of the reported analyses.

Using the relevant archived materials, researchers can review the included-study information, inspect the meta-analytic correlation structure, reproduce the provided MASEM specifications, and examine the reported robustness and publication-bias diagnostics. Reproduction of individual stages depends on the availability of their corresponding data, inputs, and analytical scripts.

Together, these materials support transparency and traceability in evaluating the pooled conditional associations between ESG dimensions and corporate market valuation. They do not establish causal identification of the proposed valuation-recognition mechanisms.
