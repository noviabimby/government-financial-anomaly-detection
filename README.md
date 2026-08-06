# Government Financial Anomaly Detection

This project focuses on detecting anomalous financial transactions in government financial reports using unsupervised machine learning approaches.

## Project Overview

The study compares the performance of Isolation Forest and Local Outlier Factor (LOF) in identifying anomalous transaction patterns within reconstructed government financial transaction datasets derived from LKPP/BPK RI reports.

The project applies audit-aware feature engineering and dimensionality reduction using TruncatedSVD to improve anomaly detection performance on structured financial transaction data.

---

## Methods

- Isolation Forest
- Local Outlier Factor (LOF)
- TruncatedSVD
- Audit-aware Feature Engineering

---

## Dataset Features

The dataset contains financial transaction attributes such as:

- Transaction Date
- Source Account
- Destination Account
- Transaction Amount
- Expenditure Category
- Transaction Description
- Anomaly Label

### Data Cleaning Result

![Data Cleaning](images/data_cleaning.png)

---

## Feature Engineering

The project applies several preprocessing and feature engineering techniques:

- Log Transformation
- Frequency Encoding
- Temporal Feature Extraction
- One-Hot Encoding
- TruncatedSVD Dimensionality Reduction

### Explained Variance Ratio

![Explained Variance](images/explained_variance_ratio.png)

### Cumulative Explained Variance

![Cumulative Variance](images/cumulative_variance.png)

### TruncatedSVD Output Example

![SVD Result](images/truncatedsvd_result.png)

---

## Model Evaluation

### Isolation Forest Performance

| Metric | Score |
|---|---|
| Accuracy | 0.8883 |
| Precision | 0.0827 |
| Recall | 0.1222 |
| F1-Score | 0.0987 |
| AUC | 0.5341 |

![Isolation Forest](images/isolation_forest_result.png)

---

### Local Outlier Factor (LOF) Performance

| Metric | Score |
|---|---|
| Accuracy | 0.7089 |
| Precision | 0.0517 |
| Recall | 0.2778 |
| F1-Score | 0.0871 |
| AUC | 0.5439 |

![LOF](images/lof_result.png)

---

## Confusion Matrix Comparison

![Confusion Matrix](images/confusion_matrix_comparison.png)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## Repository Structure

```text
├── anomaly_detection_lkpp.ipynb
├── images/
├── data/
├── results/
└── README.md

## Author

**Novia Putri Bimby**  
Bachelor of Computer Science (S.Kom)  
Machine Learning & Data Science Enthusiast  
Universitas Lancang Kuning

- LinkedIn: https://www.linkedin.com/in/novia-putri-bimby-7929401b4/
- Google Scholar: https://scholar.google.co.id/citations?view_op=list_works&hl=id&user=FoBjfaAAAAAJ
