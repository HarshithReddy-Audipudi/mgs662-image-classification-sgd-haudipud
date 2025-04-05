# MGS 662 – Project 1 Part B: Image Classification Using SGD in R

This repository contains the implementation of **Part B** of the MGS 662 course project. The objective was to classify narrative scroll paintings using grayscale image features and machine learning optimization techniques implemented in **R**.

## 🔧 Requirements

- **R** version ≥ 4.2
- Packages:
  - `dplyr`
  - `EBImage`
  - `ggplot2`
  - `readr`

### To install:

```r
install.packages(c("dplyr", "ggplot2", "readr"))
if (!requireNamespace("BiocManager", quietly = TRUE)) install.packages("BiocManager")
BiocManager::install("EBImage")


