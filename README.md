# Open source templates for mapping lead in water systems

We use the Washington, DC lead [data](https://www.dcwater.com/service-line-materials-dashboard) and [mapping template](https://geo.dcwater.com/Lead/) to build the examples in this repository. 

A live example of the mapping template can be viewed here: [watergrid.io/lead](https://watergrid.io/lead/).  

## Getting started

Clone this repo, and open the RProject, `lead.Rproj`. Open `template.Rmd` and knit the file. This generates the html map and dashboard for DC lead data.  

Ensure you have R >= 4.1.0 installed. 

Install packages required for this project:

```
pkgs <- c("flexdashboard", "leaflet", "tidyverse", "leafgl", "sf")
install.packages(pkgs)
```

For more detailed R and package installation support, see [this guide](https://www.r4wrds.com/intro/m_install_r). 


## More information

Key R packages used in this project:

- [flexdashboard](https://pkgs.rstudio.com/flexdashboard/index.html)  
- [leaflet](https://rstudio.github.io/leaflet/)  
- [leafgl](https://github.com/r-spatial/leafgl)  

```
> sessionInfo()
R version 4.1.0 (2021-05-18)
Platform: x86_64-apple-darwin17.0 (64-bit)
Running under: macOS Catalina 10.15.7

Matrix products: default
BLAS:   /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vecLib.framework/Versions/A/libBLAS.dylib
LAPACK: /Library/Frameworks/R.framework/Versions/4.1/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] leafgl_0.1.1        sf_1.0-4            forcats_0.5.1       stringr_1.4.0      
 [5] dplyr_1.0.7         purrr_0.3.4         readr_2.1.0         tidyr_1.1.4        
 [9] tibble_3.1.6        ggplot2_3.3.5       tidyverse_1.3.1     leaflet_2.0.4.1    
[13] flexdashboard_0.5.2

loaded via a namespace (and not attached):
 [1] Rcpp_1.0.7           lubridate_1.8.0      class_7.3-19         assertthat_0.2.1    
 [5] digest_0.6.28        utf8_1.2.2           R6_2.5.1             cellranger_1.1.0    
 [9] backports_1.3.0      leaflet.extras_1.0.0 reprex_2.0.1         e1071_1.7-9         
[13] evaluate_0.14        httr_1.4.2           pillar_1.6.4         rlang_0.4.12        
[17] readxl_1.3.1         rstudioapi_0.13      rmarkdown_2.11       htmlwidgets_1.5.4   
[21] munsell_0.5.0        proxy_0.4-26         broom_0.7.10         compiler_4.1.0      
[25] modelr_0.1.8         janitor_2.1.0        xfun_0.28            pkgconfig_2.0.3     
[29] htmltools_0.5.2      tidyselect_1.1.1     fansi_0.5.0          crayon_1.4.2        
[33] tzdb_0.2.0           dbplyr_2.1.1         withr_2.4.2          grid_4.1.0          
[37] jsonlite_1.7.2       gtable_0.3.0         lifecycle_1.0.1      DBI_1.1.1           
[41] magrittr_2.0.1       units_0.7-2          scales_1.1.1         KernSmooth_2.23-20  
[45] cli_3.1.0            stringi_1.7.5        fs_1.5.0             snakecase_0.11.0    
[49] xml2_1.3.2           ellipsis_0.3.2       generics_0.1.1       vctrs_0.3.8         
[53] tools_4.1.0          glue_1.5.0           hms_1.1.1            crosstalk_1.2.0     
[57] fastmap_1.1.0        colorspace_2.0-2     classInt_0.4-3       rvest_1.0.2         
[61] knitr_1.36           haven_2.4.3         
```