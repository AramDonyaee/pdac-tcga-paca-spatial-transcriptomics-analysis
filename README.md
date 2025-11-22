This repository contains all analysis code and workflows for my study on resolving neural contamination in Pancreatic Ductal Adenocarcinoma (PDAC) transcriptomic data. Using TCGA, ICGC PACA-AU and spatial transcriptomics datasets, I developed and applied a multi-lineage in-silico purification pipeline to disentangle tumor-intrinsic gene expression from stromal, vascular, and neural components.

The Python scripts/jupyter notebooks in this repository implement:

Bulk deconvolution of TCGA-PAAD (n=178) to separate tumor, fibroblast, vascular, and Schwann-cell–derived signals.

Correlation and marker-origin analysis to evaluate claims of neural mimicry in PDAC.

Spatial transcriptomics processing (Visium / GSE274103) with spot-level scoring for nerves, tumor epithelium, fibroblasts, and vasculature.

Ion channel spatial mapping, identifying neural contaminants (e.g., SCN9A, CACNA1A) restricted to nerve tracts.

Discovery of CACNA1C as a vascular–stromal marker, not tumor-intrinsic, through spatial co-localization with ACTA2 and PECAM1.

Cross-cohort survival and subtype validation, including TCGA and ICGC PACA-AU comparisons.

Overall, this repository provides the computational framework supporting my finding that reported neural mimicry in PDAC largely reflects perineural invasion artifacts, and that loss of CACNA1C marks vascular integrity collapse in high-grade tumors.
