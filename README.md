# User Activity and Anomaly Detection on Website Data

This repository contains analysis of user activity on websites as stored in a given CSV file. The data includes timestamps (in seconds) when activity was detected, the amount of money the user spent (USD), and several other anonymized features. Among the users, some are labeled as bots and the rest are genuine users.

## 📂 Contents

1. **`ResearchScript.ipynb`** 
    - Contains exploratory data analysis (EDA) of the user activities.
    - Development of a classification model to differentiate between bots and genuine users.
  
2. **`MainClustering.ipynb`**
    - Focuses on dimensionality reduction techniques, like PCA (Principal Component Analysis) and multidimensional scaling.
    - Application of different anomaly detection algorithms like an adapted version of DBSCAN clustering and one-class SVM.

## 🎯 Objectives

1. **Anomaly Detection**
    - Detect any anomalies in the dataset, assuming that the dataset is not labeled.
  
2. **Classification Model**
    - Develop a classifier to determine whether a given user activity belongs to a bot or a genuine user. The notebook should detail every step, including code, visualizations, and explanations.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone [[repository-url]](https://github.com/sneddy/FraudDetection.git)
   ```
2. Navigate to the repository directory:
   ```bash
   cd FraudDetection
   ```
3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## 📜 Data Description

- second: Timestamp in seconds when activity was detected.

- USD: Amount of money the user spent.

- Класс: Label indicating if the record belongs to a bot (bot) or a genuine user (не_бот).

- Other columns: Anonymized and transformed, but their proportions have been preserved.

## 🤝 Contribute
Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss the proposed change.
