# NBA Hall of Fame Prediction Model

## Overview
This machine learning project predicts NBA players' likelihood of being inducted into the Basketball Hall of Fame based on their career statistics and achievements. The model analyzes various performance metrics to identify patterns that distinguish Hall of Famers from other players.

## Features
- **Player Statistics**: Points, rebounds, assists, games played, etc.
- **Advanced Metrics**: Player Efficiency Rating (PER), Win Shares (WS), shooting percentages
- **Career Longevity**: Years active, career totals
- **Peak Performance**: Best seasonal performances

## Model Details
- **Algorithm**: Optimized Random Forest Classifier
- **Key Metrics**:
  - ROC-AUC: 0.917 (excellent discrimination)
  - Precision: 0.593
  - Recall: 0.457
  - F1-Score: 0.516
- **Class Handling**: 1:10 class weighting to address imbalance (3.33% HOF rate)

## Top Predictive Features
1. **Win Shares (WS)** - Most important factor (29% weight)
2. **Total Career Rebounds** (15%)
3. **Total Career Points** (13.8%)
4. **Points Per Game (PTS)** (9.4%)
5. **Average Seasonal Points** (7.7%)

## Data Characteristics
- **Time Period**: 1947-2025
- **Players**: 5,313 total (177 HOF inductees)
- **Missing Data**: Handled for FG3%, eFG%, and other stats

## Requirements
- Python 3.8+
- Scikit-learn
- Pandas
- NumPy
- Matplotlib/Seaborn

## Acknowledgments
Data sourced from Basketball-Reference.com, Kaggle.com and NBA.com

