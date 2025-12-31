# Student Exam Score Prediction 

This project aims to predict student exam scores based on study hours, sleep hours, attendance, and score history using Linear Regression, Random Forest, and Decision Tree modeling.

## Project Overview
* **Problems:** Is study time the only thing that affects exam scores, or are there other factors, such as sleep hours and their score history?
* **Tujuan:** Building a prediction model to help students estimate their score based on their academic habits.
* **Dataset:** Dummy data containing student identities, study hours, sleep hours, attendance rates, and score history.

## Tech Stack
* **Language:** `Python`
* **Libraries:** `Pandas`, `NumPy`, `Scikit-Learn`, `Matplotlib`, `Seaborn`

## Key Insights
1.  **Hours Studied** has the strongest positive correlation with exam score.
2.  **Sleep Hours** has no significant direct impact on score.
3.  No multicollinearity was found between independent variables.

## Model Performance
This project uses and compares three algorithms:

| Model | RMSE (Error Poin) | R2 Score |
|-------|-------------------|----------|
| **Linear Regression** | 2.76 | 0.87 |
| Random Forest | 3.41 | 0.80 |
| Decision Tree | 4.47 | 0.66 |

**Comparation Visualization:**
<img width="1013" height="518" alt="image" src="https://github.com/user-attachments/assets/746a9eed-0cab-4499-b9a9-d9e1e7064d30" />

**Conclusion:** Linear Regression was chosen because it performed better, producing a lower RMSE and higher $R^2$ score compared to Random Forest and Decision Tree for this dataset.

## Result Visualization
<img width="1033" height="642" alt="image" src="https://github.com/user-attachments/assets/2cf12712-8fc6-447c-870c-35ea577fcf31" />
