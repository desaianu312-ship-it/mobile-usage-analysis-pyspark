# 📱 Mobile Usage Analytics & User Clustering using PySpark

## 🚀 Overview

This project leverages **PySpark** and **Machine Learning** to analyze mobile usage behavior and identify user patterns through **K-Means Clustering**. By processing screen-time and application usage data, the system categorizes users into distinct groups such as **Low Usage**, **Medium Usage**, and **Heavy Usage** users.

The project demonstrates the application of **Big Data Analytics**, **Data Processing**, **Machine Learning**, and **Data Visualization** to uncover meaningful insights from user behavior data.

---

## 🎯 Objectives

* Analyze mobile screen-time and app usage behavior.
* Process large datasets using PySpark.
* Apply K-Means clustering to segment users.
* Visualize user behavior patterns and trends.
* Generate insights for understanding digital consumption habits.

---

## ✨ Key Features

✅ Large-scale data processing using PySpark

✅ Data cleaning and preprocessing

✅ Feature engineering using VectorAssembler

✅ User segmentation using K-Means Clustering

✅ Cluster center analysis

✅ Data visualization with Matplotlib

✅ Gender-based screen-time analysis

✅ Actionable insights from user behavior patterns

---

## 🛠️ Technologies Used

| Technology         | Purpose                 |
| ------------------ | ----------------------- |
| Python             | Programming Language    |
| PySpark            | Big Data Processing     |
| Pandas             | Data Manipulation       |
| K-Means Clustering | Machine Learning        |
| Matplotlib         | Data Visualization      |
| Google Colab       | Development Environment |
| Excel Dataset      | Data Source             |

---

## 📂 Dataset Features

The dataset contains mobile usage statistics including:

* Daily Screen Time (Hours)
* Social Media Usage (Minutes)
* Gaming Usage (Minutes)
* Gender Information
* User Activity Metrics

---

## 🔍 Methodology

### 1. Environment Setup

* Installed Java and Apache Spark
* Configured Spark environment
* Initialized SparkSession

### 2. Data Preparation

* Imported dataset from Excel
* Converted Excel data into CSV format
* Loaded dataset into PySpark DataFrame
* Removed missing values

### 3. Feature Engineering

Selected features:

* Daily Screen Time Hours
* Social Media Usage Minutes
* Gaming Usage Minutes

Combined features using:

```python
VectorAssembler
```

### 4. User Clustering

Implemented:

```python
K-Means Clustering
```

with:

```python
k = 3
```

to classify users into:

* Low Usage Users
* Medium Usage Users
* Heavy Usage Users

### 5. Data Visualization

Generated:

* User Cluster Scatter Plot
* Gender-wise Screen Time Analysis
* Cluster Distribution Summary

---

## 📊 Results

The clustering algorithm successfully segmented users into three behavioral groups:

### Low Usage Users

Users with lower screen-time and reduced engagement across applications.

### Medium Usage Users

Users demonstrating balanced digital consumption patterns.

### Heavy Usage Users

Users exhibiting high screen-time and intensive app usage behavior.

The analysis provides valuable insights into user engagement and digital behavior trends.

---

## 📈 Sample Visualizations

### User Clustering

* Screen Time vs Social Media Usage
* Cluster-based User Segmentation

### Gender-Based Analysis

* Average Daily Screen Time by Gender

*(Add screenshots of generated graphs here)*

---

## 📸 Project Screenshots

### User Clustering Visualization

(<img width="985" height="621" alt="Screenshot 2026-06-17 134414" src="https://github.com/user-attachments/assets/9bd775de-bdc0-40fe-9f0f-7d5f832161c9" />
)

### Gender-Based Screen Time Analysis

(<img width="750" height="587" alt="Screenshot 2026-06-17 134426" src="https://github.com/user-attachments/assets/b005815b-7625-422c-872f-efd1ae23fe9a" />
)

---

## 💡 Key Learning Outcomes

* Big Data Processing using PySpark
* Machine Learning with K-Means Clustering
* Feature Engineering
* Data Visualization
* User Behavior Analytics
* Spark DataFrame Operations
* Real-world Data Analysis Workflow

---

## 🔮 Future Enhancements

* Advanced Clustering Techniques (DBSCAN, Hierarchical Clustering)
* Real-Time User Behavior Analytics
* Interactive Dashboard using Streamlit
* Predictive User Engagement Models
* Recommendation System Integration

---

## 👩‍💻 Author

**Anu**

B.Tech – Artificial Intelligence & Data Science

Passionate about Artificial Intelligence, Machine Learning, Data Analytics, and Big Data Technologies.

---

## ⭐ Support

If you found this project useful:

⭐ Star this repository

🍴 Fork the repository

💡 Share your feedback

---

## 📜 License

This project is intended for educational, research, and portfolio purposes.
