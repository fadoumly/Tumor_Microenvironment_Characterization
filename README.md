# Characterization of TME in HCC Mouse Models

The file mMCPcounter.Rmd presents an R script designed for the analysis of transcriptomic data obtained from bulk RNA sequencing in the context of characterizing the tumor microenvironment (TME) of mouse models of hepatocellular carcinoma (HCC). This dataset allows for the exploration of tumor microenvironments across various models.

It is important to note that prior to establishing the TMEs, the data were downloaded via R using the GEOquery package. Data normalization was then performed to ensure the quality and comparability of the analyses. Initially, the characterization of the TME was conducted using the mMCPcounter tool available in R, employing the mMCPcounter_signatures_GCRm38 signature. Subsequently, the Fadoum_mMCP_counter tool, which utilizes the mMCPcounter_signatures_GCRm38 signature enriched with functional signatures extracted from the work of Job et al. 2020 (which required the conversion of human genes to mouse genes), was used for an in-depth characterization of the HCC TMEs across the seven mouse models present in this dataset.

Statistical analyses and visualizations are included. Hierarchical clustering was also performed to group the mouse models based on their similarities. Heatmaps illustrate these clusters as well as the average expression of associated genes. Additionally, chi-squared tests are conducted to evaluate the significance of the distributions of the models within the clusters.

Overall, this script provides a robust analytical framework for studying the characteristics of the TME in mouse models of HCC, allowing for the identification of complex interactions between different cellular populations and their potential impact on tumor progression.
