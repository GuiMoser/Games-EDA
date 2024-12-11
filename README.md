# Games EDA

## Project Description
This notebook performs exploratory data analysis on dataset about games with data up to 2016.

Using python and libraries like pandas, scipy, matplotlib and seaborn, to analyze and clean the data, separates data by year for a cleaner view and then plot graphs discovering things like which platforms are leading in sales, what the user profile is in each region, and what the most popular genres are.

At the end performs some statistical tests to get conclusions about the analysis.

## Objectives
- Perform exploratory data analysis.
- Separate data by year for a cleaner view.
- Plot graphs to discover trends and patterns.
- Perform statistical tests to get conclusions about the analysis.

## Tools and Libs used
- Python: Main language used for analysis.
- Pandas: Library for data manipulation and analysis.
- NumPy: Library for numerical operations.
- Matplotlib: Library for plotting graphs.
- Seaborn: Library for creating informative and attractive statistical graphics.
- Scipy: Library for statistical analysis.

## Methodology
#### EDA
- Import libraries.
- Load the dataframes.
#### Preprocessing
- Identify and treat missing values.
- Separate data by year.
#### Data Analysis
- Plot graphs to discover trends and patterns.
- Perform statistical tests to get conclusions about the analysis.

## Conclusions
After cleaning the data and adding the column for 'total_sales', we analyzed the dataframe and filtered only the data from the most relevant years for the analysis, from 2007 to 2016 (which would be the current year), with this data we can notice in the analysis that the platforms that had led in sales for years were now giving way to their respective successor platforms (such as the PS4 replacing the PS3, the XOne replacing the X360 and the WiiU replacing the Wii), and considering that they lead in sales in all regions, leads to an easy decision to focus games and campaigns on those platforms. Now about genres, Action is by far the genre with the most sales, making it the best to focus on regardless of region. Shooter and Sports are also great genres for campaigns in the NA and EU regions, while in the JP region, Role-Playing is the best bet.

## Learnings
- Data analysis: interpreting and extracting valuable insights from large volumes of data.
- Data cleaning: identifying and correcting missing, duplicate, and anomalous values.
- Creating graphics: using matplotlib and seaborn to visualize data in an intuitive and informative way.
- Data preprocessing: preparing data for analysis, including cleaning and treat the data.
- Use of libraries and tools: practical application of various libraries and tools from the Python ecosystem, such as Pandas, Numpy, Plotly, Matplotlib and Seaborn.
- Data visualization: Creating very detailed graphs and other types of visualizations to identify patterns and trends.
- Data-driven decision making: Using insights derived from data analysis to guide strategic decisions.