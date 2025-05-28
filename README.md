# Hotel_dataset_webscrap
# 🏨 Bengaluru Hotels Scraper – 6000+ Hotels from Booking.com

This project involves web scraping hotel listings from [Booking.com](https://www.booking.com) specifically for **Bengaluru**, India. The goal was to collect real-world data for educational purposes and to practice data scraping, processing, and analysis using Python.

---

## 📌 Overview

- ✅ Scraped over **6000 hotel listings**
- ✅ Target website: Booking.com (search results pages for Bengaluru)
- ✅ Scraped using Python `requests` + `BeautifulSoup`
- ✅ Output stored in `CSV` format
- ✅ Intended for **data analysis**, **EDA**, and **machine learning practice**

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `scraper.py` or `scraper.ipynb` | Python script or Colab notebook used to scrape the data |
| `hotels.csv` | Final dataset with 6000+ hotel entries |
| `README.md` | You're reading it! Project summary and details |

---

## 🛠 Tech Stack

- Python 3
- BeautifulSoup (for HTML parsing)
- Requests (for HTTP requests)
- Pandas (for DataFrame creation)
- Jupyter/Colab (for notebooks)

---

## 📊 Data Columns Collected

| Column               | Description                            |
|----------------------|----------------------------------------|
| `hotel_name`         | Name of the hotel                      |
| `hotel_location`     | Area or neighborhood                   |
| `hotel_location_detail` | Sub-location/landmark or street     |
| `quality`            | Description like “Very Good”, “Excellent”, etc. |
| `reviews`            | Total number of reviews (if available) |
| `rating`             | Star or user rating                    |
| `price`              | Link to hotel details (not exact price) |



## 🚀 How It Works

The scraper:
1. Sends a request to Booking.com's Bengaluru hotel listing page
2. Parses each result block with `BeautifulSoup`
3. Extracts required fields like name, rating, reviews, etc.
4. Handles pagination using `offset` in URL (e.g., `&offset=25`, `&offset=50`)
5. Stores all entries into a Pandas DataFrame and saves as CSV

---

## 📌 Important Note

This data is collected **from public search result pages** and does **not access** any protected or user-specific content.

---

## ⚠️ Disclaimer

> This dataset is intended solely for **educational** and **non-commercial** purposes.
>
> All content, trademarks, logos, and property details belong to [Booking.com](https://www.booking.com) and their respective owners.
>
> Please do not use this dataset for commercial purposes or redistribution.

---



