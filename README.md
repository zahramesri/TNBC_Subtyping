# TNBC_Subtyping


This repository accompanies the manuscript:

"Spatial context of cellular heterogeneity in triple-negative breast cancer reveals actionable subtypes"

and contains reproducible analysis pipeline for the study. Contains scripts for quality control, molecular subtyping, differential expression, pathway enrichment, and manuscript figure generation.

## Repository Structure

| Directory | Description |
|-----------|-------------|
| `01_BulkRNA` | Bulk RNA-seq preprocessing, molecular subtyping, and differential expression analysis |
| `02_GeoMx_QC` | GeoMx DSP quality control and normalization |
| `03_GeoMx_TME_deconvolution` | SpatialDecon and EcoTyper analyses |
| `04_GeoMx_DEA` | Differential expression and pathway enrichment analyses |
| `05_Shiny_App` | Interactive Shiny application for data visualization |
| `06_Manuscript_Figures` | Scripts used to generate all main and supplementary manuscript figures |

# Data
Raw Bulk expressions are available in GEO: GSE268851
Raw GeoMx data and post-QC data object are available in GEO: GSEXXXXXX
# Contact 
Zahra Mesrizadeh @zmesriza@ucsd.edu
