# Weak Supervision applied for Fraud Detection

This project applies **weak supervision techniques** to identify and correct label noise in an artificially generated e-commerce fraud detection dataset. We use `Cleanlab` to detect mislabeled data and improve the performance and reliability of machine learning models.

## Project Structure

```
weak-supervision-fraud-detection
│
├── data/                   # Raw and processed datasets
│   └── Commerce_Transaction_Data_2.csv
│
├── notebooks/              # Jupyter notebooks for EDA, cleaning, feature engineering
|   ├──  analysis_univatiate_1.ipynb
|   ├──  analysis_bivariate_2.ipynb
|   ├──  data_preprocessing_3.ipynb
│   └── leanlab_4.ipynb
│
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── main.py                 # Entry point script
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/fraud-detection-weak-supervision.git
cd fraud-detection-weak-supervision
```

### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

## Features

- Clean noisy labels using `Cleanlab`
- Identify near-duplicates and outliers
- Visualize label quality and dataset issues

## Next Steps

- Integrate anomaly detection models

