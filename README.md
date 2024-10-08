# Loan_approval_prediction

## Dataset

The dataset contains the following features:

- **Gender**: Male or Female.
- **Married**: Marital status of the applicant.
- **Dependents**: Number of dependents of the applicant.
- **Education**: Education level (Graduate/Not Graduate).
- **Self_Employed**: Whether the applicant is self-employed.
- **Credit_History**: Whether the applicant has a history of paying debts.
- **Property_Area**: The location of the property (Urban, Rural, Semi-urban).
- **Loan_Status**: Target variable indicating if the loan is approved ('Y') or rejected ('N').
- **ApplicantIncome_log**: Log-transformed applicant's income.
- **LoanAmount_log**: Log-transformed loan amount.
- **Loan_Amount_Term_log**: Log-transformed loan amount term in months.
- **Total_Income_log**: Log-transformed total income (combination of applicant and co-applicant income).

## Installation

To run this project, you need to have Python installed on your system along with the following libraries:

### Step 1: Clone the Repository

git clone [here](https://github.com/GoutamIITP/Loan_approval_prediction.git).

### step 2: Set up a Virtual Environment

python -m venv env
.\env\Scripts\activate   # On Windows
source env/bin/activate  # On macOS/Linux

### Step 3: Install the Required Packages

pip install -r requirements.txt

# Project Structure

loan-approval-prediction/
│
├── data/                           # Contains the dataset (train.csv, test.csv)
├── env/                            # Virtual environment directory
├── notebooks/                      # Jupyter notebooks for analysis
├── src/                            # Source code for data processing and model training
│   ├── preprocess.py               # Data cleaning and preprocessing
│   ├── model.py                    # Machine learning model implementation
│   └── predict.py                  # Script to make predictions
├── requirements.txt                # List of dependencies
├── README.md                       # Project documentation
└── loan_approval.ipynb             # Main Jupyter notebook for analysis and modeling

### Model
We experimented with multiple machine learning models, including:

Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors(KNN)

### License

This `README.md` file provides an overview of the project, explains its purpose, and details how to install and use it, along with its structure. You can customize the sections and results based on your specific model's performance and functionality.
