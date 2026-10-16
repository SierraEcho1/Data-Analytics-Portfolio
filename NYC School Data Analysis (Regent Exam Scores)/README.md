# NYC School Data Analysis | Regents Exams
## Project Overview
This project was completed as part of the Data Science program at LaGuardia Community College. Using Python, I explored New York City Regents examination data from 2015, 2016, and 2017. The project involved examining school-level assessment data, reviewing examination categories, summarizing records by year, and using visualizations to compare the distribution of exam records.

## Objectives
* Explore NYC Regents examination data using Python.
* Examine the structure and dimensions of a large dataset.
* Compare the number of records across Regents examination types.
* Review dataset summaries across the 2015, 2016, and 2017 reporting years.
* Create visualizations to communicate patterns in the data.
## Tools & Technologies
* **Python** - data analysis
* **Pandas** - data loading, inspection, grouping, and summarization
* **Matplotlib** - data visualization
* **Jupyter Notebook** - interactive analysis and documentation
## Methodology
1. Data Import: Loaded the NYC Regents Report dataset from a public GitHub-hosted CSV file using Pandas.
2. Data Inspection: Reviewed the dataset's dimensions, column names, descriptive statistics, and sample records.
3. Grouping and Aggregation: Grouped records by Regents examination type and counted the records in each category.
4. Yearly Summary: Examined the distribution of the Mean Score field across reporting years.
5. Data Visualization: Created a bar chart to compare record counts across Regents examination types.
   
## Visualizations
* Bar Charts (plot.bar()): Used to compare record counts across Regents examination types.
* Histograms (plot.hist()): Used to examine the distribution of numerical values, including mean scores.
* Scatter Plots: Used to explore relationships between numerical variables.
* Grouped Comparison Bar Charts: Used to compare multiple groups side by side.

These visualizations helped summarize the dataset and communicate patterns across examination categories and reporting years.

## Key Findings
- **Dataset Size:** The dataset contained 212,331 rows and 15 columns.
- **Most Frequent Exam Category:** Common Core Algebra had the highest number of records, with 29,254, followed by Living Environment with 25,539.
- **Other Exam Categories:** U.S. History and Government had 20,426 records, while Common Core English had 19,878.
- **Records by Year:** The dataset contained 72,768 records for 2015, 76,123 for 2016, and 63,440 for 2017.
- **Data Quality Observation:** Some score fields contained values such as `s` and `na` rather than numeric results, which is important to recognize when preparing the data for further analysis.

The counts above represent dataset records grouped by examination type, not necessarily the number of individual students tested. A single school and exam combination may appear in multiple records.

## Project Files
View NYC Regents Data Jupyter Notebook
View NYC Regents Data Jupyter Notebook
## Skills Demonstrated
* Importing public datasets
* Inspecting dataset structure and descriptive statistics
* Data grouping and aggregation with Pandas
* Summarizing data by category and year
* Creating bar charts with Matplotlib
* Identifying non-numeric values in datasets
* Communicating findings through data summaries
## Reflection
This project provided practical experience working with public education data and using Python to explore a large dataset. It helped develop my understanding of data inspection, grouping, summarization, and visualization while highlighting the importance of recognizing inconsistent values during data analysis.
