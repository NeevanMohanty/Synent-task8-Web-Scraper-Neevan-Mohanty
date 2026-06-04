# Synent-task8-Web-Scraper-Neevan-Mohanty
# Web Scraper

## Project Description

The Web Scraper is a Python-based application that extracts book data from a website using web scraping techniques. The project collects information such as book titles, prices, and availability, then stores the extracted data in both JSON and CSV formats.

This project demonstrates the fundamentals of web scraping, HTML parsing, data extraction, and file handling using Python.

## Features

* Extract book titles
* Extract book prices
* Extract availability status
* Store data in JSON format
* Store data in CSV format
* Display structured scraped data
* Simple and efficient implementation

## Technologies Used

* Python 3
* BeautifulSoup
* Requests Library
* JSON
* CSV

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/web-scraper.git
```

### 2. Navigate to the Project Directory

```bash
cd web-scraper
```

### 3. Install Required Libraries

```bash
pip install requests beautifulsoup4
```

### 4. Run the Python File

```bash
python web_scraper.py
```

## Website Used

https://books.toscrape.com

## Example Output

```text
===== SCRAPED BOOK DATA =====

Title        : A Light in the Attic
Price        : £51.77
Availability : In stock
```

## Concepts Used

* Web Scraping
* HTML Parsing
* File Handling
* Loops
* Dictionaries
* Lists
* JSON Handling
* CSV Handling

## Project Structure

```text
Web-Scraper/
│
├── web_scraper.py
├── books.json
├── books.csv
└── README.md
```

## Program Workflow

```text
Start
  |
  v
Access Website
  |
  v
Download HTML
  |
  v
Parse HTML using BeautifulSoup
  |
  v
Extract Required Data
  |
  v
Store Data in List
  |
  v
Save Data to JSON & CSV
  |
  v
Display Output
  |
  v
End
```

## Sample JSON Output

```json
[
    {
        "Title": "A Light in the Attic",
        "Price": "£51.77",
        "Availability": "In stock"
    }
]
```

## Sample CSV Output

```csv
Title,Price,Availability
A Light in the Attic,£51.77,In stock
```

---

## Purpose of the Project

This project was developed to:

* Learn web scraping techniques using Python
* Understand HTML document structure
* Practice data extraction and processing
* Work with JSON and CSV file formats
* Build a foundation for automation and data collection projects

## Future Improvements

* Scrape multiple pages automatically
* Extract additional book information
* Add image scraping functionality
* Export data to Excel format
* Create a graphical user interface (GUI)
* Schedule automatic scraping tasks
* Store data in a database
