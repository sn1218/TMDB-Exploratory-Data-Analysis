# TMDB Exploratory Data Analysis
## Overview

This project involves exploratory data analysis (EDA) of the TMDB (The Movie Database) dataset to uncover patterns and insights about movie performance, including budget, revenue, and other factors. A significant portion of the data contains missing or unreliable values, such as movies with zero budget, revenue, or runtime, which was taken into account during the analysis.

Key findings include trends in movie releases, genre performance, and the relationship between budget and revenue. For example, 2011 was a particularly notable year with the highest number of movie releases, with Drama being the most produced genre, though Action films generated the most revenue. However, the revenue distribution for Action films shows a large disparity, with a few blockbuster films significantly outperforming the rest.

The analysis also highlights Avatar and Transformers: Dark of the Moon, two top-grossing films that outperformed their peers in both budget-to-revenue ratios and popularity metrics, with Avatar standing out as the overall top earner.

## The Project
### Dataset Description

The dataset consists of 4803 rows and 20 columns covering details such as budget, revenue, runtime, production company, etc.

### Tools and libraries
The tools used in this report are Python libraries - numpy, pandas, seaborn, and matplotlib.

### Project Workflow

1.) Data Cleaning: The dataset was cleaned by handling missing values, correcting data types, and addressing unrealistic entries (e.g., zero values for budget or revenue).

2.) Exploratory Data Analysis (EDA): A detailed exploration was conducted to reveal:
* Yearly trends in movie production.
* Correlations between budget, revenue, and popularity.
* Genre-specific performance, especially in 2011.

3.) Insights Summary: Key insights include the positive correlation between budget and revenue, the outperformance of select films like Avatar, and discrepancies in genre success, particularly in Action films.


