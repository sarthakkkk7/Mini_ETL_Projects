# 🌦️ Weather ETL Pipeline using Python & OpenWeatherMap API

This project demonstrates a real-world **ETL (Extract, Transform, Load)** pipeline using live weather data. Weather info is extracted from the **OpenWeatherMap API**, cleaned and transformed using `pandas`, and loaded into a **SQLite database** — ideal for beginners entering the Data Engineering and Analytics domain.

---

## 🛠️ Tech Stack

- **Python**
- **pandas**
- **requests**
- **OpenWeatherMap API**
- **SQLite3**
- **dotenv** (for managing API key securely)

---

## 📌 Features

- Fetches weather data for Mumbai (Can be changed accordingly in the query)
- Extracts 12+ useful weather metrics like:
  - Temperature
  - Humidity
  - Weather description
  - Wind speed & direction
  - Cloudiness, Rain, and Snow volume
- Stores data into a relational **SQLite database**
- Timestamped and structured — ideal for future automation or scheduling

---


## 📁 Project Structure

```
Weather_ETL/
│
├── Weather_ETL.ipynb       # Jupyter notebook (full ETL logic)
├── weather_data.db         # SQLite database file (auto-generated)
├── .env                    # Stores API Key (not uploaded to GitHub)
└── README.md               # This file
```

---

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/weather-etl-pipeline.git
   cd weather-etl-pipeline
   ```

2. Create `.env` file in root directory:
   ```
   api_key =your_openweathermap_api_key
   ```

3. Install dependencies:
   ```bash
   pip install requests pandas python-dotenv
   ```

4. Run the notebook (`Weather_ETL.ipynb`) or convert to `.py` for automation.

---

## 🚀 Future Improvements

- Automate via `cron` or `Airflow`
- Store in PostgreSQL/MySQL instead of SQLite
- Add weather-based condition emojis 🌦️🌩️☀️
- Visualize trends with `matplotlib` or `seaborn`

---

## 📌 Motivation

This was built as part of a **"100 Days of Data Engineering"** challenge focused on building resume-worthy, beginner-friendly, real-world projects.

---

## 🙌 Author

**Sarthak Satish Deshmukh**  
🔗 [LinkedIn](https://www.linkedin.com/in/sarthak-deshmukh-398316235) | [GitHub](https://github.com/sarthakkkk7)

---

## 📄 License

Open for learning and inspiration. Attribution appreciated.
