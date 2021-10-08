# INFO 550
## My project

For my project, I will analyze the `ALL COVID vs MIS-C` data. 

This project used WGCNA method to detect the differentially expressed genes between COVID and MIS-C patients. To analyze the data you will need to install some `R` packages. The required packages can be installed using `R` commands.
``` r
install.packages("BiocManager")
BiocManager::install("WGCNA")
```

## Execute the analysis

To execute the analysis, from the project folder you can run 

``` bash
Rscript -e "rmarkdown::render('INFO_550.Rmd')"
```

This will create a file called `INFO_550.html` output in your directory that contains the results.

