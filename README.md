
# Premier League Match Outcome Prediction

This project explores predictive modeling for Premier League (PL) football matches using historical data. The objective is to build a machine learning model that forecasts the outcome (home win, draw, away win) of a match based on various match and team features.

## Project Overview

The workflow involves:

* **Data Preprocessing**: Cleaning and encoding categorical features.
* **Feature Engineering**: Selecting relevant features such as team names, match statistics, and results.
* **Model Training**: Using `RandomForestClassifier` and evaluating its accuracy.
* **Outcome Prediction**: Predicting future match results based on input features.

## Technologies Used

* Python (Pandas, NumPy, Scikit-learn)
* Jupyter Notebook
* Matplotlib (optional, for visualization)
* LabelEncoder for categorical variables

## Model Details

* Model Type: Random Forest Classifier
* Evaluation Metric: Accuracy score on test set
* Target Variable: `FTR` (Full-Time Result - 'H', 'D', 'A')

## How to Run

1. Clone the repository or download the `.ipynb` file.
2. Ensure you have Python and the required packages installed:

   ```bash
   pip install pandas numpy scikit-learn
   ```
3. Open the notebook in Jupyter Lab or Jupyter Notebook.
4. Run all cells to preprocess data, train the model, and evaluate results.

## Example Input

The model uses encoded features such as:

* HomeTeam
* AwayTeam
* FTHG (Home Goals)
* FTAG (Away Goals)

## Output

The notebook displays:

* Model accuracy
* Sample predictions from the test dataset


# Dataset Access

You can download it from the following link:

➡️ [Download PL_2023_2024_Dataset.csv ](https://www.football-data.co.uk/mmz4281/2324/E0.csv).

Once downloaded, place it in the root folder of the project to run the notebook as intended.
