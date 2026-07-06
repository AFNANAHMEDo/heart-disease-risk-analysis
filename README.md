

Heart Disease Risk Analysis

Heart disease risk analysis is done using patient health information. It makes use of the Cleveland Heart Disease dataset available on the UCI Machine Learning Repository. Several classification techniques have been tried to determine the best performing one.

Project Overview

Heart disease is one of the leading causes of mortality all over the world. Early prediction of heart disease improves decision-making for doctors.

I have done a complete machine learning process in this project that included:
- Data cleaning and pre-processing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Training of various machine learning models
- Model Evaluation
- Selection of the best performing model

Dataset

- Name of Dataset: UCI Cleveland Heart Disease Dataset
- Total number of records: 303
- Number of features: 13 clinical attributes
- Target variable: Heart disease presence

Features include:
- Patient age
- Patient sex
- Type of chest pain
- Resting blood pressure
- Cholesterol levels
- Fasting blood sugar level
- Resting electrocardiographic measurement
- Maximum heart rate achieved
- Exercise induced angina
- ST depression induced by exercise relative to rest
- Number of major vessels colored by fluoroscopy
- Thalassemia

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Project Workflow

1. Loading and inspection of dataset
2. Handling any missing values
3. Perform Exploratory Data Analysis (EDA)
4. Visualization of important patterns
5. Data preparation for modeling
6. Training of various machine learning models
7. Comparison of model performance
8. Selecting the best performing model
9. Drawing final conclusions

Machine Learning Models

The models that have been tried are:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Various evaluation metrics have been considered such as:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion matrix

Repository Structure

heart-disease-risk-analysis/

Heart_Disease_Modeling_Project.ipynb
processed.cleveland.data
requirements.txt
LICENSE
README.md

Getting Started

Clone the repository:
git clone https://github.com/AFNANAHMEDo/heart-disease-risk-analysis.git

Change to the directory:
cd heart-disease-risk-analysis

Install requirements:
pip install -r requirements.txt

Run Jupyter Notebook:
jupyter notebook

Start working on:
Heart_Disease_Modeling_Project.ipynb

##  Results

Different machine learning models were compared to determine which one performed best on the dataset. The notebook includes detailed evaluation metrics, visualizations, and comparisons that help explain each model's strengths and limitations.


## Future Improvements

- Hyperparameter tuning
- Feature selection techniques
- Cross-validation
- Model deployment using Flask or Streamlit
- Real-time prediction interface

---

## 👨‍💻 Author

**Afnan Ahmed**

GitHub: https://github.com/AFNANAHMEDo
