# Impact of Covid-19 on Crime Rates in NYC and SF

This project aims to analyze the relationship between the Covid-19 pandemic and crime rates in New York City and San Francisco. We will review the disease case rates reported during and after the pandemic across different cities and analyze the percentage of crime reported in each of the cities before and during the critical wave of Covid-19.

## Contributors

- Adit Doshi (ad8343@rit.edu)
- Addl Tariq (at1816@rit.edu)

## Project Overview

- The project’s main goal is to identify if Covid-19 pandemic has a direct impact on the crime rate in major cities.
- The COVID-19 pandemic has led to a dramatic loss of human life worldwide and presents an unprecedented challenge to public health, food systems, and the world of work.
- During the pandemic, individuals were subjected to limitations such as school and company closures, social gathering bans, and so on. Individuals were only allowed to travel for vital tasks or requirements under the stay-at-home orders (SAHOs).
- Mobility restrictions were effective in reducing the spread of the coronavirus, but unemployment and financial suffering reached new highs as a result of the pandemic and social distancing measures.

## Methodology

1. Data Source Identification and Selection: Selection of the cities' police department datasets for New York City and San Francisco in the Google Marketplace and Covid-19 public datasets identification selection.
2. Data Extraction: Standard SQL queries development to extract the information, embedding of SQL queries in python wrapper using big-query python library, execution of queries, and storage in the form of data frames using the python pandas library.
3. Data Pre-processing: Cleaning the datasets using python numpy, math, and pandas library to remove null, missing, and discrepancy values, analyzing and dropping missing and duplicated rows.
4. Feature Engineering Selection: Importance of existing columns in relation to the existing datasets will be statistically analyzed, and new features will be derived to identify the relation and hypothesis testing.
5. Exploratory Data Analysis: This analytic exercise will enable us to identify the relationships between Covid-19 cases, crimes, and solution over the data times (pre, during, and post-analysis) keeping in view of the pandemic waves in each city.
6. Data Set Finalization Loading: New data tables in the form of data frames will be formed from the feature selection. This will be done using the python library, and new data tables will be loaded in Big-Query using Python and SQL commands.
7. Data Visualization: New data layer 2 will be integrated with Tableau or Data Studio to visualize and study the important results for the associated data, and dashboards will be created using the charts to build up a story of the impact of Covid-19 on crimes rates in New York City and San Francisco.

## Meta Analysis
Cleaning the data is one of the hard task as the dataset has more than 700k entries with 15+ columns, and MANY values of the dataset are NULL.
Identification of the right relationships will be difficult as a high number of columns usually leads to inaccurate and imprecise research focus.
Displaying the result using charts will be relatively easy, as finding the crime rate can be done by aggregating the crime rate during the mentioned time frame.



## Conclusion

Understanding the pandemic’s impact on violence is important for public health and criminal justice decision-making to reduce the number of deaths and injuries due to violent crimes. By analyzing the data from New York City and San Francisco, we hope to gain insight into how the Covid-19 pandemic has affected crime rates in major cities.

## References

The project references articles from scholarly sources and statistical reports. The team utilized the following articles for research and analysis:

Unemployment rises in 2020, as the country battles the COVID-19 pandemic: Monthly Labor Review: U.S. Bureau of Labor Statistics.
COVID and Crime: An Early Empirical Look
The Impact of COVID-19 on Gun Violence Across Census Tracts in NYC
Global crime trends during COVID-19
COVID and Crime: Analysis of crime dynamics amidst social distancing protocols
Pandemic Restrictions and Spatiotemporal Crime Patterns in New York, São Paulo, and Stockholm
For more information, please refer to the project report in this repository
