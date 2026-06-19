# 🌐 Largest U.S. Companies Web Scraping Project

## 📌 Project Overview

This project demonstrates the use of Python web scraping techniques to collect and structure real-world data from Wikipedia.

The objective was to scrape information about the largest companies in the United States by revenue, extract the data from an HTML table, and transform it into a structured dataset for future analysis.

The scraped data is stored in a Pandas DataFrame and exported to a CSV file for further processing and analysis.

---

## 🎯 Project Objectives

- Connect to a live website using Python.
- Extract tabular data from a webpage.
- Parse HTML content using BeautifulSoup.
- Store scraped data in a structured format.
- Export the cleaned dataset to a CSV file.

---

## 📂 Data Source

The data was collected from the Wikipedia page:

### Largest Companies in the United States by Revenue

The webpage contains a table listing major companies along with business-related metrics such as:

- Company Name
- Industry
- Revenue
- Number of Employees
- Headquarters
- Additional company information

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- BeautifulSoup4
- Requests
- Pandas

---

## 🔄 Project Workflow

### Step 1: Import Required Libraries

The project begins by importing the necessary Python libraries:

```python
from bs4 import BeautifulSoup
import requests
import pandas as pd
```

### Step 2: Access the Webpage

A request is sent to the target webpage using the Requests library.

```python
response = requests.get(url, headers=headers)
```

---

### Step 3: Parse HTML Content

BeautifulSoup is used to parse the webpage and allow navigation through HTML elements.

```python
soup = BeautifulSoup(response.text, "html.parser")
```

---

### Step 4: Locate the Data Table

The target HTML table is identified and extracted.

```python
table = soup.find_all('table')[0]
```

---

### Step 5: Extract Column Headers

The table headers are collected and cleaned.

```python
world_titles = table.find_all('th')
```

---

### Step 6: Create a DataFrame

A Pandas DataFrame is created using the extracted column names.

```python
df = pd.DataFrame(columns=world_table_titles)
```

---

### Step 7: Extract Table Rows

Each row of data is extracted and added to the DataFrame.

```python
for row in column_data[1:]:
```

This process converts raw HTML table data into a structured dataset.

---

### Step 8: Export Data

The final dataset is exported to a CSV file.

```python
df.to_csv('companies.csv')
```

---

## 📊 Output

The final output is a CSV file containing structured information about the largest companies in the United States by revenue.

The dataset can be used for:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Business Intelligence Dashboards
- Data Visualization
- Financial Analysis

---

## 💡 Skills Demonstrated

### Web Scraping
- HTML Parsing
- Data Extraction
- Web Requests

### Data Processing
- Data Structuring
- DataFrame Creation
- CSV Export

### Python Programming
- Working with Libraries
- Loops
- Data Manipulation

---

## 🚀 Potential Improvements

Future enhancements could include:

- Scraping multiple pages automatically
- Error handling for failed requests
- Automated data refreshes
- Data cleaning and preprocessing
- Visualization of company revenue trends
- Building dashboards using Tableau or Power BI

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience with:

- Web scraping using BeautifulSoup
- Working with HTML tables
- Extracting real-world data from websites
- Using Pandas for data organization
- Exporting data for further analysis

---

## 👤 Author

**Nico Nico**

Aspiring Data Analyst building practical projects in Python, SQL, Excel, Tableau, and Power BI.

---

## 📌 Project Summary

This project demonstrates how Python can be used to collect real-world business data from the web, transform it into a structured dataset, and prepare it for analysis and visualization.
