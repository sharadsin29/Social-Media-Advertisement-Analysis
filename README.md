# Social Media Advertisement Analysis

## Description
This project is a statistical analysis of a social media advertising dataset for a company. The goal of the project is to understand the data collected by the company and provide recommendations for future advertising strategies. The project involves the use of descriptive and inferential statistics to answer various questions proposed by the company's CEO and CFO.

## Data
The dataset contains information about advertisements on different social media platforms. Each line corresponds to an ad and includes the following information:
- Social media platform that led to the sale
- Age of the customer
- Whether the customer used mobile or a computer
- Season of the year when the sale took place
- Whether or not the customer was new
- Cost of the ad
- Revenue generated by the ad

## Analysis
The project involves multiple stages of analysis using both descriptive and inferential statistics:

1. **Descriptive Analysis**: Computed relative frequencies and created corresponding bar plots to visualize the distribution of ads across different platforms. Calculated variance, standard deviation, coefficient of variation, and interquartile range for each social media platform.

2. **Hypothesis Testing**: Performed a goodness-of-fit test to verify if the marketing department is following the proposed ad strategy. This involved comparing observed proportions of ads on each platform with expected proportions. The null hypothesis assumed the observed proportions matched the expected, while the alternative hypothesis suggested at least one proportion did not match. 


## Requirements
- R
- RMarkdown
- Libraries: pacman, party, psych, rio, tidyverse, ggpubr, dplyr, magrittr, ggplot2

## Installation
To run the project, you need to have R and the above libraries installed. You can install the libraries using the `install.packages()` function in R. 

## Usage
To reproduce the analysis, you can run the RMarkdown file in an R environment. Make sure to have the dataset in the correct path.

## Limitations
The project is based on a dataset provided by the company, and the analysis is only as good as the data. The dataset might not include all factors that could influence the effectiveness of an advertisement.

## Project Status
This project was completed as a final project for the DSCC/CSC 462 course.



