# 📄 VacancyMail Job Scraper

A simple Python web scraper that extracts the latest job listings from [VacancyMail Zimbabwe](https://vacancymail.co.zw/jobs/), parses key details, and exports them into a structured CSV file.

---

## 🧰 Features

- Scrapes job titles, descriptions, locations, expiry dates, and company names.
- Handles up to the first 10 jobs from the listings page.
- Logs scraping progress and errors using the built-in `logging` module.
- Saves job data to `scraped_data.csv`.
- Automatically handles unexpected changes (e.g. missing data fields).

---

## 🐍 Technologies Used

- `requests` – For sending HTTP GET requests.
- `BeautifulSoup` – For parsing and extracting data from HTML.
- `pandas` – For structuring data and exporting to CSV.
- `logging` – For monitoring progress and errors.

---

## 🚀 Getting Started

### 🔧 Requirements

Make sure you have **Python 3.6+** installed.

Install the required packages:

```bash
pip install requests beautifulsoup4 pandas
