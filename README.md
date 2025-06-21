# Extracting Stock Data Using Web Scraping in Python

This is a small yet insightful project completed as part of the IBM Data Analyst Professional Certificate.  
It demonstrates two different methods to extract stock price data from a webpage and convert it into a clean, usable DataFrame.

---

## Project Objective

The goal is to extract stock historical data (Open, High, Low, Close, Volume, etc.) for companies like **Netflix** and **Amazon** using two different methods:

1. **Precision extraction** using `BeautifulSoup` (manual control)
2. **Quick automated extraction** using `pandas.read_html()` (when the table is well-formatted)

---

## Skills Practiced

- HTML Parsing with `BeautifulSoup`
- Web scraping logic with loops and tags
- Extracting `.text` and handling tag structures
- DataFrame creation and cleaning with `pandas`
- Comparison of scraping techniques for different use cases

---

## Techniques Compared

| Technique | When to Use | Library | Notes |
|----------|-------------|---------|-------|
| `BeautifulSoup` | When data is **unstructured or messy**, and precision is needed (e.g., multiple nested tags, custom parsing) | `bs4` | You manually control what tags to extract |
| `read_html()` | When data is inside a **standard, well-formatted HTML table** | `pandas` | Very fast, but less flexible than `bs4` |

This project demonstrates both.

---

## Files Included

| File | Description |
|------|-------------|
| `scrape_stock_data.ipynb` | Main notebook with all scraping logic |
| `netflix_soup_extract.csv` | Output from manual extraction with BeautifulSoup |
| `amazon_pandas_extract.csv` | Output from automated read_html() method |
| `README.md` | Project description

---
