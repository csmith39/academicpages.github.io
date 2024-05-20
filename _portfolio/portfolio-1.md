---
title: "Analysis of Socioeconomic Factors, Pollution, and Health Outcomes in Maryland"
excerpt: "Exploring the spatial relationships between socioeconomic status, pollution levels, and health outcomes in Maryland counties.<br/><img src='C:\Users\schmi\GES 486\csmith39.github.io\Heatmap2.png'>"
collection: portfolio
---

### Introduction

The project aimed to analyze the spatial relationships between socioeconomic factors, environmental pollution, and health outcomes in Maryland. This study is particularly significant as it sheds light on the environmental justice issues within the state, emphasizing the need for targeted public health interventions and policies. By utilizing various spatial analysis techniques, the project explored how median income, pollution levels (specifically PM2.5), and age-adjusted death rates are interrelated across different counties in Maryland.

### Data and Methods

The data for this project was sourced from multiple reliable databases:
- **Median Income Data**: Sourced from the American Community Survey (ACS) 5-Year Data (2009-2019).
- **Pollution Data**: PM2.5 levels were obtained from the Environmental Protection Agency (EPA) Air Quality System Data Mart.
- **Health Data**: Age-adjusted death rates were acquired from the Centers for Disease Control and Prevention (CDC) WONDER database.
- **Geographic Data**: County boundaries and geometries were sourced from the U.S. Census Bureau's TIGER/Line Shapefiles.

### Exploratory Data Analysis

The exploratory data analysis (EDA) revealed significant variation in median income, pollution levels, and death rates across Maryland counties. Moran's I for median income was significant, indicating spatial clustering of similar income levels. This initial analysis set the stage for more in-depth spatial statistical analyses to uncover the relationships between these variables.

### Correlation and Regression Analysis

The correlation analysis showed:
- A moderate negative correlation between median income and age-adjusted death rates (r = -0.45), suggesting that higher income is associated with lower mortality rates.
- PM2.5 levels were positively correlated with death rates (r = 0.36), indicating that higher pollution levels are associated with higher mortality rates.

Regression analysis confirmed these findings, with median income being a significant predictor of death rates (p < 0.05). The regression model helped quantify the impact of socioeconomic status and pollution on health outcomes, providing a more detailed understanding of these relationships.

### Spatial Analysis and Visualization

#### Thematic Maps

Thematic maps illustrated clear spatial patterns, showing lower-income counties in the eastern and western parts of Maryland experiencing higher pollution levels and death rates. These visualizations highlighted areas where public health interventions might be most needed.

#### Point Pattern Analysis

Point pattern analysis of pollution sources indicated clustering of pollution sources in certain areas, primarily around urban centers. Ripley's K-function suggested significant clustering at smaller spatial scales. This analysis was crucial in identifying hotspots of pollution, which are critical for directing environmental policies.

#### Heatmap

The heatmap below visualizes the density of pollution sources across Maryland, highlighting areas with higher pollution levels. This heatmap helps in visually identifying the areas most affected by pollution and provides a clear, intuitive representation of the data.

![Heatmap of Pollution Sources in Maryland]("C:\Users\schmi\GES 486\csmith39.github.io\heatmap2.png")

### Conclusion

This study highlights significant spatial relationships between socioeconomic factors, environmental pollution, and health outcomes in Maryland. Higher pollution levels and lower socioeconomic status are associated with higher mortality rates. These findings underscore the need for targeted public health interventions and policies addressing environmental justice. Policymakers should prioritize reducing pollution in high-risk areas and improving socioeconomic conditions to enhance public health outcomes.

### Reflection

The project successfully integrated various data sources and spatial analysis techniques to uncover important relationships between environmental and socioeconomic factors and public health. Future work could extend this analysis to other states or explore additional environmental variables. The use of advanced spatial analysis tools in R and visualization techniques provided a robust framework for this analysis, demonstrating the power of GIS in public health research.

Overall, this project has provided valuable insights into the interplay between income, pollution, and health, highlighting areas for policy intervention and further research.
