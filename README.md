# Naive Bayes Classification – NBA Player Longevity Prediction

## Project Overview
Gaussian Naive Bayes model to predict if an NBA rookie will play 5+ years (`target_5yrs`).

## Dataset
- File: `extracted_nba_players_data.csv`
- Target: `target_5yrs` (1 = longevity, 0 = bust)
- Features: GP, MIN, PTS, FGM, FGA, FG%, etc.

## Environment Setup
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
