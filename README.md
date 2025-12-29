# Diabetes risk screening
The objective of this project is to evaluate whether self-reported health, lifestyle, and demographic indicators collected through a large population survey can be used to identify individuals at increased risk of diabetes.

## 📁 Dataset

- Source: [Diabetes risk screening dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

## 🛠 Tools Used

- **Google Colab** for data cleaning, visualization and machine learning modeling (Logistc regression and CatBoost)

## 🔍 Key Insights

- Both models achieved similar performance (ROC-AUC ≈ 0.82), suggesting that most of the predictive signal is largely linear.
- Given its interpretability, robustness, and competitive performance, logistic regression emerges as the recommended model for this dataset, particularly when transparency and auditability are priorities.
- Strong discrimination was achieved using only 21 survey features, indicating that effective diabetes risk screening may be possible with a reduced questionnaire.

## 📎 Files

- `Hotel_Bookings.ipynb`: main notebook with all cleaning steps, plots, and insights.
- `Cleaned_hotel_bookings.csv`: processed dataset used for interactive dashboard generation.
- `Hotel bookings - report.pdf`: descriptive report from the analysis.

## 🚀 How to Run

- View the notebook directly in GitHub: [`Hotel_Bookings.ipynb`](./Hotel_Bookings.ipynb)
- Or open it in Google Colab to run it interactively: [Open In Colab](https://colab.research.google.com/drive/1dP5EWc7Bt-bFV1ESSgzswU5m8QdBLyxE?usp=sharing)


## 🙋‍♂️ About Me

I'm a health sciences researcher transitioning into data science, with strong skills in data analysis, visualization, and scientific communication. You can see more of my work on my [GitHub profile](https://github.com/santib31).

---

> 📌 This project is part of my **Data Science Portfolio**. Feedback and suggestions are welcome!
