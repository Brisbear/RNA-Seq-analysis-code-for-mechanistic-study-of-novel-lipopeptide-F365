# RNA-Seq analyses in manuscript "A new lipopeptide targeting top-priority multidrug-resistant Gram-negative pathogens"
A new lipopeptide targeting top-priority multidrug-resistant 1 Gram-negative pathogens

[![DOI](https://zenodo.org/badge/452678489.svg)](https://zenodo.org/badge/latestdoi/452678489)


**raw_data_processing/**<br />
**data_hk2/**<br />
**data_ab5075/**<br />
**scripts/**<br />
**HK2**<br />
rnaseqHK2.r: identify differentially expressed genes in HK2 upon treatments of polymyxins and analogs, produce PCA plot and Upset plots.<br />
generate.degs.cds.ann.r: generate dataframe of gene ensemble ID, entrenz ID, symbol, and name.<br />
plotCircosHK2.r: generate a Circos plot for all differentially expressed genes in HK2.<br />
plotComplexHeatmapHK2.r: produce complexheatmap of selected genes.<br />
extsignore.r: produce specfic signor gene regulatory network based on differentially expressed genes.<br />
plotUpsetHK2.r generate upset plot to show uniquely/commonly differentially expressed genes across all conditions.<br />
<br />
**AB5075**<br />
ab_rnaseq.r: identify differentially expressed genes in AB5075 upon treatments of polymyxins and analogs, produce PCA plot and Upset plots.<br />
plotComplexHeatmapAB5075.r: produce complexheatmap of selected genes.<br />
plotCircosAB5075.r: generate a Circos plot for all differentially expressed genes in AB5075.<br />
geneLogFCTableAB5075.r: generate a combined logFC table in concise format for all differentially expressed genes in AB5075.<br />

