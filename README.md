Repository Overview
  This repository provides the complete empirical foundation and analytical materials for the study
  “Governance as the Valuation Anchor of ESG: Evidence of Green Capital Recalibration from a Meta-Analytic SEM.”
  It is designed to ensure transparency, traceability, and full replicability of the Meta-Analytic Structural Equation Modeling (MASEM) process.
  The repository is organized to reflect the sequential stages of the research workflow, from study identification and coding to structural estimation and robustness validation.

Folder Structure and Description
  1. Meta-Analysis Literature List
  This folder contains the study-level master database used for the systematic review and meta-analysis.
  Rather than a simple bibliography, this file constitutes the primary empirical inventory underlying all subsequent analyses.
  Each row corresponds to a unique primary study and is identified by a Research ID, which serves as the key linkage across coding sheets, effect-size extraction, and  robustness diagnostics.
  The database records essential descriptive information, including:
  Study identifier (Research ID), Author(s), Article title, Journal outlet, Year of publication.
  This structured design enables transparent study tracking, de-duplication, and auditability throughout the meta-analytic process.
  Only peer-reviewed studies reporting dimension-level ESG indicators and firm-level valuation or performance outcomes were retained, ensuring conceptual consistency and comparability across studies.
  Based on this literature screening and eligibility assessment, the final sample comprises 219 primary studies, which form the empirical basis for effect-size coding and synthesis.
  2. Main MASEM Analysis
  This folder contains the core analytical components required to estimate the Meta-Analytic Structural Equation Model.
  It includes:
  The integrated meta-analytic correlation matrix, Executable scripts (e.g., Mplus code) implementing the Two-Stage Structural Equation Modeling (TSSEM) procedure, Output files reporting standardized path coefficients, model fit indices, and explained variance.
  The structural model estimates the independent net effects of the environmental, social, and governance dimensions on firm market valuation, while controlling for firm size, firm age, and leverage.
  All results reported in Figure 2 and Tables 2–3 can be reproduced directly using the files in this folder.
  3. Robustness Checks
  This folder documents the robustness and validation procedures applied to the main findings.
  Specifically, it includes materials for:
  Sensitivity analysis, conducted using the Sample-Adjusted Meta-Analytic Deviancy (SAMD) statistic to identify influential effect sizes and re-estimate the model after their removal;
  Publication bias assessment, including Egger’s regression test and fail-safe N statistics.
  Across all robustness checks, the core conclusions remain stable: governance exhibits the strongest valuation effect, environmental performance is discounted, and social performance does not show an independent pricing effect once cross-dimensional dependencies are accounted for.

Replicability Statement
  All data files are organized at the study level and are linked consistently through unique identifiers, allowing researchers to replicate the full empirical workflow—from literature screening and effect-size synthesis to structural estimation and robustness testing—using the provided correlation matrices and scripts.
