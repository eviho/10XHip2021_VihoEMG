# Cell type specificity of glucocorticoid signaling in the adult mouse hippocampus

Viho EMG et al. 2021 - Journal of Neuroendocrinology

DOI: pending

## Project description

This repository contains the details of the algorithms the authors used for single-cell analysis, coupling heatmaps and gene regulatory analysis.

1. Pre-processing according to Seurat standard workflow (R v3.6.1)
2. Gene expression: pre-processing and visualization of the gene expression matrix (R v3.6.1)
3. Co-expression: generation of coupling heatmaps (R v3.6.1)
4. pySCENIC: scalable Python SCENIC workflow (Python v3.8.5)
5. Processing of pySCENIC output (R v3.6.1)

## Data availability

The hippocampus matrix and metadata table are available for download at: https://portal.brain-map.org/atlases-and-data/rnaseq/mouse-whole-cortex-and-hippocampus-10x

The processed and clustered Seurat object "10XHip2021_seurat.object.rds" used for gene expression/co-expression visualization is available for download at:

The hippocampus subset of metadata "10XHip2021_md.tsv" is available for download at: 

The loom object used as input for pySCENIC "10XHip2021.loom" is available for download at:

The pySCENIC output (GRN activity matrix) "10XHip2021_GRN.matrix.csv" is available for download at:
