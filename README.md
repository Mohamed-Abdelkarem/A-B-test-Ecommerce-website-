# A/B Test of E-commerce Website

## Project Overview

This project involves conducting an A/B test on an e-commerce website to evaluate the impact of a new feature on user behavior and business metrics.

## Table of Contents

- [Introduction](#introduction)
- [Experiment Design](#experiment-design)
- [Data Collection](#data-collection)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Regression Analysis](#regression-analysis)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

In this project, I conducted an A/B test to evaluate the impact of a new feature on an e-commerce website. The goal was to determine whether the new feature improves user engagement and business metrics compared to the existing version.

## Experiment Design

The experiment was designed with two groups:
1. **Control Group**: Users who interacted with the existing version of the website.
2. **Treatment Group**: Users who interacted with the new feature.

Key metrics measured include:
- Conversion rate
- Average order value
- User engagement (e.g., time spent on site, number of pages visited)

## Data Collection

Data was collected from the e-commerce website's analytics platform. The dataset includes user interactions, transactions, and other relevant metrics. A total of 10,000 user sessions were recorded, with 5,000 sessions in each group.

## Data Cleaning

The collected data was cleaned to ensure accuracy and consistency. This involved:
- **Handling missing values**: Missing data was filled in with appropriate values or removed if it was not critical. For example, 200 sessions with incomplete data were removed.
- **Correcting data types**: Ensuring that all data fields had the correct data types, such as converting strings to dates or numbers.
- **Removing duplicates**: Duplicate entries were identified and removed to avoid skewing the analysis. For instance, 50 duplicate sessions were removed.
- **Filtering out irrelevant data**: Any data that was not relevant to the analysis was removed to focus on the important information.

## Data Analysis

The cleaned data was analyzed to compare the performance of the control and treatment groups. This included:
1. **Exploratory Data Analysis (EDA)**: Initial analysis to understand the data distribution, identify patterns, and detect anomalies. For example, histograms were used to visualize the distribution of session durations, and scatter plots were used to examine the relationship between session duration and conversion rate.
2. **Statistical analysis**: Applying statistical methods to summarize the data and draw inferences. For instance, descriptive statistics such as mean, median, and standard deviation were calculated to summarize the central tendency and variability of the data.
3. **Hypothesis testing**: To determine whether the new feature had a statistically significant impact on the conversion rate, a two-sample z-test was conducted. The steps included:
   - **Formulating Hypotheses**:
     - **Null Hypothesis (H0)**: The new feature does not affect the conversion rate.
     - **Alternative Hypothesis (H1)**: The new feature affects the conversion rate.
   - **Choosing a Significance Level**: A significance level (alpha) of 0.05 was chosen.
   - **Conducting the Test**: A two-sample z-test was used to compare the conversion rates of the control and treatment groups.
   - **Interpreting Results**: The p-value was greater than 0.05, indicating that the difference in conversion rates was not statistically significant. Therefore, the null hypothesis was not rejected.
4. **Data visualization**: Creating visualizations using libraries like Matplotlib and Seaborn to present the data in an easily understandable format. Examples of visualizations include:
   - **Bar charts**: To show the frequency of conversions in each group, revealing that the treatment group had a higher conversion rate.
   - **Line graphs**: To track the trend of user engagement metrics over time, showing that the new feature increased the average time spent on the site.
   - **Box plots**: To compare the distribution of average order values between the control and treatment groups.

## Regression Analysis

Regression analysis was used to ensure the A/B test was conducted correctly. This involved modeling the relationship between user engagement metrics (e.g., time spent on site, number of pages visited) and conversion rate. The regression analysis helped verify that the observed differences between the control and treatment groups were due to the new feature and not other confounding factors.

## Results

The results of the A/B test are presented through visualizations and summaries. Key findings include:
- **Conversion rate**: The treatment group had a conversion rate of 12%, compared to 10% in the control group. However, the difference was not statistically significant.
- **Average order value**: The average order value in the treatment group was $75, compared to $70 in the control group.
- **User engagement**: The treatment group showed an increase in user engagement, with an average session duration of 5 minutes compared to 4 minutes in the control group.

## Conclusion

Based on the results of the A/B test, the new feature did not have a statistically significant impact on conversion rates. Therefore, the final decision was to keep the existing version of the website. This project demonstrates the importance of experiment design, data cleaning, regression analysis, and visualization in evaluating the impact of changes on user behavior and business metrics.
