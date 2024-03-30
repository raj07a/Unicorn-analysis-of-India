# Unicorn-analysis-of-India
This project conducts an analysis of startup data retrieved from a CSV file named "dataset.csv". The dataset is loaded into a Pandas DataFrame and examined to gain insights into various aspects of the startup landscape.

Project Steps:

Data Loading: The dataset is loaded into a Pandas DataFrame named df.

Data Exploration:

The first few rows of the DataFrame are displayed using df.head() to understand its structure.
Information about the DataFrame is obtained using df.info() to check for data types and missing values.
Missing values are identified using df.isnull().sum() and duplicated rows are checked using df.duplicated().
Sector Analysis:

The number of startups in each sector is counted using value_counts() on the 'Sector' column.
The top 10 sectors with the highest number of startups are identified and visualized using a bar plot.
Valuation Analysis:

The DataFrame is sorted based on the valuation in descending order, and the top 5 unicorns with the highest valuation are selected.
These top 5 unicorns are visualized using a bar plot to compare their valuations.
Yearly Analysis:

The 'Entry' column is converted to datetime format, extracting the year, and stored in a new column named 'Year'.
The number of unicorns started each year is counted and visualized using a bar plot.
Libraries Used:

Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Seaborn: For data visualization.
Matplotlib: For creating plots and visualizations.
Plotly Express: For interactive visualizations (not utilized in this code snippet).
Requirements:

Python 3.x
Pandas
NumPy
Seaborn
Matplotlib
This project provides valuable insights into the startup ecosystem, including sector distribution, unicorn valuations, and yearly startup trends.
