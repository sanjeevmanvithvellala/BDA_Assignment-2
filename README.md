# 📊 Big Data Analytics using PySpark

## 🚀 Overview
This project demonstrates the implementation of core Big Data Analytics techniques using **PySpark MLlib**:

- 🔹 Classification (Fraud Detection)
- 🔹 Clustering (Customer Segmentation)
- 🔹 Recommendation System (MovieLens ALS)

The project is implemented in **Google Colab** using real-world datasets and includes evaluation metrics and visualizations.

---

## 🎯 Problem Statement
The objective of this project is to apply Big Data Analytics techniques to:

- Detect fraudulent transactions using classification models  
- Segment customers based on behavior using clustering  
- Build a recommendation system using collaborative filtering  

---

## 🛠️ Technologies Used

- Python 🐍  
- PySpark ⚡  
- Google Colab ☁️  
- Pandas 🧮  
- Matplotlib 📈  
- Seaborn 🎨  

---

## 📂 Datasets Used

### 1️⃣ Classification – Credit Card Fraud Detection
- Real-world dataset with highly imbalanced classes  
- Used to predict fraudulent transactions  

### 2️⃣ Clustering – Mall Customers Dataset
- Customer income and spending data  
- Used for segmentation using KMeans  

### 3️⃣ Recommendation System – MovieLens 100K
- User–movie ratings dataset  
- Used for collaborative filtering with ALS  

---

## ⚙️ Implementation Details

### 🔹 1. Classification (Logistic Regression)

- Feature vector creation using `VectorAssembler`
- Train-test split (80:20)
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC AUC

📊 Visualization:
- Confusion Matrix Heatmap  

---

### 🔹 2. Clustering (KMeans)

- Feature engineering using `VectorAssembler`
- Optimal K selection using **Elbow Method**
- Evaluation Metric:
  - Silhouette Score

📊 Visualization:
- Cluster Scatter Plot  
- Cluster Centers (Centroids)  

---

### 🔹 3. Recommendation System (ALS)

- Collaborative Filtering using ALS
- Train-test split on ratings data
- Evaluation Metric:
  - RMSE (Root Mean Square Error)

📊 Visualization:
- Actual vs Predicted Ratings Plot  

---

## 📊 Results Summary

| Model | Dataset | Metric | Value |
|------|--------|--------|------|
| Logistic Regression | Credit Card | ROC AUC | ~0.95 |
| KMeans | Mall Customers | Silhouette | ~0.5–0.7 |
| ALS | MovieLens | RMSE | ~0.9–1.1 |

---

## 🧠 Key Insights

- Fraud detection model performs well on imbalanced data using ROC AUC  
- Customer segmentation reveals distinct spending patterns  
- ALS effectively predicts user preferences and recommendations  

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**
2. Install PySpark:
!pip install pyspark

3. Upload datasets:
- `creditcard.csv`
- `Mall_Customers.csv`
- `u.data`
4. Run all cells sequentially  

---

## 📁 Project Structure
📦 BDA-PySpark-Project   
┣ 📜 BDA_Assignment.ipynb    
┣ 📜 README.md       
┣ 📂 datasets/     
┃ ┣ creditcard.csv      
┃ ┣ Mall_Customers.csv       
┃ ┗ u.data     


---

## 🎯 Learning Outcomes

- Hands-on experience with PySpark MLlib  
- Understanding of classification, clustering, and recommendation systems  
- Working with real-world datasets  
- Model evaluation and visualization techniques  

---

## 📌 Conclusion

This project demonstrates how PySpark can be used for scalable machine learning tasks including classification, clustering, and recommendation systems, providing practical exposure to Big Data Analytics.

---

## 👨‍💻 Author

- **Name:** V.Sanjeev Manvith 
- **Course:** Big Data Analytics  
- **Institution:** Chaitanya Bharathi Institute Of Technology
- **Submitted To:** Yenigalla Pallavi
