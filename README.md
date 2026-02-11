
#  T20 Cricket Score Prediction

A Machine Learning project that predicts the final score of a T20 cricket innings based on match conditions and live match statistics.

This project demonstrates data preprocessing, feature engineering, model training, evaluation, and prediction using real-world cricket match data.



##  Project Overview

In T20 cricket, predicting the final score during an ongoing match can help teams strategize better and assist analysts in understanding match dynamics.

This project builds a regression model that predicts the final score using features such as:

* Batting Team
* Bowling Team
* Current Runs
* Wickets Fallen
* Overs Completed
* Runs in Last 5 Overs
* Wickets in Last 5 Overs

The notebook walks through the complete Machine Learning pipeline from raw dataset to final prediction.



##  Features

* Data Cleaning and Preprocessing
* One-Hot Encoding for categorical variables
* Feature Selection
* Model Training using Regression Algorithms
* Model Evaluation using performance metrics
* Real-time score prediction function

---

##  Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn (for visualization)
* Jupyter Notebook

---

## 📂 Dataset

The dataset contains historical T20 match data including ball-by-ball or over-level statistics.

Key columns used:

* `batting_team`
* `bowling_team`
* `runs`
* `wickets`
* `overs`
* `runs_last_5`
* `wickets_last_5`
* `total_score` (Target variable)



## Installation & Setup

1. Clone the repository:

```bash
git clone https://

