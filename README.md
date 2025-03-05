# PUBG Winner Prediction

## Overview
This project builds a machine learning model to predict PUBG match winners based on player performance metrics. It includes data preprocessing, exploratory data analysis (EDA), and predictive modeling using Random Forest and Linear Regression.

## Features
- **Data Preprocessing**: Handles missing values and removes outliers using the IQR method.
- **Exploratory Data Analysis (EDA)**: Generates histograms, correlation heatmaps, and boxplots.
- **Feature Engineering**: Selects key features like kills, damage dealt, walk distance, etc.
- **Model Training**:
  - **Random Forest Classifier** for winner prediction.
  - **Linear Regression** for win probability estimation.
- **Evaluation**: Measures model accuracy, mean squared error (MSE), and R² score.

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data Handling)
- **Seaborn, Matplotlib** (Visualization)
- **Scikit-Learn** (Machine Learning)

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/pubg-winner-prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```
3. Run the script:
   ```bash
   python pubg_winner_prediction.py
   ```

## Example Usage
```python
new_player = {"kills": 5, "damageDealt": 800, "walkDistance": 3000, "rideDistance": 500, "weaponsAcquired": 5, "heals": 2, "boosts": 3}
print(predict_winner_rf(new_player))
print(predict_win_probability_lr(new_player))
```

## Results
- **Random Forest Accuracy**: High prediction accuracy for match winners.
- **Linear Regression**: Provides win probability based on player stats.

## Future Improvements
- Hyperparameter tuning for better accuracy.
- Addition of more features for improved prediction.
- Deployment as a web application.

## License
MIT License

