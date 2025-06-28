# 🧼 Superstore Sales ETL Pipeline

This project demonstrates a complete ETL (Extract, Transform, Load) workflow using a real-world retail sales dataset. It covers every step of the data engineering process — from raw data ingestion to cleaning, transformation, storage in both CSV and SQLite, and final visualization.

---

## 🚀 Project Overview

| Step        | Action                                                              |
|-------------|---------------------------------------------------------------------|
| 🗃️ Extract   | Loaded dataset directly from GitHub using Pandas                   |
| 🧹 Transform | Cleaned missing values, fixed data types, created new features     |
| 🗂️ Load      | Stored the cleaned data into a CSV file and SQLite database        |
| 📊 Analyze   | Visualized monthly sales trends using a line chart (Matplotlib)    |

---

## 🧠 Features

- ✅ Real dataset with fields like `Sales`, `Quantity`, `Profit`, `Order Date`
- ✅ Cleaned missing values and invalid dates
- ✅ Feature engineering: added `Month`, `Year`, and `Profit Margin`
- ✅ Exported clean data to `Cleaned_Superstore.csv`
- ✅ Stored structured data in `superstore.db` (SQLite format)
- ✅ Visualized **Monthly Sales Trends** via Matplotlib

---

## 📊 Sample Visualization

 📈 Monthly Revenue Trend Chart

![image](https://github.com/user-attachments/assets/d40a4b61-95b7-41e1-8c6c-75c20e66ac18)


---

## 🧰 Tech Stack

- Python 🐍  
- Pandas 🧹  
- SQLite 🗃️  
- Matplotlib 📊  
- Jupyter Notebook 📒

---

## 🗃️ Project Structure

```
Superstore_ETL/
├── Superstore_ETL.ipynb
├── Cleaned_Superstore.csv
├── superstore.db
├── requirements.txt (optional)
└── README.md
```

---

## 📂 Dataset Source

[📎 PySpaceCode – Global Superstore Dataset (GitHub)](https://github.com/PySpaceCode/Global-Superstore)

---

## ✅ How to Run

```bash
pip install pandas matplotlib
jupyter notebook
```

Open `Superstore_ETL.ipynb` and run all cells to reproduce the pipeline.

---

## 🧠 Author

**Sarthak Satish Deshmukh**  
[GitHub](https://github.com/sarthakkkk7) • [LinkedIn](https://www.linkedin.com/in/sarthak-deshmukh-398316235)

---

> “Data is the new oil. This is your refinery.” – Built with Python 🐍
