# 📈 Stock Market Clustering using Hierarchical Clustering

## 🔍 About
A beginner machine learning project that clusters AAPL stock trading days 
into groups based on market behavior using Unsupervised Learning.

## 📊 Features Used
- **Daily Return** → (Close - Open) / Open
- **Daily Range** → High - Low
- **Volume Change** → Volume / Previous Volume

## 🛠️ Libraries Used
- yfinance
- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn

## 📌 Results
Identified **3 clusters** of trading days:

| Cluster | Type | Daily Return | Daily Range | Volume Change |
|---------|------|-------------|-------------|---------------|
| 0 | 😴 Calm days | 0.000270 | 4.21 | 1.02 |
| 1 | 🔥 Volatile days | 0.013426 | 21.15 | 1.28 |
| 2 | 📈 Normal days | 0.002557 | 9.62 | 1.31 |

## 🧠 What I Learned
- Collecting real stock data using yfinance
- Feature engineering on financial data
- Debugging real errors in data science
- Hierarchical Clustering with Ward linkage
- Dendrogram visualization
- Interpreting unsupervised learning results

## ▶️ How to Run
1. Install libraries: `pip install yfinance pandas matplotlib seaborn scipy scikit-learn`
2. Open `main.ipynb` in Jupyter Notebook
3. Run all cells
