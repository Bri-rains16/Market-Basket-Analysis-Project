# Market Basket Analysis using Apriori & FP-Growth

## 📌 Overview

This project applies market basket analysis on a real-world retail dataset to uncover product associations and build a recommendation system.

## ⚙️ Techniques Used

* Apriori Algorithm
* FP-Growth Algorithm
* Association Rules (Support, Confidence, Lift, Conviction)
* RFM Customer Segmentation
* Recommendation System

## 📊 Key Features

* Identified frequent itemsets from transaction data
* Compared Apriori vs FP-Growth performance
* Built a recommendation engine based on association rules
* Performed customer segmentation using RFM analysis
* Evaluated recommendation system using hit-rate

## 📈 Results

* Strong product associations discovered (lift up to ~19)
* Segment-specific buying patterns identified
* Personalized recommendations generated per customer

## 📂 Dataset

Online Retail II Dataset (UCI Repository)
👉 https://archive.ics.uci.edu/ml/datasets/online+retail+ii

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

## 💡 Future Improvements

* Deploy as interactive web app (Streamlit)
* Add collaborative filtering
* Real-time recommendation system
