# 📊 Web Scraping and Data Visualization Project

This project demonstrates the complete process of extracting structured data from public websites using **Python** and then transforming that data into **insightful visualizations**.

---

## TASK 1: Web Scraping

**Objective:** Extract book data from a publicly available e-commerce site using Python.

### 🔧 Tools & Libraries:
- `requests` – To send HTTP requests and fetch web pages.
- `BeautifulSoup` – For parsing HTML content.
- `csv` – To save the scraped data into a structured format (CSV).

### 📌 What Was Scraped:
- Book Title
- Price
- Availability
- Star Rating

### 📂 Output:
- `books_data.csv` – Contains structured data of books scraped from [books.toscrape.com](http://books.toscrape.com).

---

## TASK 2: Data Visualization

**Objective:** Use the scraped dataset to generate meaningful visualizations that reveal patterns in book pricing, rating, and availability.

### 📊 Visualizations:
1. **Bar Chart:** Distribution of Book Ratings (1 to 5 stars)
2. **Histogram:** Distribution of Book Prices
3. **Pie Chart:** Availability of Books (In stock vs. Out of stock)

### 🧰 Libraries Used:
- `pandas` – Data manipulation and cleaning
- `matplotlib` – Static plotting
- `seaborn` – Beautiful statistical plots built on top of matplotlib

### 📈 Insights Highlighted:
- Frequency of highly rated books
- Price trends and distribution
- Stock availability proportions

---

## 🧠 Learning Objectives
- Understand the basics of HTML structure and DOM parsing.
- Gain hands-on experience with Python web scraping using BeautifulSoup.
- Learn to clean and transform data for analysis.
- Build visually appealing plots to communicate insights effectively.

---

## 🚀 How to Run This Project

1. Open the project in **Google Colab**.
2. Run the **scraper script** to generate `books_data.csv`.
3. Execute the **visualization notebook** to generate charts and graphs.
4. Download/export graphs as needed for reports or portfolios.

---

## 📁 Files Included

- `web_scraper.py` or `scraper.ipynb` – Python script/notebook for scraping.
- `books_data.csv` – Clean dataset with book info.
- `visualization.ipynb` – Notebook with all visualizations.
- `README.md` – Project documentation.

---

## 📌 Credits

Data Source: [books.toscrape.com](http://books.toscrape.com) – A sandbox site for web scraping practice.
