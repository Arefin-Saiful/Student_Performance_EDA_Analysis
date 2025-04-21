📊 Student Performance Prediction using Data Mining Techniques
This project applies data mining and regression modeling to predict student academic performance based on both academic and socio-demographic data. With over 30,000 student records, the analysis aims to uncover which features most effectively predict success in Math, Reading, and Writing scores.

🔍 Goal: Use machine learning to identify key predictors of student success and build reliable regression models for educational insights.

📁 Dataset Overview
Source: Kaggle: Students Exam Scores Dataset
Size: 30,641 records
Features:

Demographic: Gender, Ethnic Group, Parental Education, Marital Status

Behavioral: Practice Sports, Weekly Study Hours, Transport Means

Academic Scores: Math, Reading, Writing

🔧 Data Preprocessing
Missing Value Handling: Mode imputation for categorical features; median for numeric.

Outlier Detection: IQR-based filtering for numerical attributes.

Label Encoding: Applied to categorical variables.

Normalization:

Min-Max Scaling for discrete attributes (e.g., siblings)

Z-Score Scaling for performance scores

📈 Exploratory Data Analysis (EDA)
Correlation Analysis: Strong correlation between Reading, Writing, and Math scores (≥ 0.80)

Visual Tools Used:

Histograms, Boxplots, Correlation Matrix

Pair Plots & Scatter Plots to identify relationships

🤖 Model Building & Experiments
✅ Experiment 1: Predict Overall Score from Subject Scores
Method: Linear Regression

Result:

R²: 1.0 (Perfect prediction)

MAE: 0.0022

MSE: 0.000007

🔄 Experiment 2: Predict from Demographic & Behavioral Features
Method: Linear Regression

Result:

R²: 0.20

MAE: 10.25

RMSE: 12.54

📌 Insight: Subject scores are the best predictors of overall performance; demographic attributes contribute marginally.

📊 Key Insights
Math, Reading, and Writing scores are strongly interdependent and the most effective predictors.

Demographic/behavioral features alone cannot reliably predict student outcomes.

Future models could benefit from ensemble methods (e.g., Random Forest, Gradient Boosting).

💡 Recommendations
Focus academic intervention strategies on improving core subject performance.

Expand datasets to include more qualitative variables (motivation, teacher feedback, etc.).

Consider non-linear modeling techniques for better performance on complex features.

🛠 Tools & Libraries
Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)

Jupyter Notebook
