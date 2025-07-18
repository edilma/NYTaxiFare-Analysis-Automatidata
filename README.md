
---

# 🗽 NYC Taxi Tip Prediction and Fare Analysis (2017)

**Machine Learning Project**

This is a data analytics and machine learning project focused on understanding tipping behavior and fare pricing in New York City’s yellow taxis during 2017. It was developed as part of the **Automatidata** program and demonstrates end-to-end skills in data wrangling, statistical analysis, regression, and classification modeling.

> ⚠️ **Note:** This project is still in progress and continues to be improved.

---

## 🎯 Project Objectives

* Perform full-cycle **data cleaning**, **feature engineering**, and **exploratory data analysis (EDA)**.
* Investigate the relationship between **payment type and fare amount** using hypothesis testing.
* Use **multiple linear regression** to predict fare amounts.
* Apply **tree-based models** (Random Forest and XGBoost) to classify whether a customer is likely to tip generously.

---

## 🗂️ Project Structure

| File                                        | Description                                                |
| ------------------------------------------- | ---------------------------------------------------------- |
| `00_intro_and_setup.ipynb`                  | Project setup and import of libraries                      |
| `01_data_cleaning_eda.ipynb`                | Data cleaning, preprocessing, and exploratory analysis     |
| `02_hypothesis_testing.ipynb`               | Tests whether payment type influences fare pricing         |
| `03_multiple_linear_regression_model.ipynb` | Builds regression model for fare prediction                |
| `04_random_forest_modeling.ipynb`           | Uses Random Forest and XGBoost to predict generous tipping |
| `Data_Dictionary.pdf` / `.xlsx`             | Dataset feature descriptions                               |
| `requirements.txt`                          | List of required Python packages                           |

---

## 🧠 Models Used

* **Multiple Linear Regression** — for predicting fare amount
* **Random Forest** & **XGBoost** — for classifying tipping behavior

---

## 🧪 Techniques Applied

* Data cleaning and transformation
* Feature engineering (e.g., `mean_distance`, `mean_duration`, `rush_hour_flag`)
* Outlier detection and handling
* Hypothesis testing (t-test)
* Hyperparameter tuning (GridSearchCV)
* Model evaluation: **F1-score**, **Accuracy**, **MAE**, **RMSE**, **R²**
* Feature importance analysis

---

## 📈 Key Results

* Using the **multiple linear regression model**, we found that:

  * **Mean distance** and **mean duration** were the most important features for predicting fare amount.
  * **Rush hour** trips also influenced the final rate.
* For **tipping behavior**:

  * **VendorID\_2** was the strongest predictor of generous tipping (possibly due to better service or newer vehicles).
  * **Passenger count** and **total fare** had more influence than trip duration or distance.
* These insights can help taxi operators understand pricing dynamics and improve service quality to increase tips.

---

## 📊 Data

* **Dataset**: `2017_Yellow_Taxi_Trip_Data.csv`
* **Source**: NYC Taxi and Limousine Commission
* **Data Dictionary**: Included in both `.pdf` and `.xlsx` formats

---

## 💻 Installation

Install required packages with:

```bash
pip install -r requirements.txt
```

---

## 📜 License  
This project is licensed under the terms of the MIT License.

✨ Author  
Built with 💻 by **Edilma Riano** using Python, pandas, and scikit-learn.

🎓 Developed as part of the **Google Advanced Data Analytics Professional Certificate** to demonstrate skills in data wrangling, statistical analysis, regression, and machine learning classification.


---

