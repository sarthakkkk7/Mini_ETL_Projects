# 🧩 Data Engineering Mini ETL Projects

A collection of beginner-to-intermediate level **ETL (Extract, Transform, Load)** projects built using Python.  
Each project simulates a **real-world data engineering scenario** using public APIs, CSVs, or databases.

> 🎯 Objective: Practice working with raw data, apply transformations using `pandas`, and save clean outputs into structured formats (CSV, SQLite, etc.).

---

## 📁 Project Structure

Each project is contained in its own folder, with:
- Source code (`.py` or `.ipynb`)
- Cleaned data outputs (`.csv`, `.db`)
- Optional visualizations (`.png`)
- README (optional per project)

---

## 🚀 Projects Included

### 🛒 Superstore Sales ETL Pipeline
- 📂 **Source**: Superstore CSV
- ✅ Extracts, cleans, and transforms retail sales data
- 📊 Generates monthly revenue trends (line chart)
- 💾 Stores transformed data in SQLite using `sqlite3`
- 📂 Output: `cleaned_sales_data.csv`, `sales_trends.png`, `superstore.db`
  
### 💸 Crypto Price Tracker
- 📡 **Source**: CoinGecko API
- ✅ Extracts live prices of top 10 cryptocurrencies in INR
- 📊 Visualizes 24h % change using `matplotlib`
- 📂 Output: `crypto_prices_inr.csv`, bar chart

### ☁️ Weather Data ETL 
- 📡 **Source**: OpenWeatherMap API
- ✅ Fetches weather for user-selected cities with emoji condition
- 📊 Planned: historical trend tracking
- 📂 Output: Weather CSV

### 📺 YouTube Stats Collector *(Planned)*
- 📡 **Source**: YouTube Data API
- 🔄 Extracts video stats from a public channel
- 🔧 Aggregates views, likes, and publishing dates
- 📂 Output: Channel-wise video data CSV

---

## 🧠 Skills Practiced

- Python data scripting
- API integration & JSON parsing with `requests`
- Data manipulation using `pandas`
- File output to `.csv` and `.db`
- Data visualization using `matplotlib`
- SQLite storage for real-world pipelines

---

## 📌 How to Use

1. Clone the repository:
```bash
git clone https://github.com/sarthakkkk7/ETL-Projects.git
cd ETL-Projects
```

2. Open any project folder (e.g., `Crypto-Tracker/`, `Superstore-ETL/`)  
   and run the `.ipynb` or `.py` file.

3. View generated outputs like:
   - 📄 Cleaned CSVs
   - 📊 Visual Charts
   - 💾 SQLite DB files

---

## 👨🏼‍💻 Author

**Sarthak Satish Deshmukh**  
Data Engineering Enthusiast | Python & Cloud Learner  
🔗 [LinkedIn](https://www.linkedin.com/in/sarthak-deshmukh-398316235)  
📂 [GitHub](https://github.com/sarthakkkk7)

---

## ⭐ Star This Repo If You Found It Useful!

```bash
git add .
git commit -m "Added Superstore ETL to unified ETL Projects repo"
git push origin main
```

---
