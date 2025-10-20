# Loan Approval Prediction

This project predicts loan approval using **logistic regression**.

## Dataset
- File: `loan_data.xlsx`
- Target: Loan_Status (0 = Not Approved, 1 = Approved)
- Features: ApplicantIncome, LoanAmount, Credit_History, Property_Area, etc.

## Model Performance
- Accuracy: 82.1%
- AUC: 0.8529

### Class-wise Metrics

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Not Approved (0) | 0.72 | 0.68 | 0.70 |
| Approved (1) | 0.86 | 0.88 | 0.87 |

### Confusion Matrix

           Predicted
           0      1

### Key Insights
- Higher income & positive credit history → more likely approved.
- Urban/semiurban property area slightly increases approval chance.
- Can help pre-screen loans and flag risky applicants.

## How to Run
1. Install dependencies:
2. Run the Python file:
