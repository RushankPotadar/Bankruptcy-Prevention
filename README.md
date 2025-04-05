## Bankruptcy Prevention 🏦📉

This project aims to build a machine learning model that predicts the likelihood of company bankruptcy based on financial indicators. The model utilizes a dataset containing various attributes that help distinguish between bankrupt and non-bankrupt firms.

### 🚀 Project Overview
Bankruptcy can significantly affect employees, stakeholders, and the overall economy. By analyzing financial data, this project attempts to forecast bankruptcy risk and help companies or analysts take preventive measures. It includes both a Jupyter notebook and a Python script, along with a trained model file for future inference.

### 📂 Project Structure
- `bankruptcy-prevention.xlsx`: The financial dataset used for training/testing the model.
- `Bank_Prev.py`: Python script version of the notebook, useful for deployment or automation.
- `Bankruptcy_Prevention-6.ipynb`: Jupyter notebook with full implementation – data loading, EDA, model training, and evaluation.
- `Bankruptcy_Prevention.pkl`: Saved model file (pickled) for reuse.
- `P-517 Bankruptcy.docx`: report documenting project information,features, and outcomes.

### 🧠 Techniques Used
- Data Preprocessing with Pandas
- Exploratory Data Analysis (EDA)
- Feature Scaling
- Model Building with Scikit-learn (e.g., SVM, Decision Tree, etc.)
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score
- Model Serialization using `pickle`

### 📊 Dataset
The Excel dataset includes company financials and a target label indicating bankruptcy status. Features include:
- Financial ratios (e.g., current ratio, debt ratio)
- Profitability indicators
- Liquidity measures

### 🔍 Key Features
- Binary classification (Bankrupt / Not Bankrupt)
- Model persistence via `.pkl` file
- Jupyter Notebook for EDA and prototyping
- Python script for scalable use

### ✅ Outcomes
- Successful model training with reliable performance metrics
- Final report and documentation for academic or business review
- Reusable components (scripts, model, visualizations)

### 📌 How to Use
1. Clone this repository
2. Open and run `Bankruptcy_Prevention-6.ipynb` to explore and modify the project
3. For the final output, run 'Bank_Prev.py'
4. Use `Bankruptcy_Prevention.pkl` for predictions with new data

