# Credit-card-fraud-detection

This project aims to detect fraudulent credit card transactions using various machine learning algorithms. It leverages anonymized and imbalanced transaction data to build and evaluate models capable of identifying suspicious activities in real time.


## 📊 Dataset

The dataset used is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains:

* **284,807** transactions
* **492** fraudulent transactions (highly imbalanced)
* **30** features:

  * `Time`, `Amount`, and 28 anonymized PCA-transformed features (`V1` to `V28`)
  * `Class` — the target label (0 = legitimate, 1 = fraud)


## 📌 Objectives

* Preprocess and explore the imbalanced dataset
* Use machine learning models to detect fraud
* Evaluate models using appropriate metrics for imbalanced data


## 🔧 Technologies & Tools

* **Python 3**
* **Jupyter Notebook**
* **Libraries**:
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `imblearn`


## 📈 Machine Learning Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)


## 🧪 Evaluation Metrics

Since the dataset is highly imbalanced, accuracy is not a reliable metric. The following metrics are emphasized:

* **Precision**
* **Recall**
* **F1-Score**
* **Confusion Matrix**

## 🗂️ Project Structure

Credit_Card_Fraud_Detection/
│
├── Credit_Card_Fraud_Detection.ipynb    # Main notebook
├── README.md                            # Project documentation
├── requirements.txt                     # List of Python dependencies (optional)
└── data/                                # Folder to store dataset (if needed)

## 🏁 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Credit_Card_Fraud_Detection.git
   cd Credit_Card_Fraud_Detection

2. Install dependencies:

   ```bash
   pip install -r requirements.txt

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   
4. Open and run `Credit_Card_Fraud_Detection.ipynb`.


## 📌 Insights

* Random Forest and XGBoost showed strong performance in identifying fraud.
* SMOTE effectively balanced the dataset, improving recall.
* Proper cross-validation is essential to avoid overfitting due to class imbalance.


## 📜 License

MIT License © 2025 \[kalyani jupally]
