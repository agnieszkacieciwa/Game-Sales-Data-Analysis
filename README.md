# Video Game Sales Analysis

## Introduction
This repository presents a detailed analysis of video game sales data, utilizing various data visualization and statistical techniques to uncover insights into the video game industry. Through this analysis, we aim to understand trends, patterns, and the overall dynamics of the video game market.

## Overview

### Dataset Description
This dataset contains sales data for over 16,500 video games. It includes information on game titles, platforms, release years, genres, publishers, and regional sales figures.

The dataset includes the following columns:
- **Rank:** The overall sales ranking of the game.
- **Name:** The name of the game.
- **Platform:** The platform on which the game was released (e.g., PC, PS4, Xbox One).
- **Year:** The year the game was released.
- **Genre:** The genre of the game (e.g., Action, Adventure, Sports).
- **Publisher:** The publisher of the game.
- **NA_Sales:** Sales in North America (in millions).
- **EU_Sales:** Sales in Europe (in millions).
- **JP_Sales:** Sales in Japan (in millions).
- **Other_Sales:** Sales in the rest of the world (in millions).
- **Global_Sales:** Total worldwide sales (in millions).

### Analysis and Visualizations

The analysis covers several aspects of the video game market, including:
1. **Data Cleaning and Preparation:** Handling missing values and duplicates, and providing summary statistics of the data.
2. **Regional Sales Distribution:** Exploring the distribution of sales across different regions (NA, EU, JP, Other).
3. **Platform Popularity:** Analyzing the number of games released on various gaming platforms.
4. **Genre Popularity:** Examining the popularity of different game genres.
5. **Top Publishers:** Identifying the top 10 publishers by global sales.
6. **Global Game Sales Over Time:** Tracking the trends in global game sales over the years.
7. **Sales Trend Prediction:** Using polynomial regression to predict future sales trends.
8. **Genre Trends Over Time:** Analyzing sales trends within specific game genres.
9. **Platform Evolution:** Investigating how the popularity of different gaming platforms has evolved over time.
10. **Correlation Between Genres and Sales:** Studying the correlation between game genres and sales in different regions.
11. **Regional Analysis:** Comparing the impact of different regions on game sales.
12. **Regional Preferences:** Analyzing genre and platform preferences in various regions.
    
Each section includes visualizations created using matplotlib and seaborn to provide clear and insightful presentations of the findings.

## Dependencies
To run the analysis scripts provided in this repository, you need the following dependencies:
- Python 3.x
- Required Python packages (`pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn` )

## Usage
To run the analysis, ensure you have Python installed along with the required libraries listed above. Adjust the paths to your CSV file (`vgsales.csv`) accordingly in the script, then execute the script. The results including visualizations and model evaluations will be displayed in the console and/or saved to files as specified.
