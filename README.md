# Hackathon2
# Ski Resorts Around the Globe: A Data-Driven Analysis

This project explores data about ski resorts around the world. The goal is to analyze ski resorts' infrastructure, pricing, accessibility, and other features using Python.

## Key Features

- **Data Analysis**: 
  - Clean and transform data for accurate analysis.
  - Analyze slopes, lifts, and seasonal details.
  - Identify outliers and missing data.

- **Visualization**:
  - Create interactive maps and visual charts using Plotly and Matplotlib.
  - Compare ski resorts by country, region, and other attributes.

- **Insights**:
  - Explore relationships between pricing, slopes, and lift systems.
  - Understand the influence of geographical factors on ski resort accessibility.
  - Calculate efficiency metrics (e.g., price per km of slopes).

- **Accessibility**:
  - Find the nearest airport to ski resorts.
  - Analyze the impact of airport distance on resort pricing.

## Tools and Libraries

- **Python Libraries**:
  - `pandas` and `numpy` for data manipulation.
  - `matplotlib`, `seaborn`, and `plotly` for visualizations.
  - `geopy` for geographical analysis.
- **Other Tools**:
  - Google Colab for running the project.

## Dataset Overview

- Ski resort data includes:
  - Slope lengths (beginner, intermediate, and difficult).
  - Lift capacity and infrastructure details.
  - Pricing and seasonal information.
  - Geographical data for mapping.

- Additional datasets include:
  - Airports for accessibility analysis.

## Steps to Run

1. **Install Required Libraries**:
   ```bash
 - pip install folium geopy pandas numpy matplotlib seaborn plotly

2. **Upload and Unzip Data:**

 - Upload ski resort data files (resorts.csv, data_dictionary.csv).
 - Add airport data for further analysis.

3. **Run the Python Code:**

 - Use Google Colab or any Python IDE to execute the provided .py file.

4. **Explore Results:**

 - Interactive maps and charts.



## Key Insights

### Best Ski Regions
- Regions like **Auvergne-Rhône-Alpes** and **Tyrol** have long ski seasons and excellent infrastructure.
- Regions like **Wallis**, **Piedmont**, and **British Columbia** also perform well but rank slightly lower.

### Efficiency Analysis
- Some regions offer more slopes per euro spent, making them highly cost-effective.
- The presence of **gondola lifts** significantly increases the **lift capacity**, making resorts more efficient.

### Airport Proximity
- Resorts near airports are generally more accessible to tourists.
- However, unique remote locations like **Lapland** may still have high pricing due to exclusivity.

### Pricing Insights
- The most expensive ski resorts (based on ski pass prices) are located in **the USA**.
- The number of slopes and lifts does **not significantly influence the price** of a ski pass.


- Resorts with more **difficult slopes** tend to have higher prices (moderate correlation: 0.57).
- **Total slope length** and **beginner slopes** have little impact on price (weak correlations: 0.31 and 0.12).
- **Lift capacity** shows almost no correlation with price (0.15), even at high-performance resorts.
---


### Additional Features to Include
- Data on accommodation prices, equipment rentals, ratings, and customer reviews for a more comprehensive analysis.
- Integration of **real-time data** for dynamic pricing insights.
- Expansion of datasets to include information on weather and tourism statistics.
