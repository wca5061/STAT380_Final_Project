# STAT380_Final_Project


## Project Overview

This project aims to analyze and predict voting outcomes in video game map selections. By combining and cleaning datasets from two players, the project investigates which maps are most likely to win during map votes in Call of Duty. The analysis applies machine learning models to predict outcomes based on in-game features, providing insights into player preferences and map characteristics.

## Objectives

**Identify Winning Maps** – Determine which maps are most frequently chosen during votes.

**Predict Outcomes** – Build machine learning models to predict map vote results based on in-game data.

**Model Comparison** – Compare the performance of three models: Random Forest, k-Nearest Neighbors (kNN), and Naive Bayes.

## Key Findings

**Random Forest** – Outperformed other models in terms of accuracy, sensitivity, and specificity.

**Model Performance** – Random Forest achieved the highest kappa value, indicating strong agreement with ground truth data.

**Improvement Potential** – Although the Random Forest model performed best, the highest accuracy achieved was 67.7%, indicating room for further refinement.

## Technologies and Tools

R (tidyverse, dplyr, ggplot2)

**Machine Learning Models** – Random Forest, kNN, Naive Bayes

**Data Sources** – CSV files containing in-game data (player performance, map names, and voting outcomes).

## How to Run

Clone the repository and ensure R is installed.

Load required libraries (tidyverse, dplyr, ggplot2).

Execute the R script to preprocess data and build models.

View results through the HTML output or generated plots.
