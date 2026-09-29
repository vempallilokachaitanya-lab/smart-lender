# SMART LENDER – Loan Approval Prediction Using Machine Learning

## Project Overview
SMART LENDER is a Machine Learning-based web application that predicts whether a loan application will be Approved or Rejected based on applicant details.

## Features
- Loan Approval Prediction
- User-friendly Flask Web Interface
- Machine Learning Model
- Fast and Accurate Predictions

## Technologies Used
- Python
- Flask
- HTML
- CSS
- Scikit-learn
- NumPy
- Pandas
- Joblib

## Project Structure

SMART_LENDER/
│
├── DataSet/
│   └── loan_approval_dataset.csv
├── Flask/
│   ├── static/
│   ├── templates/
│   ├── app.py
│   ├── model.pkl
│   └── scaler.pkl
├── notebook.ipynb
├── README.md
└── requirements.txt

## How to Run

1. Clone the repository
2. Install the required packages

```bash
pip install -r requirements.txt
```

3. Run the application

```bash
python app.py
```

4. Open the browser and visit

```
http://127.0.0.1:5000
```

## Input Features

- Number of Dependents
- Education
- Self Employed
- Annual Income
- Loan Amount
- Loan Term
- CIBIL Score
- Residential Assets Value
- Commercial Assets Value
- Luxury Assets Value
- Bank Asset Value

## Output

- Loan Approved ✅
- Loan Rejected ❌

## Author

Sindhu
## Live Demo

👉 [Start Prediction](https://kandukurisindhu.pythonanywhere.com)
