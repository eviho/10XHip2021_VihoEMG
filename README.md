# Cell type specificity of glucocorticoid signaling in the adult mouse hippocampus

Viho EMG et al. 2021 - Journal of Neuroendocrinology

DOI: pending

## Project description

This repository contains the details of the algorithms the authors used for single-cell analysis, coupling heatmaps and gene regulatory analysis.

- Pre-processing according to Seurat standard workflow (R v3.6.1)
- Gene expression: pre-processing and visualization of the gene expression matrix (R v3.6.1)
- Co-expression: generation of coupling heatmaps (R v3.6.1)
- pySCENIC: scalable Python SCENIC workflow (Python v3.8.5)
- Processing of pySCENIC output (R v3.6.1)

## Data availability

The hippocampus matrix and metadata table are available for download at: https://portal.brain-map.org/atlases-and-data/rnaseq/mouse-whole-cortex-and-hippocampus-10x

The processed and clustered final Seurat object used for gene expression/co-expression visualization is available for download at:

The loom object used as input for pySCENIC is available for download at:
