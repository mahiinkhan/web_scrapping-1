# 📘 Task 1: Web Scraping Project – Book Data Extractor
## 🧾 Overview
This project demonstrates how to scrape structured book data from a public website using Python and BeautifulSoup. It collects book titles, prices, and availability from BooksToScrape.com, and saves the information into a CSV file for further analysis.

The project is beginner-friendly and includes a step-by-step explanation for understanding HTML structures, handling pagination, and writing the extracted data to a custom dataset.

## 📚 Data Source
### Website: https://books.toscrape.com
A sandbox site made specifically for practicing web scraping.

Each book listing contains:

Book Title

Price (in GBP)

Stock Availability

Star Rating (optional for future extensions)

## ✅ Features
Scrapes all 50 pages of book listings

Extracts:

Title

Price

Availability

Handles pagination

Saves data to a CSV file (/content/books_dataset.csv)

## 🧰 Technologies Used
| Tool            | Purpose                               |
| --------------- | ------------------------------------- |
| `requests`      | Downloading HTML pages                |
| `BeautifulSoup` | Parsing and extracting data from HTML |
| `csv`           | Writing structured data to file       |

## 🚀 Getting Started
1. Install Required Libraries
```bash
pip install requests beautifulsoup4
```
2. Run the Script
```bash
python scrape_books.py
```
This will create a CSV file called
```bash
books_dataset.csv
```
in your directory.

## 📁 Output
The script generates a file:
```bash
books_dataset.csv
```
| Title                | Price  | Availability |
| -------------------- | ------ | ------------ |
| A Light in the Attic | £51.77 | In stock     |
| Tipping the Velvet   | £53.74 | In stock     |
| Soumission           | £50.10 | In stock     |


## 📌 Project Structure
```bash
book-scraper/
├── scrape_books.py      # Main scraping script
├── books_dataset.csv    # Output file
└── README.md            # Project overview
```

## 🧠 Concepts Covered
Web scraping basics

Navigating and analyzing HTML structure

Handling pagination

Data extraction and formatting

Exporting to CSV
