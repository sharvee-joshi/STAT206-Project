# Replication and Extension: Instabilities of Regression Estimates Relating Air Pollution to Mortality

## Overview

This project replicates and extends the analyses presented in the article "Instabilities of Regression
Estimates Relating Air Pollution to Mortality". The original study investigates the sensitivity of
regression-based estimates when analyzing the relationship between air pollution and mortality,
focusing on the challenges of model specification and the stability of the results.

The goal of this project is to reproduce the findings from the paper while incorporating modern
techniques and fitting our own alternative model. Additionally, we aim to assess the robustness of
the methods used, and provide deeper insights into the factors
that contribute to the observed instabilities in regression estimates.

## Contents
The repository contains the following components:

1. **Data:**
   Details of the dataset used in the analysis, including preprocessing steps and any derived variables.
2. **Code:**
    Scripts for replicating the regression analyses and generating outputs (e.g., tables, graphs), written in R
3. **Report:**
   A comprehensive report detailing the methodology, results, and findings from the replication study.
4. **README:** This document, outlining the structure and purpose of the project.

## Packages 
Below is a list containing all packages used:
1. `bestglm` : used to input the data "mcdonald"
2. `ggplot2`: used for any and all ggplots used throughout the report
3. `reshape`: used to melt data in order to better visualize it
4. `corrplot`: used for correlation plots to check multi-collinearity
5. `knitr`: used for kable/ table creations
6. `car`: used for vif functions
7. `ggpubr`: used for arranging ggplots
8. `MASS`: self - explanatory
9. `glmnet`: used for glm function
10. `leaps`: used for C_p Mallows' Code

## Contributors
As seen in the main GitHub, this report was created by the following team members in no particular order:
1. Behzad FallahiFard
2. Makena Grigsby
3. Sharvee Joshi
4. Wonkeun Lee
