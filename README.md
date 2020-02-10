# Frodyma, et. al. 2020
Data analysis for Frodyma paper

### Citation
```
Coming soon...
```

### RNA-seq analysis methods
RNA sequencing (RNA-seq) analysis was conducted by _ _ _ _ _ . For RNA sequencing, RNA was purified from _ _ _ _ _  by _ _ _ _ _ . Total RNA samples (_ _ _ _ _  ng) were hybridized with _ _ _ _ _  (_ _ _ _ _ ) to substantially deplete rRNA from the samples. _ _ _ _ _ Stranded/Unstranded_ _ _ _ _  RNA sequencing libraries were prepared as using the _ _ _ _ _  Kit. Purified libraries were quantified on _ _ _ _ _  using _ _ _ _ _ . Libraries were normalized to _ _ _ _ _  nM and equal volumes were pooled in preparation for sequence analysis. _ _ _ _ _ etc_ _ _ _ _  Raw sequence data has been deposited as GSE_ _ _ _ _ 

Sequence reads were preprocessed using XPRESSpipe (v0.4.1) [1], with adapter sequences set to AGATCGGAAGAGCACACGTCTGAACTCCAGTCA and AGATCGGAAGAGCGTCGTGTAGGGAAAGAGTGT. Reads were processed using H. sapiens GRCh38.p13 Ensembl release 99. Differential expression analysis was performed using the XPRESSpipe wrapper for DESeq2 (v1.22.1) [2]. Differentially expressed genes were further visualized using XPRESSplot [1]. Isoform abundance analysis was performed using the XPRESSpipe wrapper for Cufflinks (v2.1.1) [3] and IGV (v2.4.19) [4]. Scripts used to perform these analyses can be found at https://github.com/j-berg/froydma_2020.

### References
[1] Berg JA, Belyeu JR, Morgan JT, Ouyang Y, Bott AJ, Quinlan AR, Gertz J, Rutter J. XPRESSyourself: Enhancing, Standardizing, and Automating Ribosome Profiling Computational Analyses Yields Improved Insight into Data. PLoS Comp. Biol. 2020. https://doi.org/10.1371/journal.pcbi.1007625  

[2] Love M, Huber W, Anders S. Moderated estimation of fold change and dispersion for RNA-seq data with DESeq2. Genome Biol. 2014;15. https://doi.org/10.1186/s13059-014-0550-8.  

[3] Trapnell C, Roberts A, Goff L, Pertea G, Kim D, Kelley D, et al. Differential gene and transcript expression analysis of RNA-seq experiments with TopHat and Cufflinks. Nat Protoc. 2012;7. https://doi.org/10.1038/nprot.2012.016.

[4] Robinson J, Thorvaldsdóttir H, Winckler W, Guttman M, Lander E, Getz G, et al. Integrative Genomics Viewer. Nat Biotechnol. 2011;29:24–26. https://doi.org/10.1038/nbt.1754.
