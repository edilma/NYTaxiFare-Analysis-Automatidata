# NYC Taxi Tip Prediction and Fare Analysis (2017)

This project analyzes the 2017 NYC Yellow Taxi trip dataset to uncover patterns in tipping behavior and fare pricing. It uses data cleaning, exploratory analysis, hypothesis testing, regression, and classification models to answer key business questions.

## 🔍 Project Goals

- Perform end-to-end **data cleaning, feature engineering**, and EDA.
- Test if **payment type impacts fare amount** using hypothesis testing.
- Predict the **fare amount** using multiple linear regression.
- Predict if a customer will **tip generously** using classification models.


## 📁 Project Structure

| File/Notebook                         | Description |
|--------------------------------------|-------------|
| `00_intro_and_setup.ipynb`           | Loads libraries and provides project setup |
| `01_data_cleaning_eda.ipynb`         | Cleans and preprocesses the raw taxi trip data; performs exploratory data analysis (EDA) |
| `02_hypothesis_testing.ipynb`        | Tests whether payment type influences fare using hypothesis testing |
| `03_multiple_linear_regression_model.ipynb` | Builds a multiple linear regression model to predict fare amount |
| `04_random_forest_modeling.ipynb`    | Builds and compares Random Forest and XGBoost models to predict generous tippers |
| `Data_Dictionary.pdf` / `.xlsx`      | Describes dataset features |
| `requirements.txt`                   | Python package dependencies |

## 📊 Models Used

- **Random Forest** and **XGBoost** for classification
- **Multiple Linear Regression** for fare prediction

## 🧪 Techniques Applied

- Data cleaning and transformation
- Feature engineering (e.g., `mean_distance`, `mean_duration`)
- Outlier detection and handling
- Hypothesis testing (t-test)
- Hyperparameter tuning (GridSearchCV)
- Model evaluation: F1, Accuracy, MAE, RMSE, R²
- Feature importance analysis

## 📦 Dependencies

Install the required packages with:

```bash
pip install -r requirements.txt
``` 

### 📈 Key Results

- **Random Forest outperformed XGBoost**, achieving the highest F1 score in both cross-validation and test sets.
- **VendorID_2** was the most important feature in predicting whether a customer tips generously.
- The **multiple linear regression model** showed a good fit for predicting taxi fares, evaluated using **R², MAE, and RMSE**.
- **Hypothesis testing** revealed a statistically significant relationship between **payment type** and **fare amount**, suggesting that payment method may influence pricing.

---

### 📂 Data

- **Dataset**: `2017_Yellow_Taxi_Trip_Data.csv`
- **Source**: NYC Taxi and Limousine Commission
- **Data Dictionary**: Included as `Data_Dictionary.pdf` and `Yellow_Taxi_Trip_Data_Data_Dictionary.xlsx`

---

### 👩‍💻 Author

This project was developed as part of the **Automatidata** program.  
If you have questions or suggestions, feel free to explore the notebooks or get in touch!
