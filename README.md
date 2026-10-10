# FIFA World Cup 2026 Match Prediction ⚽

## Project Overview

This project explores the use of machine learning to predict international football match outcomes using historical match data. It applies data preprocessing, feature engineering, and classification techniques to estimate whether the home team wins, the match ends in a draw, or the away team wins.

The project is designed as a sports analytics portfolio project that combines football data with predictive modelling.

## Objectives

- Analyse historical international football results.
- Engineer features that may influence match outcomes.
- Train and evaluate machine learning classification models.
- Compare model performance using appropriate evaluation metrics.
- Explore how machine learning can support football analytics.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn (if used in the notebook)
- Scikit-learn
- XGBoost (if used in the notebook)

## Dataset

The project uses historical international football match results, covering matches from 1872 to 2017.

The dataset includes match information such as teams, dates, scores, and match outcomes. Additional features, such as recent team form, goals scored and conceded, Elo ratings, or FIFA rankings, can be incorporated where available.

**Data source:** [Kaggle — International Football Results from 1872 to 2017](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017)

## Methodology

1. **Data preprocessing:** Load the dataset, inspect missing values, and prepare the match data.
2. **Feature engineering:** Explore historical performance, recent form, and other relevant team-strength indicators.
3. **Target encoding:** Represent home wins, draws, and away wins as three outcome classes.
4. **Model training:** Train and compare classification models.
5. **Model evaluation:** Assess predictive performance using accuracy, classification reports, and other appropriate metrics.

## Results

The project achieved approximately 60% accuracy in an evaluation run.

Accuracy alone does not fully describe performance across all three outcome classes. Draw prediction and class-level precision and recall are also important when evaluating football match predictions.

*Exact metrics, model configurations, and evaluation details should be updated to match the final notebook.*

## Limitations

- Historical results do not guarantee future match outcomes.
- Team strength and performance change over time.
- Injuries, line-ups, tactics, and tournament conditions may not be fully represented.
- Class imbalance can affect how well the model predicts draws and other outcomes.
- Predictions should be interpreted as estimates, not certainties.

## How to Run

1. Clone or download this repository.
2. Install the required Python packages.
3. Open the Jupyter Notebook.
4. Run the cells in order.

```bash
pip install pandas numpy scikit-learn jupyter
```

Install additional packages if the notebook uses them, such as XGBoost, Matplotlib, or Seaborn.

## Future Improvements

- Integrate updated FIFA rankings and Elo ratings.
- Improve recent-form and home-advantage features.
- Compare additional machine learning models.
- Use time-based validation to better simulate future predictions.
- Evaluate class-specific performance and probability calibration.
- Extend the model to upcoming international fixtures.

## Author

Developed as a machine learning and sports analytics portfolio project.

