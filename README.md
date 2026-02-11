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

##  Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn (for visualization)
* Jupyter Notebook

##  Dataset

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


##  Installation & Setup

1. Clone the repository:

bash
git clone https://github.com/your-username/t20-score-prediction.git
cd t20-score-prediction

2. Create a virtual environment (optional but recommended):

bash
python -m venv venv
venv\\Scripts\\activate   # On Windows


3. Install required dependencies:

bash
pip install -r requirements.txt


4. Open the notebook:

bash
jupyter notebook


##  Model Building Process

1. Data Cleaning
2. Handling categorical features using One-Hot Encoding
3. Splitting dataset into Training and Testing sets
4. Model Training (Linear Regression / Random Forest / etc.)
5. Model Evaluation using:

   * R² Score
   * Mean Absolute Error (MAE)
   * Mean Squared Error (MSE)

##  Model Performance

The model predicts the final T20 score with reasonable accuracy depending on match conditions.

Performance metrics may vary based on:

* Dataset size
* Feature engineering
* Algorithm selection

## How to Make Predictions

After training the model, you can use the prediction function by providing:

* Batting Team
* Bowling Team
* Current Runs
* Wickets Fallen
* Overs Completed
* Runs in Last 5 Overs
* Wickets in Last 5 Overs

The model outputs the predicted final score.

##  Project Structure


 t20-score-prediction
 ┣  t20_score_prediction.ipynb
 ┣  README.md
 ┣  requirements.txt
 ┗  dataset

##  Future Improvements

* Deploy as a Web App using Streamlit or Flask
* Hyperparameter tuning for better accuracy
* Add more contextual match features
* Use Deep Learning models for improved performance

## License

This project is open-source and available under the MIT License.

---

If you like this project, don’t forget to ⭐ star the repository!
