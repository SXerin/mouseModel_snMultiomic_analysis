# mice_snMultiomic_analysis

Code for analyzing single-nucleus multiomic data from mouse models.

**Gene expression (GEX) analysis:**
Gene expression matrix were generated using CellRanger (arc version 2.0.2, cellranger version 7.2.0, aligned to GRCm38 genome) and ambient RNAs were removed using CellBender.
1. Doublets removal: GEX_doublet_removal.ipynb
2. QC, normalize, cluster, and cell type annotation: GEX_allSample_QC_and_celltypeAnnotaiton.ipynb
3. Differentially gene expression (DEGs) analysis: GEX_cDC1_DEG_analysis.ipynb

**ATAC analysis:**
1. Peak calling and QC (per sample): ATAC_perSample_peakCalling_and_QC.ipynb
2. Merge, normalize, cluster and cell type annotation: ATACsubsetGex_and_clusterCellTypeAnnotation.ipynb
3. Differential accessibility and motif enrichment analysis: ATACsubsetGEX_DC1_DAR_and_MotifsEnrichment.ipynb
