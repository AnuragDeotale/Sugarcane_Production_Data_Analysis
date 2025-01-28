# Sugarcane Production Analysis Project

This project analyzes global sugarcane production using data from various countries. It includes data cleaning, transformation, and visualization to derive insights about sugarcane production trends, acreage, yield, and regional comparisons.

---

## Features

- **Data Cleaning**: Handles missing values, removes invalid entries, and formats data for analysis.
- **Exploratory Data Analysis (EDA)**: 
  - Univariate and bivariate analyses of sugarcane production data.
  - Visualization of production trends by countries and continents.
- **Insights**: 
  - Countries with the highest production, acreage, and yield.
  - Correlations between yield, acreage, and production.
  - Regional comparisons (continents and countries).
- **Visualizations**: Bar plots, pie charts, scatter plots, and heatmaps to explore relationships in the data.

---

## Dataset

- **Dataset Name**: `List of Countries by Sugarcane Production.csv`
- **Fields Included**:
  - `Country`: Name of the country.
  - `Continent`: Continent where the country is located.
  - `Production(Tons)`: Total sugarcane production in tons.
  - `Production_per_Person(Kg)`: Production per capita in kilograms.
  - `Acreage(Hectare)`: Land area used for sugarcane cultivation (in hectares).
  - `Yield(Kg/Hectare)`: Yield per hectare of land.

---

## Tools and Libraries

- **Libraries Used**:
  - `pandas`: Data manipulation and cleaning.
  - `seaborn`: Advanced data visualization.
  - `matplotlib`: General plotting.
- **Jupyter Notebook**: For interactive data exploration.

---

## Analysis Workflow

1. **Data Loading**:
   - Read the dataset using `pandas`.
   - Preview data using `df.head()` and `df.shape`.

2. **Data Cleaning**:
   - Remove invalid characters and formats (e.g., commas in numeric fields).
   - Drop missing or null values and reset the index.
   - Rename columns for consistency.

3. **Data Transformation**:
   - Convert columns to appropriate data types (e.g., `float`, `int`).
   - Add computed fields, such as production percentage.

4. **Univariate Analysis**:
   - Distribution of production, acreage, and yield.
   - Count of countries per continent.

5. **Bivariate Analysis**:
   - Correlations between production, yield, and acreage.
   - Scatter plots for production vs. acreage and yield.

6. **Insights Derived**:
   - Top 10 sugarcane-producing countries.
   - Countries with the highest acreage and yield.
   - Production distribution across continents.

---

## Key Visualizations

- **Bar Charts**:
  - Countries with the highest sugarcane production.
  - Countries with the largest acreage.
  - Yield per hectare by country.

- **Pie Charts**:
  - Share of global sugarcane production by country.

- **Heatmaps**:
  - Correlation between production, yield, and acreage.

- **Scatter Plots**:
  - Relationship between acreage and production.
  - Relationship between yield and production.

---

## Sample Insights

1. **Top Producers**:
   - Brazil is the highest sugarcane producer globally, contributing ~40% of the total production.
   - India and China follow as the second and third largest producers.

2. **Acreage and Yield**:
   - Countries with large acreages do not always have high yields per hectare.
   - Yield is a critical factor influencing overall production efficiency.

3. **Regional Trends**:
   - Asia dominates global sugarcane production, followed by South America.
   - Africa has the highest number of sugarcane-producing countries but lower yields on average.

