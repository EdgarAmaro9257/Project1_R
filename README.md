# Project: Statistical Analysis of WorldHits

## Project Overview

This project is designed to perform a comprehensive statistical analysis on the WorldHits dataset. The analysis includes both descriptive statistics and a linear regression model to explore and understand patterns in the data. Specifically, the focus is on investigating the relationship between the **Year** and **Duration** variables, offering insights into how the duration of popular songs has changed over time. By providing both numerical summaries and visualizations, this project aims to facilitate a clear interpretation of trends in the dataset.

## Purpose and Objectives

The primary objective of this project is to analyze historical trends in song durations (Duration) and how they have evolved across different years (Year). By examining this relationship, the analysis can provide insights into the following key questions:

- Has the average duration of popular songs increased or decreased over time?
- Are there significant variations in song durations in specific time periods?
- Is there a linear relationship between Year and Duration, or do other patterns emerge?

## Technology and Tool

[![My Skills](https://skillicons.dev/icons?i=r)](https://skillicons.dev)

## Project Structure

The project follows a well-organized and modular structure to ensure clarity, scalability, and ease of use. It is divided into several components, each focusing on a specific aspect of the analysis:

- **Data Loading**: The dataset, WorldHits.csv, is imported and prepared for analysis. This includes basic data cleaning steps such as handling missing values and - ensuring the correct data types.
- **Descriptive Statistics**: A summary of key statistics is provided for the Duration variable, including measures such as the mean, median, standard deviation, and variance. This helps establish a general understanding of how the duration of songs varies within the dataset.
- **Regression Analysis**: A linear regression model is employed to examine the relationship between Year and Duration. This analysis will determine whether there is a statistically significant trend in song durations over time and how strongly the two variables are correlated.
- **Visualization:** Graphical representations of the data are created to visually depict trends. A scatter plot with a regression line is used to show the relationship between Year and Duration, making it easier to interpret potential trends or anomalies in the data.

## Analysis Workflow

**1. Data Exploration:** The dataset is first explored to understand its structure and identify any necessary data cleaning steps. This includes checking for missing values, outliers, and understanding the distribution of the Duration variable.

**2. Descriptive Analysis:** Descriptive statistics provide a snapshot of the dataset. For Duration, metrics such as the average song length, variability, and distribution are calculated. These statistics give a clear understanding of the central tendency and dispersion of song durations over the years.

**3. Regression Model:** A linear regression model is applied to quantify the relationship between Year and Duration. This model helps answer the question of whether there is a consistent trend in how song durations have changed over time, and if the year significantly predicts song length. The model summary will include the regression coefficients, R-squared value, and p-values to assess the statistical significance of the relationship.

**4. Visualization:** To complement the numerical analysis, a scatter plot is generated, with Year on the x-axis and Duration on the y-axis. A fitted regression line is overlaid on the plot, providing a visual representation of the trend. This allows for an intuitive understanding of whether song durations have increased, decreased, or remained stable over time.

## Potential Insights

The analysis will yield insights into historical trends in song durations. For instance, if the regression analysis shows a negative slope, it may indicate that songs have become shorter over time. Conversely, a positive slope could suggest an increase in song lengths. Additionally, the analysis could uncover periods of rapid change or stability in the music industry, providing a valuable historical perspective on the evolution of popular music.

## Future Applications

This project serves as a foundation for further exploration of music data. Beyond the basic relationship between Year and Duration, future analyses could explore additional factors, such as genre, artist, or geographic region, to provide a more nuanced understanding of trends in the music industry. Moreover, incorporating more advanced statistical models or machine learning techniques could deepen the analysis and potentially reveal more complex patterns.

## Conclusion

This project provides a clear, structured approach to understanding how song durations have evolved over time. Through the use of descriptive statistics, regression analysis, and visualizations, it offers valuable insights into the relationship between Year and Duration. The modular and professional organization of the project ensures that it is easy to maintain, extend, and apply to similar datasets in the future.

## References
Kaggle: https://www.kaggle.com/datasets/thebumpkin/300-world-music-tracks-with-spotify-data
