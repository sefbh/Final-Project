# Final Project: Addressing Bias in Healthcare Algorithms

This repository contains the R Markdown file, supporting resources, and the knitted PDF for the final project, "Addressing Bias in Healthcare Algorithms." This project explores the impact of algorithmic bias in healthcare predictive models, evaluates their methods, and proposes ethical and technical improvements.


## Repository Structure

STOR_390_Final.Rmd: The R Markdown file containing the full essay, analysis, and R code for the figures, tables, and simulations.

STOR_390_Final.pdf: The knitted PDF file generated from the R Markdown document. This is the final submission document.

README.md: This file, providing an overview of the project and repository structure.


## Project Overview

The project critically examines a predictive healthcare algorithm that exhibits racial bias against Black patients. It leverages the seminal work "Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations" by Obermeyer et al. to:

Analyze the methods used in the algorithm.

Conduct a novel data simulation and statistical evaluation using R.

Discuss normative considerations and ethical implications.

Propose technical and policy-based improvements to mitigate bias.


## Highlights

Novel Analysis Using R: Includes simulations and visualizations demonstrating statistical parity, equalized odds, and disparate impact.

Figures and Tables: All visual elements use a cohesive theme of shades of blue for clarity and professionalism.

Ethical Considerations: Examines the consequences of biased algorithms and emphasizes the need for fairness.

## How to Reproduce

To reproduce the results and figures:

Clone this repository:

1. git clone [repository-url]

2. Open the stor390_final_project.Rmd file in RStudio.

3. Install necessary R packages: install.packages(c("dplyr", "ggplot2", "knitr", "reshape2"))

4. Knit the R Markdown file to PDF: Click the Knit button in RStudio or use the following command: rmarkdown::render("stor390_final_project.Rmd") The output will be saved as stor390_final_project.pdf.


## Dependencies

The following R packages are required:

dplyr

ggplot2

knitr

reshape2

Ensure these packages are installed before knitting the R Markdown file.


## Ethical and Policy Implications

This project underscores the ethical and societal importance of addressing bias in healthcare algorithms. By integrating fairness constraints and emphasizing transparency, this work aims to advance equitable healthcare delivery through responsible AI innovation.

