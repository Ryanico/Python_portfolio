# 🛒 Amazon Product Price Tracker (Python Web Scraping)

## 📌 Project Overview

This project demonstrates how Python can be used to automatically collect product information from Amazon through web scraping. The script extracts product details such as the product title, current price, and the date the data was collected, then stores the information in a CSV file for future analysis.

The objective of this project is to simulate a simple price tracking system that can be expanded to monitor price changes over time.

---

## 🎯 Project Objectives

- Connect to an Amazon product page using Python.
- Scrape product information from the webpage.
- Extract the product title and current price.
- Store the scraped data in a CSV file.
- Build the foundation for an automated price tracking system.

---

## 📂 Project Features

- Connects to a live Amazon product page
- Parses HTML using BeautifulSoup
- Extracts:
  - Product Title
  - Product Price
  - Date Collected
- Saves the data into a CSV file
- Designed to support repeated data collection for price monitoring

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Requests
- BeautifulSoup4
- Pandas
- Datetime
- CSV

---

## 🔄 Project Workflow

### 1. Import Libraries

The project begins by importing the required Python libraries.

```python
import requests
from bs4 import BeautifulSoup
import pandas as pd
import datetime
import csv
```

---

### 2. Connect to Amazon

A request is sent to the Amazon product page using custom HTTP headers to simulate a browser request.

```python
page = requests.get(url, headers=headers)
```

---

### 3. Parse the HTML

BeautifulSoup is used to parse the webpage and navigate the HTML structure.

```python
soup = BeautifulSoup(page.content, "html.parser")
```

---

### 4. Extract Product Information

The script extracts important product information including:

- Product Title
- Product Price

The extracted text is cleaned before being stored.

---

### 5. Capture the Current Date

The current date is recorded whenever the script is executed.

```python
today = datetime.date.today()
```

This allows historical price tracking over time.

---

### 6. Save Data

The scraped information is written to a CSV file.

Example output:

| Title | Price | Date |
|--------|------:|------------|
| Meta Ray-Ban Smart Glasses | 17,616 | 2026-06-23 |

---

## 📊 Output

The script generates a CSV dataset containing product information that can later be used for:

- Price trend analysis
- Dashboard creation
- Data visualization
- Historical price comparison

---

## 💡 Skills Demonstrated

### Web Scraping
- Sending HTTP requests
- Parsing HTML documents
- Extracting webpage elements
- Working with browser headers

### Data Handling
- Data cleaning
- CSV file creation
- Data collection
- Date handling

### Python Programming
- Functions
- Variables
- Error handling
- File operations

---

## ⚠️ Challenges Encountered

Amazon pages are dynamic and frequently change their HTML structure. During development, several challenges were encountered, including:

- Dynamic page elements
- Changing HTML class names
- Multiple prices displayed on a single product page
- Regional pricing differences
- Anti-scraping protections that may return unexpected page content

These challenges provided valuable experience in debugging web scraping projects and writing more robust scraping logic.

---

## 🚀 Future Improvements

Planned enhancements include:

- Automatically collect prices daily
- Append new records instead of overwriting the dataset
- Track multiple products simultaneously
- Send email notifications when a price drops below a target value
- Create a Power BI or Tableau dashboard to visualize historical price changes
- Improve error handling for unavailable products or blocked requests

---

## 📚 Learning Outcomes

This project strengthened my understanding of:

- Web scraping using BeautifulSoup
- HTTP requests with custom headers
- Working with HTML elements
- Data collection automation
- Exporting structured datasets
- Debugging real-world web scraping challenges

---

## 👤 Author

**Nico Nico**

Aspiring Data Analyst building projects with **Python, SQL, Excel, Tableau, and Power BI** to develop practical data analytics skills.

---

## 📌 Project Summary

This project demonstrates how Python can be used to collect live product data from Amazon and store it in a structured format. It highlights practical skills in web scraping, data collection, automation, and data preparation, providing a foundation for building a complete price tracking system.
