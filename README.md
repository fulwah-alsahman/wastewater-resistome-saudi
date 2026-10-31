# wastewater-resistome-saudi

This repository contains the R code used for sample A1 (notebooks 01 and 02) as a representative example of the analysis workflow, together with the code used to merge the CARD annotation tables of all samples and to compute the counts reported in the Results (notebooks 03 and 04). The code was run in R in Google Colab. The same workflow (same steps and parameters) was applied to the other samples (A2, B1, B2 and K), which were analysed in R either in Google Colab or in RStudio, with only the input file names changed, and gave outputs in the same format. The code is therefore provided once, for A1, and is not repeated for each sample.

## Files

- `01_assembly_stats_and_AMR_CAT_merge.ipynb`: assembly statistics and merging of AMRFinderPlus with CAT taxonomy
- `02_ARGs_comparison_heatmap.ipynb`: comparison of resistance genes across samples and heatmap
- `03_CARD_merge.ipynb`: merging of the CARD annotation tables
- `04_CARD_counts.ipynb`: counts used in Sections 3.7-3.9 of the report

## Note

The input files are not included in this repository. The raw sequencing data of sample A1 are publicly available under accession ERR4419502, and the input tables read by the code (seqtk_comp, AMRFinderPlus, CAT and CARD annotation tables) are intermediate outputs generated from these data with the tools and settings described in the Methodology. This repository therefore contains only the R code used for the downstream analysis.
