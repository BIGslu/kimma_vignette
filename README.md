# kimma vignette

The identification of differentially expressed genes (DEGs) from transcriptomic datasets is a major avenue of research across diverse disciplines. Current bioinformatic tools support a number of experimental designs including covariates, random effects, and blocking. However, covariance matrices are not yet among the features available. Here, we introduce kimma for kinship in mixed model analysis, an open-source R package that provides linear and linear mixed effects modeling of RNA-seq data including all previous designs plus covariance random effects. kimma equals or outcompetes other DEG pipelines in terms of sensitivity, computational time, and model complexity. 

In particular, kimma provides:

* A single function `kmFit` for flexible linear modeling of fixed, random, and complex random effects
* Multi-processor architecture for reduced computational time
* Multiple model fit measures such as AIC and BIC
* Easy incorporation with data visualization and downstream analyses in the `BIGverse` (see below)

![](figures/intro_diagram-01.png)

## Vignettes

You can find html rendered vignettes for kimma as well as up and downstream analyses at the following links

* [SEAsnake](https://bigslu.github.io/SEAsnake/vignette/SEAsnake_vignette.html): An AWS snakemake pipeline for processing bulk RNAseq from fastq to gene counts
* [Counts to voom](https://bigslu.github.io/tutorials/RNAseq/2.Hawn_RNAseq_counts.to.voom.html): An R based pipeline in `edgeR` and `limma` to assess RNAseq library quality, filter, and normalize data
* [kimma](https://bigslu.github.io/kimma_vignette/kimma_vignette.html): Linear mixed effects modeling of RNAseq differential gene expression
* [SEARchways](): Gene set analyses of RNAseq data (under construction)
* [BIGpicture](): Data visualization related to RNAseq data analysis (under construction)


https://bigslu.github.io/kimma_vignette/
