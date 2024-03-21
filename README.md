# NBA-fantasy-league-project
# NBA Fantasy Points Prediction with KNN Model

## Overview
This project applies a K-nearest neighbors (KNN) algorithm to predict NBA players' fantasy points for the upcoming season. It leverages historical player performance data to identify patterns and relationships that can inform future predictions.

## Features
- Data Normalization: Adjust player statistics to account for changes in game pace and style over the years.
- Similarity Ranking: Identify the top 10 historically similar players to any given player based on their stats.
- Weighted Averages: Calculate predicted performance metrics for players in the next season by considering the performance of their historical counterparts.

## Data
The model uses a dataset containing player stats from the past 20 NBA seasons. This data includes points per game, minutes played, field goal percentage, and other relevant metrics.

## Methodology
The project follows these steps:
1. Normalize player data from past seasons to align with current game trends.
2. Select the 10 most historically similar players based on a set of chosen features.
3. Rank and assign weights to these players based on their similarity scores.
4. Calculate weighted averages for each statistical category to predict the current players' performance in the upcoming season.
5. Repeat the process for all players to create a projection of their stats. 
