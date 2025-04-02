# Batch Effect Correction in Gene Expression Data

This R Markdown project demonstrates an end-to-end pipeline for identifying and correcting batch effects in gene expression data using the `ComBat` algorithm from the `sva` package.

## 📊 Summary
- Dataset: `bladderEset` from the `bladderbatch` package
- Visualization: PCA (2D/3D) pre- and post-batch correction
- Methods: ComBat with and without covariates (cancer status)
- Visualization: `ggplot2`, `plotly`, and heatmaps
- Outcome: Effective removal of technical batch noise while preserving biological signal

## 🔧 Tools
- R
- R Markdown
- ggplot2 / plotly / sva

## 📁 Files
- `Batch Effect Correction in Gene Expression Data.Rmd`: Main analysis script
- `Batch Effect Correction in Gene Expression Data.html`: Rendered HTML report (optional)

## 📸 Preview
![PCA Before Correction](https://github.com/Penod/gene-expression-batch-correction/blob/main/PCA%20Before%20Batch%20Correction%20-%20Colored%20by%20Cancer.png)
![PCA After Correction](https://github.com/Penod/gene-expression-batch-correction/blob/main/pca_after_colored_by_color.png)

