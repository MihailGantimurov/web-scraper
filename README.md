# 🔍 Web Scraper

Automated data collection script. Scrapes web sources, processes HTML, exports structured CSV.

## 🚀 Features
- HTTP sessions with retry on failure
- HTML parsing via BeautifulSoup
- Robust error handling (timeouts, bad status codes)
- Clean CSV output

## 🛠 Stack
Python · requests · BeautifulSoup · csv

## 📦 Install
```bash
pip install -r requirements.txt
```

## ▶️ Run
```bash
python scraper.py
```

## 📁 Output
Data saved to `output.csv`.