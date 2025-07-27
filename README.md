# LLMs for GWAS Causal Gene Prioritization

This repository contains the resources and data for the project (**Shringarpure_etal_2025_LLM_GWAS**) on using Large Language Models for prioritizing causal genes from Genome-Wide Association Studies (GWAS).

## Supplementary Files

This section provides an overview of the supplementary files, which contain the data, notes, and figures that support this study.

### ▶️ [Supplementary Tables (Supp_Tables.xlsx)](https://github.com/akds/llm-gwas-causal-genes/blob/main/Supp_Tables.xlsx)

This Excel file contains all the supplementary tables with detailed data and results referenced in the study.

**List of Tables:**
*   **Supplementary Table 1:** Datasets
*   **Supplementary Table 2:** Performance for all methods
*   **Supplementary Table 3:** Pairwise test LLM vs non-LLM
*   **Supplementary Table 4:** Performance of methods in gene-dense and gene-sparse regions
*   **Supplementary Table 5:** Performance of methods on deduplicated datasets
*   **Supplementary Table 6:** Calibration of LLM predicted confidence
*   **Supplementary Table 7:** Reproducibility of predictions and confidence
*   **Supplementary Table 8:** LLM reasons
*   **Supplementary Table 9:** Ablation study
*   **Supplementary Table 10:** LLM precision by phenotype
*   **Supplementary Table 11:** Causal gene deletion result
*   **Supplementary Table 12:** Input gene order shuffling result
*   **Supplementary Table 13:** Phenotypes included in evaluation dataset from 23andMe unpublished GWAS
*   **Supplementary Table 14:** Performance on novel vs known loci
*   **Supplementary Table 15:** Hallucinations
*   **Supplementary Table 16:** Pairwise concordance of methods
*   **Supplementary Table 17:** Ensemble of nearest gene + LLM
*   **Supplementary Table 18:** Ensemble of PoPS + LLM
*   **Supplementary Table 19:** Ensemble method predictions for all feature combinations
*   **Supplementary Table 20:** Contamination checks with GPT3.5 and GPT4
*   **Supplementary Table 21:** Performance on shuffled phenotypes


### ▶️ [Supplementary Notes and Figures (Supp_Notes_Figures.docx)](https://github.com/akds/llm-gwas-causal-genes/blob/main/Supp_Notes_Figures.docx)

This document contains detailed supplementary notes on the datasets and methodologies used, as well as all the supplementary figures.

**Notes Content:**
*   **Datasets:** Detailed descriptions of the OpenTargets and Pharmaprojects datasets.
*   **Data Processing:** Explanation of the processing steps for Pharmaprojects data and MeSH mappings.
*   **Methodology:** Details on the creation of synthetic GWAS hits for the Pharmaprojects dataset.
*   **Contamination Checks:** An overview of the `tabmemcheck` process used to evaluate dataset memorization in the LLMs.

**List of Figures:**
*   **Supplementary Figure 1:** Study design schematic.
*   **Supplementary Figure 2:** F-score performance of all LLM and non-LLM methods.
*   **Supplementary Figure 3:** Performance stratified by the number of genes in the locus.
*   **Supplementary Figure 4:** Performance on deduplicated datasets.
*   **Supplementary Figure 5:** Calibration plots for LLM-based approaches.
*   **Supplementary Figure 6:** Sensitivity analysis of prompt format on LLM performance.
*   **Supplementary Figure 7:** Performance of embedding-based causal gene identification.
*   **Supplementary Figure 8:** Cosine similarity for the LDL cholesterol phenotype and genes in the PCSK9 locus.
*   **Supplementary Figure 9:** Proportion of examples where the causal gene is in the top-K most similar genes.
*   **Supplementary Figure 10:** Performance of chain-of-thought prompting vs. standard prompting.
*   **Supplementary Figure 11:** Concordance between predictions from different methods.
*   **Supplementary Figure 12:** Performance of the best-performing LLMs across all datasets.
