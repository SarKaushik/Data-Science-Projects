# Supplier Message Classification Project

## 📌 Project Overview
This project focuses on **classifying supplier messages in a supply chain context**. Using historical supply chain data, the model generates synthetic supplier messages and categorizes them into actionable classes such as:

- **Restock Request**
- **Price Concern**
- **Quality Issue**
- **General Inquiry**

The project demonstrates the application of **NLP, data preprocessing, class balancing, and machine learning classification** for practical supply chain scenarios.

---

## 🛠️ Technologies & Libraries
- **Python 3.9+**
- **pandas** – Data manipulation
- **numpy** – Numerical computations
- **scikit-learn** – Machine learning pipeline and evaluation
- **matplotlib & seaborn** – Visualization
- **Jupyter Notebook** – Project execution and experimentation

---

## 📂 Dataset
- Original dataset: `supply_chain_data.csv`
- Columns used: 
  - `SKU`, `Product type`, `Availability`, `Price`, `Defect rates`, `Lead time`
- Synthetic messages generated from dataset for classification.

---

## ⚙️ Key Steps in the Project
1. **Load & Clean Data**
   - Remove unnecessary columns, handle missing values.
2. **Generate Synthetic Supplier Messages**
   - Messages created based on inventory, price, and defect rates.
3. **Label Messages**
   - Logic-based labels assigned: `Restock Request`, `Price Concern`, `Quality Issue`, `General Inquiry`.
4. **Balance Dataset**
   - Upsampling applied to handle class imbalance.
5. **Train/Test Split**
   - 80/20 split with stratification to preserve label distribution.
6. **Build Machine Learning Pipeline**
   - `TfidfVectorizer` for text vectorization.
   - `LogisticRegression` for classification.
7. **Train & Evaluate Model**
   - Accuracy, classification report, and confusion matrix metrics.
8. **Visualize Confusion Matrix**
   - Heatmap visualization using `seaborn`.

---

## 📈 Model Performance
- **Accuracy:** ~ `Your accuracy here` (replace with actual value)
- **Classification Report:** Shows precision, recall, and F1-score per class.
- **Confusion Matrix:** Visual representation of prediction performance across classes.

---
