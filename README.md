# TMDB Exploratory Data Analysis
## Overview

This project performs an exploratory data analysis (EDA) of the TMDB (The Movie Database) dataset, aiming to uncover trends, patterns, and insights related to movie performance metrics, such as budget, revenue, and genre. The dataset contains some missing or unreliable data (e.g., movies with zero budget, revenue, or runtime), which were carefully handled during the analysis to ensure accurate results.

Key findings include trends in movie releases, the performance of various genres, and the relationship between budget and revenue. For instance, 2011 was the most prolific year for movie releases, with Drama being the most produced genre. However, Action films dominated in terms of revenue, albeit with significant disparity, as a few blockbuster films heavily skewed the overall revenue distribution.

The analysis also identifies Avatar and Transformers: Dark of the Moon as standout top-grossing films, particularly for their impressive budget-to-revenue ratios and popularity metrics, with Avatar securing its position as the highest earner in the dataset.

## Objectives
The primary objectives of this project are:

* To explore trends in the film industry by analysing movie release patterns, budget, and revenue data.
* To identify the performance of various genres in terms of production volume and financial success.
* To examine the relationship between key metrics, such as budget and revenue, and investigate how certain films and genres outperform others.

## Project Details
### Tools and libraries
The following Python libraries were used in this project:

* pandas and numpy: For data cleaning, manipulation, and basic statistical analysis.
* matplotlib and seaborn: For data visualisation to uncover trends, correlations, and distributions.

### Dataset Description

The dataset consists of 4803 rows and 20 columns covering details such as budget, revenue, runtime, production company, etc.

### Data Preprocessing and EDA

The dataset was cleaned by handling missing values, correcting data types, and addressing unrealistic entries (e.g., zero values for budget or revenue).

The EDA focused on uncovering trends, correlations, and insights into various aspects of the film industry. Key areas of analysis included:

* Yearly Trends in Movie Releases:
  * The number of movie releases was analysed over time, revealing that 2011 saw the highest number of releases.
* Genre Performance:
  * Drama was the most frequently produced genre, while Action films were the most financially successful, although this success was skewed by a few blockbusters.
* Budget vs. Revenue Correlation:
  * There was a positive correlation between budget and revenue, suggesting that higher-budget films tend to generate higher returns.
* Top-Grossing Films:
  * Avatar and Transformers: Dark of the Moon emerged as outliers, both in terms of revenue generation and their exceptional budget-to-revenue ratios.
* Popularity vs. Financial Success:
  * Popularity scores were analysed to see how they align with financial success, and while some overlap exists, it was found that popularity is not always a reliable indicator of revenue.

### Insights and Findings
* 2011 had the highest number of movie releases.
* Drama dominated in production volume in 2011, but Action films, despite their smaller output, captured a large share of the revenue, with blockbusters like Avatar driving this trend.
* The relationship between budget and revenue was generally positive, but certain genres like Action showed a significant disparity, where a few high-budget films earned the majority of the revenue.
* Avatar stands out as the highest-grossing film in the dataset, both in terms of revenue and popularity.

## Repository Structure

* tmdb_movies.csv: The dataset used for the analysis.
* EDA.ipynb: The Jupyter notebook that contains the detailed exploratory data analysis, including data cleaning and visualisation.

## How to Use the Project

1. Clone the repository and download the dataset and notebooks.
2. Open the EDA.ipynb notebook to review the data cleaning process and explore trends in movie performance.
3. Visualise key insights from the dataset, such as trends in movie releases, budget-revenue correlations, and genre-specific success metrics.
4. Use the provided visualisations to explore further questions regarding movie performance in the TMDB dataset.




