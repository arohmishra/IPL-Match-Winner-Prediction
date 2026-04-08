# IPL-Predictor

# IPL Match Winner Prediction (Beginner ML Project)

This is a beginner-level Machine Learning project that predicts the winner of an IPL match using historical match data.

The project focuses on understanding the **end-to-end ML workflow** including data analysis, feature engineering, model building, and evaluation.

## Live Web App
👉 https://ipl-predictor.edgeone.app/

##  Project Objective
The goal of this project is to build a simple classification model that predicts whether **Team 1 will win the match or not**, based on match-related features.

## 📊 Dataset Used

* `matches.csv` → Match-level data
* 
## Exploratory Data Analysis (EDA)

Performed basic data analysis to understand:

* Most successful teams
* Impact of toss on match results
* Matches played across venues
* Season-wise trends

## Feature Engineering

The following features were created and used:

* `team1` and `team2` (encoded)
* `city` (encoded)
* `toss_winner`
* `toss_decision`
* `toss_winner_is_team1` (new feature)
* Target variable:

  * `1` → Team 1 wins
  * `0` → Team 2 wins

Categorical variables were encoded using **Label Encoding**.

## Model Used

* **Algorithm:** Logistic Regression
* **Type:** Binary Classification

## Model Training

* Train-Test Split: 80% training, 20% testing
* Model trained using `scikit-learn`

##  Model Evaluation

*  Accuracy Score
*  Confusion Matrix
*  Classification Report

The model provides a basic understanding of prediction but is not highly optimized.

## Tech Stack

* **Programming Language:** Python

* **Libraries Used:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn

* **Deployment:** Web page (EdgeOne Hosting)

---

## 📂 Project Structure

```bash
├── matches.csv
├── deliveries.csv
├── ipl.ipynb          # Main notebook (EDA + Model)
├── templates/         # HTML files
└── README.md
```

## Limitations

* Uses basic features only (no real-time match data)
* Model accuracy is limited due to simple approach
* No advanced feature engineering or tuning

---

## 📈 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Add more match features (runs, wickets, overs, etc.)
* Perform hyperparameter tuning
* Use real-time data for better predictions
* Improve UI and user interaction

---

## What I Learned

* Data cleaning and preprocessing
* Feature engineering basics
* Model training using Logistic Regression
* Model evaluation techniques
* End-to-end ML project workflow

## Author

Aroh Mishra
GitHub: [https://github.com/your-username](https://github.com/arohmishra)

This is my first Machine Learning project, built for learning and practice purposes.
