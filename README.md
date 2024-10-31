# Transcriptional circuitry underlying neuropathology-associated microglia phenotypes 
## Molecular signatures and spatial organisation of AD-pathology-associated microglia under different conditions
![Spatial Logo](images/logo_1-01.png)
## Description:
## In this repository, we show how to analyze MERFISH (MERSCOPE/VIZGEN) datasets on  the brain samples of AD-pathology mouse models. Additionally, we provide our data processing pipelines to reproduce the figures for our submitted 2024 manuscript.

## Abstract
Plants lack specialized and mobile immune cells, requiring any cells–regardless of cell type–that encounter pathogens to mount immune responses and communicate with surrounding cells for successful defense. However, the diversity, spatial organization, and function of cellular immune states in pathogen-infected plants are scarcely understood. Here, we comprehensively identify cell states in Arabidopsis thaliana leaves infected by immune-triggering and -suppressive bacterial pathogens by integrating time-resolved single-cell transcriptomics, epigenomics, and spatial transcriptomics. We reveal cell state-specific gene regulatory logic involving transcription factors (TFs), putative cis-regulatory elements, and target genes associated with disease and immunity. We identify a rare cell population that emerges at the nexus of immune-active hotspots designated as the Primary IMmunE Responder (PRIMER) cells. PRIMER cells show non-canonical immune signatures, exemplified by the expression of a previously uncharacterized TF, GT-3a, and high accessibility of this TF in the genome. We demonstrate that GT-3a negatively regulates plant immune responses against bacterial pathogens. PRIMER cells are surrounded by cells that activate genes for long-distance cell-to-cell immune signaling, suggesting potential interactions between these cell states for propagating immune responses across the leaf. Our molecularly defined spatiotemporal atlas serves as a discovery platform for immune cell states with functional and regulatory insights.

## Spatial Data Download

The data needed to reproduce our results is available for download [here](http://neomorph.salk.edu/download/Nobori_etal_merfish).

## Processing
We have a spatial processing pipeline with several ordered Jupyter notebooks to create the processed objects needed for figure creation.

Processing of .
   [MERSCOPE processing](/processing_pipelines/MERFISH_processing)

## Figures

This section contains the scripts to reproduce the figures in the paper.

### MERFISH Figure Script Links

| Figure | Link                                                  |
|--------|-------------------------------------------------------|
| smFISH EDS16     | [Notebook](/processing_pipelines/smFISH_processing/01_quantify_sid_expression.ipynb)         |
| bacterial analysis     | [Notebook](/figures/bacteria/bacteria.ipynb) |
| Quality control metrics     | [Notebook](/figures/qc_metrics/qc_metrics.ipynb)     |
| Joint embedding and spatial plotting  | [Notebook](/figures/joint_embedding_and_spatial_clusters/joint_embedding_and_spatial_clusters.ipynb)    |
| Celltype assignments accuracy  | [Notebook](/figures/celltype_assignment_accuracy/celltype_assignments.ipynb)     |
| snMultiome pseudotime and clusters   | [Notebook](/figures/seq_clusters_and_pseudotime_figures/seq_clusters_and_pseudotime_figures.ipynb)    |
| spatial pseudotime and clusters   | [Notebook](/figures/spatial_clusters_and_pseudotime/spatial_clusters_and_pseudotime.ipynb)    |
| RNA/ATAC/Chromvar imputation      | [Notebooks](/figures/imputation)   |
| Spatial Differential Expression   | [Notebooks](/figures/spatial_differential_expression/HowWeFoundBON3.ipynb)     |


## Contact

- Tatsuya Nobori: :envelope: Tatsuya.Nobori@tsl.ac.uk
