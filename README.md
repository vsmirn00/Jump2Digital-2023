# Jump2Digital-2023

## Data Preprocessing and PCA

This repository contains code and documentation for a data preprocessing and Principal Component Analysis (PCA) process applied to a dataset that combines rental data and noise data (lloguer and poblacio). The goal is to demonstrate how to transform and analyze the data effectively. This repository was created as an exercise to complete the task for the Jump2Digital 2023 hackathon.

## Overview

The process involves the following steps:

1. **Loading Data**: We begin by loading the rental and noise datasets into separate DataFrames. The data is sourced from CSV files.

2. **Joining Datasets**: We merge the rental and noise datasets based on a common key, resulting in a unified dataset that combines information from both sources.

3. **Data Preprocessing**: This step includes handling missing values. It ensures that the data is clean and ready for analysis.

4. **Exploratory Data Analysis (EDA)**: EDA is conducted to gain insights into the data. This involves data visualization, descriptive statistics, and identifying relationships between variables. No significant insights were obtained since the data was too uniformly distributed.

5. **Standardization**: To prepare the data for PCA, we normalize it using the Min-Max Scaler. This ensures that all features have a consistent scale with a range between 0 and 1.

6. **Principal Component Analysis (PCA)**: PCA is applied to reduce the dimensionality of the dataset and capture the most significant information.

## Results

The number of variables in the dataset decreased to a total of 100 from 200.
