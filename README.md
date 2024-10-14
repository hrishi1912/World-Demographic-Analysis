**Global Trends in Life Expectancy, Fertility Rate, and Population (1960-2017)**

This project explores the relationship between life expectancy, fertility rates, and country populations across different regions of the world from 1960 to 2017. The analysis uses datasets from various global sources, and visualizes demographic trends over time through interactive, animated visualizations.

__Project Overview:__ 

__Data Cleaning and Preprocessing:__
- Life Expectancy, Fertility Rates, and Population Datasets: Unnecessary columns are removed, missing data is filled using the mean for each year, and data is cleaned of unclassified country entries.
- Country Metadata: Additional country-level information, such as region and income group, is merged to provide more context.

__Data Transformation:__
- Datasets are reshaped to facilitate merging and analysis. This transformation helps in observing changes in the variables over time.

__Data Merging__
- The cleaned datasets (life expectancy, fertility, and population) are merged into a single dataframe, linked by country and year.
- Metadata about each country is also incorporated to add regional and income-level context.

__Visualization:__

- __A Plotly Express animated scatter plot is created, where:__
  - The x-axis represents the fertility rate (log scale).
  - The y-axis represents life expectancy.
  - The size of each point represents the population of the country.
  - The color indicates the region.
  - The animation plays through the years (1960-2017), visualizing how fertility and life expectancy have evolved globally.

- __Key Insights:__

  - Explored the relationship between fertility rates and life expectancy over time.
  - Identified regional trends and patterns.
  - Analyzed the impact of population growth on these demographic indicators.

__Tools Used:__
- Python: For Data cleaning, Transformation, and Analysis.
- Pandas: For Data manipulation.
- Plotly Express: For creating interactive, animated visualizations.
- Jupyter Notebook: For coding and documenting the process.

__Conclusion:__

 This project provides a comprehensive look at global demographic changes over several decades, revealing key insights into how healthcare, socio-economic factors, and population trends have shaped life expectancy and fertility rates worldwide.

