# LEGO Data Analysis with Python

## Overview
This project explores LEGO datasets to uncover trends in LEGO colours, themes, set releases, and product complexity over time. Using Python, Pandas, and Matplotlib in Jupyter Notebook, the analysis answers a range of business-style and exploratory questions about LEGO’s history and growth.

The project focuses on cleaning, grouping, aggregating, and visualizing data to identify patterns in LEGO production across the years.

---

## Objectives
This analysis aims to answer questions such as:

- How many different LEGO colours exist?
- How many colours are transparent versus opaque?
- When were the first LEGO sets released?
- How many sets were released each year?
- How has the number of LEGO themes changed over time?
- Has the average size of LEGO sets increased over the years?
- Which LEGO themes have the highest number of sets?

---

## Datasets Used
The project uses multiple LEGO-related datasets, including:

- **colors.csv** — information about LEGO colours and transparency
- **sets.csv** — details about LEGO sets, release years, themes, and number of parts
- **themes.csv** — theme names and theme IDs

These datasets are used together to explore LEGO history and product trends.

---

## Tools and Libraries
This project was completed using:

- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

---

## Analysis Highlights

### 1. Colour Analysis
- Counted the number of unique LEGO colours
- Compared transparent and opaque colours

### 2. Set Release Analysis
- Identified the earliest LEGO sets in the dataset
- Analyzed the number of sets released year by year
- Visualized LEGO set releases with line charts

### 3. Theme Analysis
- Calculated how many unique themes were released each year
- Compared theme growth alongside set growth using dual-axis charts

### 4. Complexity Analysis
- Measured the average number of parts per set by year
- Used scatter plots to explore how LEGO set size has changed over time

### 5. Theme Popularity
- Counted the number of sets per theme
- Explored which themes, such as Star Wars, appear most often in the dataset

---

## Key Skills Demonstrated
This project demonstrates:

- Data loading and exploration
- Boolean filtering
- Grouping and aggregation with Pandas
- Sorting and counting values
- Working with multiple datasets
- Merging data through keys
- Data visualization with Matplotlib
- Trend analysis and storytelling with data

---

## Project Structure

lego-data-analysis
│
├── data
│   ├── colors.csv
│   ├── sets.csv
│   └── themes.csv
│
├── assets
│   ├── bricks.jpg
│   └── rebrickable_schema.png
│
├── Lego_Analysis_for_Course_(start).ipynb
└── README.md

Example Questions Explored

Some of the questions answered in this notebook include:

Which year had the first LEGO sets?
How many products were released in LEGO’s first year?
What are the top 5 LEGO sets with the most parts?
Did LEGO release more sets and themes over time?
Are modern LEGO sets larger on average than older ones?

How to Run the Project
Clone the repository
Open the notebook in Jupyter Notebook or JupyterLab
Make sure the data and assets folders are in the correct location
Run the notebook cells step by step

Conclusion

This project provides a useful exploratory analysis of LEGO data and shows how Python can be used to answer real analytical questions from raw datasets. It also highlights long-term trends in LEGO’s product range, themes, and set complexity.
