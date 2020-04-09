# The ribbon-helix-helix domain proteins CdrS and CdrL regulate cell division in archaea. 
**Authors: Cynthia L. Darnell[1], Jenny Zheng [2], Sean Wilson [2], Ryan M. Bertoli[1], Alexandre W. Bisson-Filho [3], Ethan Garner [2], Amy K. Schmid [1,4]**

[1] Biology Department, Duke University, Durham, North Carolina, United States
[2] Department of Molecular and Cellular Biology, Harvard University, Cambridge, Massachusetts, United States.
[3] Biology Department, Brandeis University, Waltham, Massachusetts, United States
[4] Center for Genomics and Computational Biology, Duke University, Durham, North Carolina, United States

## Requirements
- R v3.6.1

## Packages and dependencies
- attached base packages:
 [1] parallel  stats4    grid      stats     graphics  grDevices utils     datasets  methods  
[10] base     

- other attached packages:
 [1] moderndive_0.4.0         effsize_0.7.9            referenceIntervals_1.1.1
 [4] trackViewer_1.22.1       GenomicFeatures_1.38.2   AnnotationDbi_1.48.0    
 [7] Biobase_2.46.0           rtracklayer_1.46.0       GenomicRanges_1.38.0    
[10] GenomeInfoDb_1.22.0      IRanges_2.20.2           S4Vectors_0.24.3        
[13] BiocGenerics_0.32.0      gridExtra_2.3            DataCombine_0.2.21      
[16] maSigPro_1.58.0          lubridate_1.7.4          gplots_3.0.3            
[19] ggpubr_0.2.5             magrittr_1.5             ggExtra_0.9             
[22] rstatix_0.4.0            sjstats_0.17.9           bestNormalize_1.4.3     
[25] patchwork_1.0.0          EnvStats_2.3.1           viridis_0.5.1           
[28] viridisLite_0.3.0        corrplot_0.84            forcats_0.5.0           
[31] stringr_1.4.0            purrr_0.3.3              readr_1.3.1             
[34] tibble_2.1.3             tidyverse_1.3.0          dplyr_0.8.5             
[37] tidyr_1.0.2              ggplot2_3.3.0            psychometric_2.2        
[40] multilevel_2.6           MASS_7.3-51.5            nlme_3.1-145            
[43] plyr_1.8.6              

           
## Source data
All data needed to run the code in the "2020-03-19-cdr-analysis-all.Rmd" file are downloadable here _except_:
- "GE-dulmage.txt" 
     - file for gene expression analysis in Figure 1 is too large to host on github. Download the file from the Duke Digital Repository at  https://dx.doi.org/10.7924/r4pz54w7h. Click on "Expression" on the front page, then download the file "1154_normalized_GE_data.csv". Use "read.csv" command to load this file.
     - If you use gene expression data from that repository in a publication, please cite the source article: 
     - Copy number variation is associated with gene expression change in archaea. Keely A. Dulmage, Cynthia L. Darnell, Angie Vreugdenhil, and Amy K. Schmid1 Microb Genom. 2018 Sep; 4(9): e000210. doi: 10.1099/mgen.0.000210

- bam files for ChIP-seq visualization. 
     - These can be generated using the code in the ChIP-seq folder or 
     - Downloaded from the sequence read archive at GEO accession GSE148065.

