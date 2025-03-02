# Gene Regulatory Network Analysis Pipeline
This repository contains R Markdown scripts for constructing and analyzing gene regulatory networks (GRNs) from RNA-seq data. The pipeline includes preprocessing, model reduction for differential gene expression, network inference, and filtering transcription factors (TFs) associated with trait subnetworks.

**Pipeline Overview**
1. RNA-seq Preprocessing (1_RNA-seq-preprocessing.Rmd): Normalizes RNA-seq data, performs quality control and filtering low-expressed genes.

2. Model Reduction (2_Model_Reduction.Rmd): Performs differential gene expression analysis using DESeq2.

3. Inferring GRNs (3_InferringGRNs.Rmd): Constructs gene regulatory networks using the inference methods ARACNE, CLR and GENIE3.

4. Building Merged Networks (4_BuildingMergedNetworks.Rmd): Merges inferred networks into a high-confidence consensus network

5. Gene-Trait Correlation (5_GeneTraitCorrelation.Rmd): Correlates gene expression with phenotypic traits and identifies trait-associated modules.

6. Filtering TFs in Trait Subnetworks (6_FilteringTFs-traitsubnetworks.Rmd): Identifies key TFs regulating trait-associated subnetworks
