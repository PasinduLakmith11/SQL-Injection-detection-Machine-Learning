
# 💻 SQL Injection Detection Using Machine Learning


This repository contains a machine learning model that detects SQL Injection (SQLi) attacks by classifying SQL queries as either **malicious** or **non-malicious**. It uses data preprocessing, feature engineering, and model training techniques to build an effective detection system.

## 🚀 Features

- **⚡ Data Preprocessing**: Cleans and prepares the SQL query dataset for training.
- **🧠 Machine Learning Model**: A supervised learning model trained on labeled SQL queries.
- **📊 Visualization**: Includes bar and pie charts to analyze the distribution of malicious vs. non-malicious SQL queries.

## 📂 Repository Structure

```
├── data/                 # Directory to store dataset
├── notebooks/            # Jupyter notebooks for data analysis and modeling
├── models/               # Trained models
├── images/               # Directory for visualizations and banners
├── README.md             # This file
├── requirements.txt      # List of required dependencies
└── SQLI_Model.ipynb      # Main Jupyter Notebook containing code
```

## ⚙️ Requirements

Ensure you have the following dependencies installed before running the notebook:

```bash
pip install -r requirements.txt
```

### Dependencies:
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `numpy`

## 🛠️ How to Use

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/sql-injection-detection
```

### 2. Navigate to the project directory:
```bash
cd sql-injection-detection
```

### 3. Install the required libraries:
```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter notebook:
```bash
jupyter notebook SQLI_Model.ipynb
```

### 5. Input Data:
Make sure your SQL query dataset is in the `data/` folder in CSV format. Modify the path in the notebook if needed.

### 6. Train the Model:
Follow the steps in the notebook to preprocess the data, train the model, and visualize the results.

## 📊 Visualizations

The notebook includes visualizations for better understanding the dataset:

- **Bar Chart**: Displays the count of malicious vs. non-malicious queries.
- **Pie Chart**: Shows the proportion of SQL injection attacks in the dataset.


## 🎯 Results

After training, the model will classify SQL queries based on patterns learned from the dataset. The notebook provides accuracy and other performance metrics to evaluate the model's effectiveness.


