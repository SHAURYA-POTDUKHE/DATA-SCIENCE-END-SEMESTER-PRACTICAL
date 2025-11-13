# ---------------------------------------------------------------
# NAME: Shaurya Potdukhe
# PRN: 22070521011
# SECTION: A
# EXPERIMENT: Implementation of Simple Linear Regression on Auto MPG Dataset
# ---------------------------------------------------------------

# README

### NAME: Shaurya Potdukhe
### PRN: 22070521011
### SECTION: A

---

## TITLE:
Implementation of Simple Linear Regression on Auto MPG Dataset

---

## AIM:
To implement a Simple Linear Regression model to predict fuel efficiency (miles per gallon)
of cars based on their weight using the Auto MPG dataset.

---

## DATASET USED:
Auto MPG Dataset (from UCI Machine Learning Repository)

**Attributes:**
| Feature | Description |
|----------|-------------|
| mpg | Miles per gallon (target variable) |
| cylinders | Number of engine cylinders |
| displacement | Engine displacement (cubic inches) |
| horsepower | Engine power |
| weight | Vehicle weight (lbs) |
| acceleration | 0–60 mph acceleration time (seconds) |
| model year | Year of manufacture |
| origin | Origin of car (1: USA, 2: Europe, 3: Japan) |
| car name | Model name |

---

## TOOLS AND LIBRARIES USED:
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn (LinearRegression, train_test_split, metrics)

---

## STEPS PERFORMED:
1. Load and clean the dataset.
2. Select features: 
   - Independent variable (X): weight
   - Dependent variable (Y): mpg
3. Split data into training (80%) and testing (20%).
4. Train the Linear Regression model using Scikit-learn.
5. Evaluate the model using R², MAE, and RMSE.
6. Visualize results using scatter plots and residual plots.

---

## RESULTS:
**Regression Equation:**
mpg = 46.216 - 0.0076 × weight

**Model Performance:**
- R² Score ≈ 0.71
- MAE ≈ 2.4
- RMSE ≈ 3.1

**Interpretation:**
There is a strong negative correlation between vehicle weight and fuel efficiency.
As car weight increases, the MPG value decreases.

---

## CONCLUSION:
The Simple Linear Regression model effectively predicts car fuel efficiency based on weight.
The results confirm that vehicle weight is a major factor affecting MPG.
Further improvement can be achieved using Multiple Linear Regression or Polynomial Regression.

---

## GRAPHICAL INSIGHT:
A scatter plot of Weight vs MPG shows a downward trend (negative linear relationship).

