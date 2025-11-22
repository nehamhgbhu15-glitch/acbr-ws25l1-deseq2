# Start R
To start R statistical Programming language type R in the command line of the R4.5WS conda environment
```{CMD}
R
```

# Install Packages for Bioconductor
Installing `BiocManager` from CRAN (Comprehensive R Archival Network) using `install.packages()` function in R base
```{R}
install.packages("BiocManager")
```

Install `Biostrings` Bioconductor package using `BiocManager::install()` function
```{R}
BiocManager::install("Biostrings")
```