# BRCA1 RNA Sequencing Analysis

This repository contains the code for the Foundations of Data Science final project using TCGA-BRCA RNA-sequencing counts and metadata.

## Required files

Create a `data` folder in the project directory and place the following files inside it:

- `data/counts.csv`
- `data/meta_data.csv`

The raw count matrix is not committed because its size exceeds GitHub's ordinary single-file limit. The files supplied through the course should be used without altering their contents.

## Reproduce the analysis

1. Open `WongFaith-FinalProject.Rmd` in RStudio.
2. Install any missing packages: `tidyverse`, `ComplexHeatmap`, `circlize`, `knitr`, `rmarkdown`, and `scales`.
3. Knit the R Markdown file to PDF. This creates the figures and tables in `results`.
4. Compile `WongFaith-FinalProject-LaTeX.tex` using a LaTeX editor such as Overleaf, TeXShop, or the RStudio Terminal.

## Outputs

- Knitted R Markdown PDF with code and outputs
- Compiled LaTeX report
- PDF figures and CSV summary tables in `results`

## Data source

The data were derived from The Cancer Genome Atlas Breast Invasive Carcinoma project. See the report references for source documentation.

