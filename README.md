# 🧠 Apple MacBook Pro Web Scraper

This Python script extracts the current MacBook Pro models and their prices directly from the official Apple Store using `requests` and `BeautifulSoup`.

## 💡 Why this project?

This is a lightweight example of real-world web scraping, showing how to:
- Scrape structured product data from a dynamic e-commerce site
- Parse HTML content and extract relevant product titles and prices
- Handle potential HTML structure inconsistencies gracefully

## 🚀 How it works

1. Sends a `GET` request to [Apple’s official MacBook Pro store page](https://www.apple.com/shop/buy-mac/macbook-pro)
2. Locates product sections (`div.rc-productbundle-details`)
3. Extracts the product title and pricing
4. Prints a list of available models with their prices

## 📦 Requirements

- Python 3.8+
- `requests`
- `beautifulsoup4`

Install dependencies:
```bash
pip install requests beautifulsoup4

