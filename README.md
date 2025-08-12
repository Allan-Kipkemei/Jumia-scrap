# 📱 Jumia Kenya Smartphones Scraper

This project is a simple Python web scraper that extracts smartphone listings from **[Jumia Kenya](https://www.jumia.co.ke/smartphones/)**.  
It uses **`requests`** to fetch the HTML content and **`BeautifulSoup`** to parse and extract the relevant data.

---

## 🚀 Features
- Scrapes smartphone listings from Jumia Kenya.
- Filters items based on specific HTML classes.
- Uses `lxml` parser for fast and reliable parsing.
- Easy to extend for additional product details (price, brand, rating, etc.).

---

## 🛠️ Requirements
Before running the script, ensure you have the following Python packages installed:

```bash
pip install requests beautifulsoup4 lxml
