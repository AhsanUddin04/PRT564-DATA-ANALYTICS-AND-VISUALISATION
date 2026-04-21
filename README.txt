

##Before You Run

Open each notebook and find **Cell 1**.

Change the BASE path to the folder where you saved this project.
The folder should contain: "Raw_Dataset/" and "Notebook/"

```python
# Windows example
BASE = r"C:\Users\YourName\Desktop\Rana_Research_Workspace"

# Mac or Linux example
BASE = "/Users/YourName/Desktop/Rana_Research_Workspace"
```

**How to find your path:**
- Windows: Open the project folder in File Explorer → click the address bar at the top → copy the path
- Mac: Right click the folder → Hold Option → click "Copy as Pathname"

> Only change the BASE line. Do not change anything else.

---



## Run Order

Run the notebooks in this order:

1.Preprocessing_EDA.ipynb
- Cleans the raw data and creates EDA charts
- Must run first

2.Regression_Models.ipynb
- Builds OLS, Ridge and Lasso models
- Requires Step 1 to be completed first

3.Model_Evaluation.ipynb
- Evaluates models and runs statistical tests
- Requires Step 2 to be completed first



## Install Libraries

```
pip install pandas numpy matplotlib seaborn scikit-learn scipy openpyxl
```
