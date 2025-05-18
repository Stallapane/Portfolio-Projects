# Exploratory Data Analysis (EDA) of Global Cancer Incidence and Mortality Data

## Overview
This project performs an Exploratory Data Analysis (EDA) on global cancer incidence and mortality data. The goal of this analysis is to understand variations in cancer rates across countries and genders, identify significant disparities, and uncover insights into mortality trends and incidence-to-mortality relationships.

## Dataset
The dataset used in this analysis contains information about cancer incidence and mortality rates across different countries. The data includes the following key columns:

- **Country**: The name of the country.
- **Male Including NMSC Incidence Rate**: The incidence rate of cancer among males (including Non-Melanoma Skin Cancer).
- **Female Including NMSC Incidence Rate**: The incidence rate of cancer among females (including Non-Melanoma Skin Cancer).
- **Male Including NMSC Mortality Rate**: The mortality rate of cancer among males (including Non-Melanoma Skin Cancer).
- **Female Excluding NMSC Mortality Rate**: The mortality rate of cancer among females (excluding Non-Melanoma Skin Cancer).

## Objectives
The key objectives of this project are:

- To clean and preprocess the cancer data for accurate analysis.
- To explore differences in cancer incidence and mortality by gender and country.
- To visualize the relationship between incidence and mortality rates.
- To identify countries with notably high or low rates and explore potential contributing factors.
- To create visually compelling plots for communicating insights effectively.

## Tools and Libraries
This analysis utilizes the following libraries and tools:

- **Python**: The main programming language used for analysis.
- **Pandas**: For loading and manipulating the dataset.
- **Matplotlib**: For basic data visualizations.
- **Seaborn**: For statistical and enhanced visualizations.
- **Jupyter Notebooks**: For organizing and presenting the workflow interactively.

## Steps in the Analysis

### Data Loading
- The dataset is loaded into a Pandas DataFrame from a CSV file or image-extracted table.

### Data Cleaning
- Ensured correct data types and handled any inconsistencies in country names or missing values.
- Selected and renamed columns for clarity and consistency.

### Exploratory Data Analysis
- Analyzed gender-wise incidence and mortality patterns.
- Compared male vs. female incidence rates across countries.
- Plotted incidence vs. mortality scatterplots to investigate correlations.

### Data Visualization
- Bar plots were created to show comparative incidence rates across countries.
- Scatter plots were used to examine the relationship between incidence and mortality.
- Custom legend placements and aesthetic adjustments were implemented to enhance readability.

### Outlier Detection
- Identified countries with extremely high or low cancer metrics.
- Compared outlier rates with global averages and potential social or healthcare variables.

## Conclusions
- Cancer incidence and mortality vary significantly by gender and country.
- Some countries report high incidence but relatively lower mortality, potentially indicating better healthcare systems.
- A visible correlation exists between incidence and mortality, especially among male populations.
- Certain regions may require further investigation due to disproportionately high mortality rates.

## Sample Visualizations
- **Incidence by Gender**: A bar plot comparing male and female cancer incidence rates for each country.
- **Mortality vs. Incidence Scatter**: A scatterplot mapping male incidence against male mortality, color-coded by country.

## Future Work
This analysis can be extended to:

- Integrate additional variables such as healthcare access, GDP, or life expectancy.
- Apply clustering techniques to group countries with similar cancer profiles.
- Use predictive modeling to forecast cancer trends.
- Conduct regional analyses or focus on specific cancer types.

## Acknowledgements
The dataset used in this project was sourced from [insert data source here].  
Special thanks to the creators of the dataset and the maintainers of the Python libraries used in this analysis.

