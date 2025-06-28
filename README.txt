
Predicting Medical Appointment No-Shows in Brazil
=================================================

This project analyzes factors that influence whether patients attend their medical appointments
and builds a machine learning model to predict no-shows.

-------------------------------------------------
Project Overview
-------------------------------------------------
In Brazil, missed medical appointments can create scheduling gaps and inefficiencies in healthcare delivery.
Using a dataset of ~100,000 appointments, this analysis explores:
- Which factors correlate most with no-shows
- The effect of SMS reminders
- Attendance differences by age and gender

-------------------------------------------------
Technologies Used
-------------------------------------------------
- Python
- Pandas, NumPy
- scikit-learn (for machine learning)
- Seaborn & Matplotlib (for data visualization)
- Jupyter Notebook

-------------------------------------------------
Project Steps
-------------------------------------------------
1. Data Loading & Cleaning
   - Standardized column names
   - Converted date fields to datetime
   - Mapped target variable (No-show) to binary (1 = no-show, 0 = show)
   - Removed duplicates and handled missing data

2. Exploratory Data Analysis
   - Visualized distributions and correlations between features and attendance
   - Analyzed the impact of age, gender, medical conditions, and SMS reminders

3. Machine Learning Model
   - Prepared data: encoding categorical variables and scaling features
   - Built a Logistic Regression classifier to predict no-shows
   - Evaluated model with accuracy score, confusion matrix, and classification report

-------------------------------------------------
Key Findings
-------------------------------------------------
- Some features, like receiving an SMS reminder or age, can influence attendance rates.
- Logistic Regression provides a solid baseline; further improvement possible using tree-based models (Random Forest, XGBoost).

-------------------------------------------------
How to Run
-------------------------------------------------
1. Clone the repo:
   git clone https://github.com/yourusername/no-show-prediction.git

2. Install dependencies:
   pip install -r requirements.txt

3. Open the Jupyter notebook:
   jupyter notebook no_show_appointments_analysis.ipynb

-------------------------------------------------
Dataset
-------------------------------------------------
Original dataset available on Kaggle:
https://www.kaggle.com/datasets/joniarroba/noshowappointments

-------------------------------------------------
Contributions
-------------------------------------------------
Feel free to fork, suggest improvements, or extend the project with new models and features!
