# Naive Bayes Classification – NBA Player Longevity Prediction

## Project Overview
This project uses **Gaussian Naive Bayes** to predict whether an NBA player will last 5+ years in the league (`target_5yrs`). The analysis includes preprocessing, model training, evaluation with business-focused metrics (Precision & Recall), and critical discussion of the independence assumption in the context of sports analytics.

## Dataset
- **File**: `extracted_nba_players_data.csv`
- Target: `target_5yrs` (1 = lasted 5+ years, 0 = did not)
- Features: Player performance metrics (games played, minutes, points, FG%, etc.)

## Environment Setup

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
