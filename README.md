# Baton Rouge Crime Data Analysis
## Overview

This project analyzes crime data from Baton Rouge, Louisiana, originally collected by the City of Baton Rouge and made publicly available through Data.gov
The goal is to explore patterns in attempted versus committed crimes, distribution across districts, and other notable crime trends.

## Objectives

Explore crime incident data for Baton Rouge.

Visualize the proportions of attempted vs. committed crimes.

Compare crime types and frequencies across districts.

Identify trends and patterns to better understand local crime distribution.

## Dataset

Source: City of Baton Rouge, Louisiana via Data.gov

Link: Baton Rouge Crime Incidents Dataset

Notes: No accompanying codebook provided. Dataset required minimal cleaning, with the main step being date reformatting for visualization.

## Methods

Tools Used: R, R Markdown

Libraries: tidyverse, ggplot2, dplyr, lubridate

Process:

Loaded and explored dataset.

Reformatted date columns for consistency.

Produced visualizations comparing attempted vs. committed crimes.

Analyzed proportions of crime types across districts.

## Results

Preliminary visualizations show that committed crimes significantly outnumber attempted ones, and crime types vary in frequency depending on the district. These insights can help contextualize local crime patterns.

## Files

Law - Final Deliverable.Rmd — Main R Markdown analysis file.

Baton_Rouge_Crime_Incidents.csv — Dataset (not included in repo due to size; available via Data.gov).

## Usage

To reproduce this analysis:

Download the Baton Rouge Crime Incidents dataset from Data.gov

Place the CSV file in your working directory.

Open Law - Final Deliverable.Rmd in RStudio.

Install required R packages if needed.

Knit the file to Word, HTML, or PDF to view the report.

## Author

Brooke Law
