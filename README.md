# Housing Price Analysis in Brazil

## Overview

This project analyzes housing prices in Brazil using data science techniques. It explores various factors influencing property prices and provides insights into the Brazilian real estate market. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization of key trends.

## Features

- **Data Cleaning**: Handles missing values, outliers, and data inconsistencies.
- **Exploratory Data Analysis**: Investigates relationships between different features and housing prices.
- **Visualization**: Creates informative plots and charts to illustrate findings.
- **Statistical Analysis**: Performs statistical tests to validate observations.

## Project Structure

The project consists of two main Jupyter notebooks:

- **housing_in_brasil.ipynb**: Contains the primary analysis, including data cleaning and initial exploration.
- **eda.ipynb**: Focuses on in-depth exploratory data analysis and visualization.


## Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn

## Setup and Execution

1. Clone the repository   
2. Install dependencies:3. 
3. Launch Jupyter Notebook
4. Open and run the notebooks `housing_in_brasil.ipynb` and `eda.ipynb`.

## Key Insights

- The dataset contains 21,826 properties across Brazil.
- Most properties are located in São Paulo, Rio de Janeiro, and Belo Horizonte.
- Property prices range from 80,000 to 4,000,000 reais, with a median of 540,000 reais.
- There's a strong positive correlation between price and area, rooms, and bathrooms.
- Location significantly impacts property prices, with variations across cities and neighborhoods.

## Visualizations

The project includes various visualizations:

- Histograms of price and area distributions
- Scatter plots showing relationships between variables
- Heatmaps of correlations between features
- Box plots comparing prices across different cities
- Geographic plots of price variations

## Data Cleaning and Preprocessing

- Removed duplicate entries and properties with unrealistic values (e.g., 0 bedrooms or bathrooms).
- Handled missing values in the 'floor' column.
- Created new features like price per square meter and total rooms.

## Exploratory Data Analysis Highlights

- Analyzed price distributions and identified outliers.
- Explored relationships between price and various features (area, rooms, bathrooms, etc.).
- Investigated price variations across different cities and property types.
- Examined the impact of amenities (e.g., elevator, furniture) on property prices.

## Future Enhancements

- Implement machine learning models for price prediction.
- Incorporate more recent data for up-to-date analysis.
- Expand the analysis to include economic indicators and their impact on housing prices.
- Develop an interactive dashboard for easy exploration of the data.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



## Acknowledgments

- Brazilian real estate data providers
- Contributors to the Python data science ecosystem
