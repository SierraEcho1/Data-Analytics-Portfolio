# NYPD 2023 Arrest Data Analysis
## Project Overview
This project was completed as part of the Data Science program at LaGuardia Community College. Using Python, I analyzed 2023 NYPD arrest data to explore arrest patterns across demographic groups, boroughs, precincts, and offense categories. The project involved examining arrest records, identifying precincts with the highest arrest counts, comparing arrests by gender, and investigating the most frequently recorded offense categories.

## Objectives
Explore 2023 NYPD arrest data using Python.
Identify precincts with the highest numbers of recorded arrests.
Compare arrest counts across gender and demographic categories.
Examine the most frequently recorded offense categories.
Create visualizations to communicate patterns in arrest records.
Consider potential bias and limitations when interpreting arrest data.
## Tools & Technologies
* **Python** - data analysis and manipulation
* **Pandas** - data inspection, grouping, counting, sorting, and aggregation
* **NumPy** - numerical operations and pie chart calculations
* **Matplotlib** - data visualization
* **Seaborn** - statistical visualization
* **Jupyter Notebook** - interactive analysis and documentation
  
## Methodology
- Data Import: Loaded the 2023 NYPD arrest dataset from NYPD_Arrest_Data__Year_to_Date__20231225.csv using Pandas.
- Data Inspection: Examined the dataset's dimensions, column names, and sample records. The dataset contained 170,095 rows and 19 columns.
- Precinct Analysis: Grouped records by arrest precinct, counted arrest records, and sorted the results to identify precincts with the highest arrest counts.
Demographic Analysis: Grouped records by perpetrator sex to compare arrest counts across the available categories.
Offense Analysis: Grouped records by offense description to identify the most frequently recorded offense categories and select the five leading categories for comparison.
Data Visualization: Created a bar chart to compare arrests by gender and a pie chart to display the five most frequently recorded offense categories.
Bias Considerations: Considered potential bias and the limitations of arrest records when interpreting differences across demographic groups and geographic areas.
## Visualizations
Bar Chart (plot.bar()): Used to compare arrest counts by perpetrator sex.
Pie Chart (plt.pie()): Used to compare the five most frequently recorded offense categories, with labels, percentage annotations, record counts, and a title.
Grouped Data Summaries (groupby()): Used to aggregate and rank arrest records by precinct, sex, and offense description before visualizing the results.
These visualizations helped summarize arrest records and communicate patterns across demographic and offense categories.

## Key Findings
Dataset Size: The dataset contained 170,095 rows and 19 columns.
Precincts with the Highest Arrest Counts: Precinct 14 in Manhattan recorded 5,817 arrests, followed by Precinct 75 in Brooklyn with 5,469, Precinct 44 in the Bronx with 5,407, Precinct 40 in the Bronx with 5,392, and Precinct 103 in Queens with 4,582.
Combined Precinct Counts: These five precincts accounted for 26,667 records, approximately 15.67% of the dataset.
Arrests by Sex: The initial analysis reported approximately 80.8% male, 17% female, and 2% unidentified.
Most Frequent Offense Category: Assault 3 & Related Offenses had the highest count, with 25,200 records, followed by Petit Larceny with 18,025 and Felony Assault with 16,030.
Other Frequent Offenses: Dangerous Drugs accounted for 11,526 records, while Miscellaneous Penal Law accounted for 11,132.
The counts represent recorded arrest events in the analyzed dataset, not necessarily unique individuals. Arrest counts alone do not establish arrest rates or explain why differences occur across communities. Evaluating potential policing bias requires additional context, such as population data and other relevant measures.

Project Files
Dataset: NYPD_Arrest_Data__Year_to_Date__20231225.csv
Jupyter Notebook: ES Python Class Project 3 - NYPD Arrest Data.ipynb
Skills Demonstrated
Importing and inspecting public datasets
Data manipulation and aggregation with Pandas
Grouping, counting, and sorting records
Exploring demographic and geographic patterns
Creating bar charts and pie charts with Matplotlib
Summarizing categorical data
Considering potential bias and data limitations
Communicating findings through data-driven summaries

## Reflection
This project provided practical experience using Python to explore public-sector data and examine arrest patterns across precincts, demographic groups, and offense categories. It helped strengthen my understanding of data inspection, grouping, aggregation, and visualization while highlighting the importance of considering data limitations and potential bias when interpreting patterns in arrest records.
