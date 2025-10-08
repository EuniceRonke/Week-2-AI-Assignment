AI for Health: Predicting Diabetes Risk Using Machine Learning
Linked SDG:

SDG 3 – Good Health and Well-being
Ensure healthy lives and promote well-being for all at all ages.

📘 Project Overview

This project demonstrates how Machine Learning can support global health by predicting diabetes risk using health indicators such as glucose level, BMI, and age.
By identifying at-risk individuals early, the project promotes preventive healthcare and supports the UN Sustainable Development Goals (SDG 3).

🎯 Objective

To build a supervised machine learning model that classifies whether a person is likely to have diabetes, supporting early screening and public health awareness.

🧠 Machine Learning Approach

Type: Supervised Learning (Classification)

Algorithm: Random Forest Classifier

Tools: Python, Google Colab, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Dataset: Pima Indians Diabetes Database (Kaggle)

🧩 Project Workflow

Data Collection:
Loaded the Pima Indians Diabetes dataset containing 768 patient records.

Data Cleaning:
Replaced zero values in key health metrics (e.g., glucose, insulin) with median values.

Exploration & Visualization:

Correlation analysis and heatmaps

Distribution plots for Glucose, BMI, and Age

Model Building:

Trained a Random Forest Classifier

Split dataset into 80% training / 20% testing

Evaluation:

Achieved ~80% accuracy

Visualized confusion matrix and feature importance

📊 Results Summary
Metric	Result
Model Accuracy	~80%
Key Features	Glucose, BMI, Age, Insulin
Top Insight	Higher glucose and BMI are strong predictors of diabetes.

Visualizations:

Feature Importance Plot

Confusion Matrix

Correlation Heatmap

/screenshots/feature_importance.png
/screenshots/confusion_matrix.png

⚖️ Ethical Reflection

Bias: Dataset is limited to one population group, which may affect generalization.

Fairness: The model is designed to assist in awareness, not replace medical diagnosis.

Sustainability: Promotes early detection and prevention, aligning with SDG 3.

💻 How to Run the Project

Open Google Colab
.

Upload the notebook file Health.ipynb.

Run all cells sequentially.

Review accuracy, visualizations, and insights.

Repository Structure
AI-for-Health/
│
├── diabetes_prediction.ipynb   # Main Colab Notebook
├── README.md                   # Project documentation
├── /screenshots/               # Charts and output images

Project Impact

This project shows how AI can power sustainable healthcare systems by providing low-cost, data-driven tools to predict disease risk.
Through early awareness and prevention, we can take steps toward achieving Good Health and Well-being for all.

👩‍💻 Author

Eunice Fagbemide
PLP Academy – AI for Sustainable Development (Week 2 Assignment)
