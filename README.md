# mice_snMultiomic_analysis

Code for analyzing single-nucleus multiomic data from mouse models.

**Gene expression (GEX) analysis:**

The gene expression matrix was generated using CellRanger (ARC version 2.0.2, CellRanger version 7.2.0, aligned to the GRCm38 genome), and ambient RNAs were removed using CellBender.
1. Doublets removal: GEX_doublet_removal.ipynb
2. QC, normalization, clustering, and cell type annotation: GEX_allSample_QC_and_celltypeAnnotaiton.ipynb
3. Differentially gene expression (DEGs) analysis: GEX_cDC1_DEG_analysis.ipynb
4. Peak-to-gene analysis: ATAC_peaks_to_gene_analysis.ipynb

**ATAC analysis:**
1. Peak calling and QC (per sample): ATAC_perSample_peakCalling_and_QC.ipynb
2. Merging, normalization, clustering, and cell type annotation: ATACsubsetGex_and_clusterCellTypeAnnotation.ipynb
3. Differential accessibility and motif enrichment analysis: ATACsubsetGEX_DC1_DAR_and_MotifsEnrichment.ipynb
