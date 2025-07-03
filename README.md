This repository provides the data and annotated R scripts necessary to replicate analyses similar to those presented in the paper:

“Length at first maturity of 43 freshwater fish species caught by professional fishers in the Itaipu Reservoir, Paraná River Basin, Brazil”

The repository includes:

📂 Excel spreadsheets with raw data for a fish species (_Geophagus sveni_) used as example;

📄 Detailed R Markdown (.Rmd) and HTML (.html) files that guides users through the process of:

  -Fitting models for estimating length at first maturity using functions from sizeMat package
 
 Each file contains methods for:

  -Adjusting models for a fish species

  -Fitting models individually for males and females and indicating if estimated L50 were different considering sexes

  -Exporting results as .xlsx and .png files

⚠️ Note: The scripts are set to save results to the user’s Desktop on Windows. If you are using macOS or Linux, you’ll need to adjust the desktop_path accordingly.

The purpose of this repository is to promote reproducibility and offer a learning resource for fisheries biologists and quantitative ecologists working with fish populations.

We recommend downloading the .Rmd and .html files for optimal visualization.
