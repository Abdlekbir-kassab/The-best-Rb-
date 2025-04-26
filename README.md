# Players Performance Analysis (2024-2025)

This project provides an in-depth analysis of the performance of three right-back football players during the 2024-2025 season. The goal is to compare their key statistics and help determine who has performed the best overall.

## Project Structure

This repository includes Python scripts and Jupyter notebooks for data analysis and visualization. The analysis is based on key statistics collected for each player throughout the season. The main steps include data cleaning, exploration, statistical analysis, and visualizations.

### Key Statistics Analyzed:
- **Goals (Goals Scored)**
- **Assists**
- **Expected Goals (xG)**
- **Expected Assists (xA)**
- **Key Passes**
- **Shots per Game**
- **Tackles per Game**
- **Interceptions**
- **Recoveries**
- **Dribbled Past**
- **Errors Leading to Goal**

## Data Preparation

The data for this analysis includes player stats for three right-back football players:
1. **Achraf Hakimi**
2. **Trent Alexander-Arnold**
3. **Jules Koundé**

The dataset contains individual player statistics such as goals, assists, expected goals, key passes, and defensive stats, along with total minutes played and match participation.

## Steps Followed in the Analysis

1. **Data Collection**  
   - Collected stats for each player and loaded them into a pandas DataFrame.
   
2. **Data Cleaning and Preprocessing**  
   - Checked for missing values and ensured that all necessary columns are present in the dataset.
   
3. **Exploratory Data Analysis (EDA)**  
   - Visualized the data using different plots to understand the trends and patterns in player performance.

4. **Statistical Analysis**  
   - Calculated key metrics such as averages and correlations to understand the relationship between different statistics.

5. **Visualizations**  
   - Plotted various charts including Bar Plots, Box Plots, Violin Plots, and Heatmaps to visually represent the performance comparison of the players.

## Key Visualizations

- **Bar Plots** for performance comparison:  
  A bar chart was created to visualize the overall performance of each player based on key stats such as goals, assists, expected goals, and expected assists.

- **Box Plots** to show the distribution of performance for each player:  
  Box plots were used to show the spread and median values for stats like goals per game, key passes, and defensive stats.

- **Violin Plots** to show the distribution of stats across all players:  
  These plots provide a more detailed view of the performance distribution for specific statistics.

- **Correlation Heatmap**:  
  A heatmap was created to show the correlations between various performance metrics, such as the relationship between goals scored and assists.

## Conclusion

This analysis allows us to compare the overall performance of the three players and determine who performed the best during the 2024-2025 season based on various key statistics. It is helpful for scouts, coaches, and analysts to evaluate the players' contributions to their teams.

## Requirements

- **Python 3.x**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**

You can install the required dependencies using:

```bash
pip install -r requirements.txt
