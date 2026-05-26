# PRT564 - Data Analytics and Visualisation
## Group 15, Sydney Campus, Charles Darwin University

================================================================
## Repository Structure

Raw_Dataset/              - Original ABS Excel files (catalogue 6416.0)
Assessment_2_Notebook/    - Regression notebooks (OLS, Ridge, Lasso)
Assessment_4_Notebook/    - Classification notebooks (NB, SVM, RF)

================================================================
## Before You Run

Open each notebook and find Cell 1.
Change the BASE path to the folder where you saved this project.
The folder should contain: "Raw_Dataset/", "Assessment_2_Notebook/" 
and "Assessment_4_Notebook/"

Example (Windows):
BASE = r"C:\Users\YourName\Downloads\PRT564-Project"

Example (Mac/Linux):
BASE = "/Users/YourName/Downloads/PRT564-Project"

Or use a relative path if running from the project folder:
BASE = "."

================================================================
## Assessment 2 - Regression (RPPI Forecasting)

Notebooks (run in order):
1. Preprocessing_EDA.ipynb
2. Regression_Models.ipynb
3. Model_Evaluation.ipynb

Models: OLS, Ridge, Lasso
Test period: 2018-Q3 to 2021-Q4

================================================================
## Assessment 4 - Classification (Market Cycle Phase)

Notebooks (run in order):
1. A4_Preprocessing_EDA.ipynb
2. A4_Classification_Models.ipynb
3. A4_Model_Evaluation.ipynb

Models: Naive Bayes, SVM (RBF kernel), Random Forest
Classes: Boom (>10% YoY), Normal (0-10%), Decline (<0%)
Best model: Random Forest, 94.64% test accuracy, macro F1 = 0.946

================================================================
## Required Python Packages

pandas, numpy, scikit-learn, matplotlib, seaborn, openpyxl

Install all at once:
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
