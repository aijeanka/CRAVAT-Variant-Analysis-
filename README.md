# CRAVAT Variant Analysis

## Project Overview
This repository contains the documentation and results of the CRAVAT variant analysis performed as part of Homework 11 in HIDS-7003. The analysis focused on exploring genomic variants using two VCF files through the CRAVAT platform.

## Data Description
Two VCF files were analyzed:
1. **Single-sample VCF file from WES processing:** `ERR2348724.sorted.indexed.flagged.vcf`
2. **Multi-sample VCF file from a Thymus Cancer project:** `20180912-ThymusSomatic_tumorOnly_wo019_nonres.vcf`

## Analysis Workflow
- VCF files were downloaded from the CRAVAT homework folder and uploaded to CRAVAT for analysis.
- Each file was processed separately, with settings adjusted to default and reference genome set to hg19.
- Post-analysis, results were explored online using the CRAVAT interface, and relevant outputs were downloaded.

## Repository Contents
### Execution Summary
- `Aizhan_Uteubayeva-CRAVAT-HW-summary.docx`: This document includes a detailed summary of the execution of the pipeline, including screenshots and links to CRAVAT output.

### Output Files from Single-sample VCF Analysis (ERR2348724)
- `Gene_Level_Analysis.Result.tsv`: Summary of gene-level variant impacts from the CRAVAT analysis.
- `Input_Errors.Result.tsv`: Details of any input errors detected by CRAVAT during the analysis.
- `Variant_Additional_Details.Result.tsv`: Provides additional details on variants analyzed in the study.
- `Variant_Non-coding.Result.tsv`: Analysis results specifically for non-coding regions.
- `Variant.Result.tsv`: Main results file listing variants and their annotations.

### Output Files from Multi-sample VCF Analysis (20180912-ThymusSomatic)
- Similar files as listed for the single-sample analysis, detailing the CRAVAT results for the multi-sample analysis. Each file serves the same purpose, providing comprehensive insights into genomic variants for multiple samples from patients who responded to immuno-therapy.

## How to Use This Repository
- Review the `Aizhan_Uteubayeva-CRAVAT-HW-summary.docx` for a comprehensive understanding of the pipeline execution and output analysis.
- Detailed results and variant analyses can be further explored by accessing the output files listed above.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
- Aizhan Uteubayeva
