# Global Analysis of Life Expectancy, Aging Populations, and Gender Equality
## Overview
This repository contains the Jupyter Notebook (PopulationDemographics.ipynb) detailing a global analysis of population demographics using data from the World Development Indicators (World Bank), the UN Human Development Reports (Gender Inequality Index), and the WHO/UNESCO Water Supply, Sanitation and Hygiene (WASH) reports.

The primary goal of this analysis is to explore potential correlations between various demographic, economic, and social indicators.

## Research Questions
The analysis focuses on answering the following questions for the year 2023:

1. **How does life expectancy correlate with sanitation?**

    Conclusion: Life Expectancy and Sanitation Coverage are highly correlated (r = 0.81).

2. **Are countries with rapidly aging populations experiencing slower economic growth?**

    Conclusion: There is no significant correlation between the Old Age Dependency Ratio and annual GDP Growth (r = -0.06).

3. **Is there a connection between the Gender Inequality Index and life expectancy disparity between men and women?**

    Conclusion: There is ** no strong correlation** between the Gender Inequality Index (GII) and the Life Expectancy Disparity between females and males (r = -0.17).

## Data Sources
The analysis utilizes three key public datasets:

1. **World Development Indicators (WDI)**: Provides metrics like GDP growth, life expectancy, and old-age dependency ratio.

2. **UN Human Development Reports (Gender Inequality Index)**: Provides the Gender Inequality Index (GII).

3. **WHO/UNESCO Water Supply, Sanitation and Hygiene (WASH)**: Provides data on "At least basic" sanitation coverage.

## Key Findings
The primary finding is the strong positive correlation (r = 0.81) between a country's basic sanitation coverage and its average life expectancy. This suggests that improvements in sanitation remain a significant factor in global public health and longevity.

## Limitations
Users of this analysis should be aware of the following limitations:
* **Data Timeliness**: The primary analysis focuses solely on data from the year 2023 to ensure direct comparability across variables. This excludes decades of historical data that could reveal long-term trends or causal relationships.
* **Missing Data Exclusions**: Many countries were necessarily excluded from the correlation analysis if they lacked data for both variables of interest, which may introduce bias.
* **Lack of Population Weighting**: The current analysis treats all countries equally regardless of population size. Future work could incorporate population weighting to better reflect global impacts.

## Author
**Vidya Balachander**

Email: vidyakbalachander@gmail.com

GitHub: [vidyabalachander](https://github.com/vidyabalachander)

LinkedIn: [vidya-balachander](https://www.linkedin.com/in/vidya-balachander/)
