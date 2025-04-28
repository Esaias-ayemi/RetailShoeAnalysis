# RetailShoeAnalysis
AL Bundy's Shoe Shop Sales Analysis

## Overview
This analysis examines historical sales data from AL Bundy's Shoe Shop to estimate the number of shoes likely to be sold based on past trends. The dataset spans three years and is considered a sample, not a population. The analysis aims to determine the 95% confidence interval for future sales, focusing on a specific segment.

## Data Understanding & Segmentation
The dataset is gotten from 365 DataScience Github [download here](https://github.com/kartikeyporwal/365datascience/blob/master/05%20-%20Statistics/6_Practical%20Example%20-%20Confidence%20Intervals/1_Practical%20Example%20-%20Confidence%20Intervals%20(10%3A05)/3.17.%20Practical%20example.%20Confidence%20intervals_lesson.xlsx)

The dataset consists of shoe sales categorized into two major groups:
Men's Shoes
Women's Shoes
Bundling these categories together could lead to misleading predictions, so they are analyzed separately. Additionally, the inventory is segmented by: 
1. Shoe Size
2. Country
3. Gender
Two tables were created: one for men's shoes and one for women's shoes.

## Problem Statement
What is the number of shoes that are likely to be sold based on historical data?

## Methodology & Game Plan
We will determine the 95% confidence interval for sales prediction using the following criteria:
1. Data from the last 12 months of sales.
2. Men's shoe sales only (as the problem focuses on male footwear).
3. Sales data from the Canada only (for consistency in market trends).

## Analysis Approach
For year 2016, we analyze the last 12 months of sales for men's shoes by shoe size.
Since we are dealing with a sample and the population variance is unknown, we will use the t-statistic for a 95% confidence interval with 11 degrees of freedom (n-1, where n = 12 months).


This gives the range in which we expect the true mean sales to lie with 95% confidence.

## Findings & Interpretation

After calculations, we found that in 95% of the cases, the true population sales for each shoe size will fall within the respective confidence interval.
The upper bound of the confidence interval represents the maximum number of pairs required (rounded up for inventory planning).

## Key Observations
Shoe sizes 42-43 show the highest sales potential.
Shoe sizes 39-40 and 49 show no recorded sales.![Men and women shoe sizes](https://github.com/user-attachments/assets/0c5aee52-2e9e-4e4e-8e77-603edc75053c)
![CI Table](https://github.com/user-attachments/assets/023d2522-2579-46b4-b089-4e458aedb7c0)
