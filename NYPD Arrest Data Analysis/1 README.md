# NYPD 2023 Arrest Data Analysis
## Project Overview
This project was completed as part of the Data Science program at LaGuardia Community College. Using Python, I analyzed 2023 NYPD arrest data to explore arrest patterns across demographic groups, boroughs, precincts, and offense categories. The project involved examining arrest records, identifying precincts with the highest arrest counts, comparing arrests by gender, and investigating the most frequently recorded offense categories.

## Objectives
* Explore 2023 NYPD arrest data using Python.
* Identify the precincts with the highest numbers of recorded arrests.
* Compare arrest counts by gender and examine demographic patterns.
* Identify the most frequently recorded offense categories.
* Use visualizations to communicate patterns in arrest records.
* Consider potential bias in the dataset and the limitations of using arrest records to evaluate policing patterns.
  
## Tools & Technologies
* **Python** - data analysis and manipulation
* **Pandas** - data inspection, grouping, sorting, and aggregation
* **NumPy** - numerical operations and pie chart percentage calculations
* **Matplotlib** - data visualization
* **Seaborn** - statistical visualization library imported for analysis
* **Jupyter Notebook** - interactive analysis and documentation

## Dataset

The analysis used the NYPD Arrest Data Year to Date dataset for 2023, saved as NYPD_Arrest_Data__Year_to_Date__20231225.csv.
* **Dataset size**: 170,095 rows and 19 columns.
Source: NYPD arrest records covering the 2023 reporting period represented in the dataset.
Key fields: Arrest date, offense description, offense category, arrest borough, arrest precinct, age group, perpetrator sex, perpetrator race, and geographic coordinates.

The dataset provided information for exploring how recorded arrests were distributed across geographic areas, demographic categories, and offense types.

Methodology

Data Import and Inspection: Loaded the CSV dataset into Pandas and examined its dimensions, column names, and sample records using methods such as df.shape and df.head().

Data Selection and Grouping: Examined selected columns to identify useful measures for analysis. Grouped records by arrest precinct, perpetrator sex, and offense description to calculate arrest counts.

Precinct Analysis: Sorted precinct-level arrest counts in descending order to identify the five precincts with the highest numbers of recorded arrests.

Demographic Analysis: Grouped records by perpetrator sex and created a bar chart to compare arrest counts across the available categories.

Offense Analysis: Counted records by offense description and identified the most frequently recorded categories. Selected the five leading offense categories for a pie chart comparison.

Data Visualization: Used Matplotlib to create a bar chart and a pie chart to communicate the results of the analysis.

Data Interpretation and Bias Considerations: Considered how demographic and geographic patterns in arrest records should be interpreted, including the limitations of arrest data when evaluating potential differences in policing.

Data Visualization

The project used Matplotlib to visualize arrest patterns by gender and offense category.

Bar Chart (plot.bar()): Compared recorded arrest counts by perpetrator sex. The chart included a title, category labels, and an arrest-frequency axis.
Pie Chart (plt.pie()): Compared the five most frequently recorded offense categories. The chart included category labels, percentage annotations, record counts, and a title.
Grouped and Aggregated Data: Used Pandas groupby(), count(), and sort_values() to summarize and rank arrests by precinct, sex, and offense description before visualization.

These visualizations helped summarize categorical data and highlight differences in the distribution of recorded arrest events.

Key Findings

The analysis identified several notable patterns in the 2023 arrest records:

Precinct distribution: Precinct 14 in Manhattan recorded 5,817 arrests, followed by Precinct 75 in Brooklyn with 5,469, Precinct 44 in the Bronx with 5,407, Precinct 40 in the Bronx with 5,392, and Precinct 103 in Queens with 4,582. Together, these five precincts accounted for 26,667 records, or approximately 15.67% of the dataset.

Arrests by sex: The initial analysis reported that men accounted for approximately 80.8% of recorded arrests, women for approximately 17%, and unidentified categories for approximately 2%. These percentages are approximate and may not total exactly 100% because of rounding.

Most frequent offense category: Assault 3 & Related Offenses was the most frequently recorded category, with 25,200 records. Petit Larceny followed with 18,025 records, while Felony Assault accounted for 16,030 records.

Other frequent offense categories: Dangerous Drugs accounted for 11,526 records, and Miscellaneous Penal Law accounted for 11,132 records. These five categories were used in the pie chart to compare the most frequently recorded offenses.

The findings describe recorded arrest events in the analyzed dataset. They do not establish the underlying causes of arrest patterns or demonstrate that a particular community experienced a higher arrest rate.

Project Files
Dataset: NYPD_Arrest_Data__Year_to_Date__20231225.csv
Jupyter Notebook: ES Python Class Project 3 - NYPD Arrest Data.ipynb
Skills Demonstrated
Importing and inspecting public datasets
Data manipulation and aggregation with Pandas
Grouping, counting, and sorting records
Exploring demographic and geographic patterns
Creating bar charts and pie charts with Matplotlib
Calculating and interpreting proportions
Examining potential bias and limitations in public-sector data
Communicating findings through data-driven summaries
Reflection

This project provided practical experience using Python to investigate public-sector data and examine arrest patterns across precincts, demographic groups, and offense categories. It strengthened my skills in data inspection, grouping, aggregation, and visualization while highlighting the importance of considering data quality, potential bias, and the limitations of arrest records when interpreting findings about communities and policing.
