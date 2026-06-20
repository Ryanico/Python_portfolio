# Programming Languages Trend Analysis 📊

This project explores the popularity of programming languages over time using data from **StackExchange**. The workflow demonstrates how to acquire, clean, manipulate, and visualize data with **Python**, **Pandas**, and **Matplotlib** in Jupyter Notebook.  
By analyzing post counts tagged with different languages, we uncover trends in developer interest, community engagement, and the rise or decline of specific technologies.

---

## Skills Demonstrated
This project demonstrates the following data analysis skills:

- **Data acquisition**  
  - Running SQL queries on StackExchange to retrieve fresh datasets.  
  - Importing `.csv` files into Pandas for reproducible analysis.  

- **Data cleaning**  
  - Converting raw date strings into proper datetime objects.  
  - Handling missing values with `fillna()` and ensuring consistent formatting.  

- **Exploratory data analysis (EDA)**  
  - Inspecting dataset dimensions with `shape` and `count`.  
  - Using `head()` and `tail()` to preview data samples.  
  - Grouping by language tags to calculate totals.  

- **Data manipulation with Pandas**  
  - Reshaping datasets with `pivot()` to align dates with language tags.  
  - Grouping and aggregating post counts by language.  
  - Counting months of data per language to identify gaps.  

- **Visualization with Matplotlib**  
  - Plotting single-language trends (e.g., Java).  
  - Comparing multiple languages on the same chart.  
  - Adding legends, labels, and axis formatting for clarity.  

- **Time series analysis**  
  - Applying rolling averages to smooth noisy data.  
  - Highlighting long-term popularity shifts across languages.  

- **Analytical thinking**  
  - Interpreting which languages grew, declined, or maintained steady interest.  
  - Recognizing the impact of older vs newer languages (e.g., C vs Swift).  

- **Working with Jupyter Notebooks**  
  - Combining code, markdown, and visualizations in a reproducible workflow.  
  - Documenting challenges and solutions step by step.  

---

## Future Improvements
Possible extensions of this project include:

- **Creating data visualizations for salary comparisons**  
  Linking language popularity to developer salary data for career insights.  

- **Building an interactive dashboard**  
  Using Plotly, Dash, or Streamlit to allow dynamic exploration of trends.  

- **Conducting deeper statistical analysis**  
  Applying regression, correlation, or forecasting models to predict future language popularity.  

- **Comparing programming language popularity with job market demand**  
  Integrating datasets from GitHub repositories or job boards to see how interest aligns with hiring trends.  

- **Automating monthly updates**  
  Scheduling queries to StackExchange so the dataset refreshes automatically.  

- **Expanding dataset scope**  
  Including additional languages (e.g., Rust, Kotlin, TypeScript) to capture emerging trends.  

---

## How to Run
1. Clone this repository:
2. cd programming-languages-trend-analysis
3. pip install pandas matplotlib jupyter
4. Open Programming_Languages_(start).ipynb and run the cells step by step.
   ```bash
   git clone https://github.com/your-username/programming-languages-trend-analysis.git
