# Diabetes Disease Prediction

This project uses machine learning techniques to predict the presence of diabetes based on patient demographic and clinical features.

## Project Structure

- **data/**  
  Contains the dataset used for training and evaluation:
  - `diabetes_data_upload (3) (1).csv`

- **notebooks/**  
  Jupyter notebooks for data exploration, feature selection, modeling, and reporting:
  - `diabetes prediction.ipynb` — Main notebook for data analysis and model building
  - `Feature selection diabetes.ipynb` — Feature selection process
  - `diabetes_prediction_report.ipynb` — Automated report generation

- **reports/**  
  Project reports and documentation:
  - `Diabetes_Disease_Prediction_Report.docx` — Main project report

## Dataset

The dataset includes 17 features such as age, gender, and various clinical symptoms, with the target variable indicating the presence (Positive) or absence (Negative) of diabetes.

## Getting Started

1. **Clone the repository**
2. **Install dependencies**  
   Recommended:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn jupyter python-docx
   ```
3. **Run the notebooks**  
   Open the notebooks in the `notebooks/` folder using Jupyter and follow the instructions.

## Results

The project explores multiple models (e.g., SVM, KNN), evaluates their performance, and generates a detailed report.  
See `reports/Diabetes_Disease_Prediction_Report.docx` for results and analysis.
