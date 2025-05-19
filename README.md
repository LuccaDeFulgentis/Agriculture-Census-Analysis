# The Impact of an Aging Farmer Population on Agriculture

Team Project: Lucca DeFulgentis, Moses Chen, Shawn Balgobind  
Date: October 6, 2024

## Overview
This project investigates how the increasing average age of U.S. farmers impacts agricultural productivity, sales, and long-term sustainability. Through data analysis using the large USDA Census of Agriculture datasets, we explore trends in farmer age, county-level production, and farm profitability.

The repository includes:
1. TheImpactofanAgingFarmerPopulationonAgriculture.pdf: A PDF report summarizing key findings, figures, and methodology
2. census_data_processing.ipynb A Jupyter Notebook containing data cleaning, processing, and visualizations used in the analysis

## Focus
1. Trend Analysis: Tracking the rise in average farmer age from 1997 to 2022
2. Sales vs. Age: Investigating whether younger farmers run more profitable operations
3. Correlation Study: Measuring the relationship between average age and acres harvested
4. Geospatial Analysis: Creating heatmaps and scatter plots to visualize age distributions across counties

## Tools & Methods
Python Libraries: pandas, plotly, matplotlib, numpy

Data Sources:
1. USDA National Agricultural Statistics Service (NASS)
2. Census of Agriculture (1997–2022)

Key Techniques:
1. Handling missing/disclosed data
2. Interpolation for undisclosed values
3. Outlier detection using IQR
4. Pearson correlation coefficient calculation

## Notes
1. The Jupyter Notebook was originally created and executed in Google Colab. All plots and visualizations successfully rendered in that environment. (Some do not render on the github publish)
