# Diabetes risk screening
The objective of this project is to evaluate whether self-reported health, lifestyle, and demographic indicators collected through a large population survey can be used to identify
individuals at increased risk of diabetes. To that aim, two supervised classification models were selected for this analysis: Logistic Regression as an interpretable baseline, and 
CatBoost Classifier as a gradient boosting model well suited for datasets with a high proportion of categorical variables.

## Dataset

- Source: [Diabetes risk screening dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

All preprocessing steps (values encoding and handling of missing values or duplicated rows) are fully reproducible and implemented in the notebook.
At the end of the preprocessing pipeline, a cleaned dataset is exported as a CSV file for downstream modeling.  
This file is intentionally not included in the repository to keep it lightweight and to avoid versioning derived data.

## Tools Used

- **Google Colab** for data cleaning, visualization and machine learning modeling (Logistc regression and CatBoost classifier)

## Key Insights

- Both models achieved similar performance (ROC-AUC ≈ 0.82), suggesting that most of the predictive signal is largely linear.
- Given its interpretability, robustness, and competitive performance, logistic regression emerges as the recommended model for this dataset, particularly when transparency and auditability are priorities.
- Strong discrimination was achieved using only 21 survey features, indicating that effective diabetes risk screening may be possible with a reduced questionnaire.

## Files

- `Diabetes_risk_prediction.ipynb`: main notebook with all cleaning steps, plots, and insights.
- `Diabetes risk prediction - report.pdf`: descriptive report from the analysis.

## How to Run

- View the notebook directly in GitHub: [`Diabetes_risk_prediction.ipynb`](./Diabetes_risk_prediction.ipynb)
- Or open it in Google Colab to run it interactively: [Diabetes risk prediction notebook](https://colab.research.google.com/drive/1Du8zQ7McMuiiVN3Nw97EM3nAamekvxB9?usp=sharing)


## About Me

I'm a health sciences researcher transitioning into data science, with strong skills in data analysis, visualization, and scientific communication. You can see more of my work on my [GitHub profile](https://github.com/santib31).

---

>  This project is part of my **Data Science Portfolio**. Feedback and suggestions are welcome!
