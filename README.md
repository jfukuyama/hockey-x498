# README for Analysis of NHL Birth Month Data

Contents of this directory:
- README.md, this file
- data/
  - canada_births_1991_2022.csv, nhl_player_births.csv; the data used in final-analysis.rmd
- source/
  - final_analysis.rmd, the analysis script used to generate results

To reproduce our analysis, compile the Rmd final-analysis.rmd from the source directory.

You will need to have the ggplot2 and tidyverse package installed.


# sessionInfo for the R session that ran the original analysis:


R version 4.5.1 (2025-06-13)
Platform: aarch64-apple-darwin20
Running under: macOS Sequoia 15.0

Matrix products: default
BLAS:   /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vecLib.framework/Versions/A/libBLAS.dylib 
LAPACK: /Library/Frameworks/R.framework/Versions/4.5-arm64/Resources/lib/libRlapack.dylib;  LAPACK version 3.12.1

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

time zone: America/Indiana/Indianapolis
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] tidyverse_2.0.0.  ggplot2_4.0.0   

loaded via a namespace (and not attached):
 [1] utf8_1.2.6         generics_0.1.4     shape_1.4.6.1      stringi_1.8.7      lattice_0.22-7     hms_1.1.3         
 [7] digest_0.6.37      magrittr_2.0.4     timechange_0.3.0   evaluate_1.0.5     grid_4.5.1         RColorBrewer_1.1-3
[13] iterators_1.0.14   fastmap_1.2.0      cellranger_1.1.0   foreach_1.5.2      survival_3.8-3     mgcv_1.9-3        
[19] viridisLite_0.4.2  scales_1.4.0       codetools_0.2-20   cli_3.6.5          rlang_1.1.6        crayon_1.5.3      
[25] splines_4.5.1      withr_3.0.2        yaml_2.3.10        tools_4.5.1        tzdb_0.5.0         vctrs_0.6.5       
[31] R6_2.6.1           lifecycle_1.0.4    pkgconfig_2.0.3    pillar_1.11.0      gtable_0.3.6       glue_1.8.0        
[37] Rcpp_1.1.0         xfun_0.53          tidyselect_1.2.1   rstudioapi_0.17.1  knitr_1.50         farver_2.1.2      
[43] nlme_3.1-168       htmltools_0.5.8.1  rmarkdown_2.29     labeling_0.4.3     compiler_4.5.1     S7_0.2.0
