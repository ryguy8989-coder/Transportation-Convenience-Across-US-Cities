# BA780

# Transportation Convenience Across U.S. Cities

**Contributors:** Ryan Jiang, Jingyu Zhang, Chenxi Wu, Tobey Fung 

## Overview

This project investigates the relationship between population growth and transportation convenience across 230 U.S. cities from 2020 to 2023. We developed a Transportation Convenience Score (0–100) combining walkability, public transit ridership per capita, and transit funding per capita to compare cities across different population tiers.

Our goal is to understand whether growing cities are becoming more convenient for residents who rely on walking and public transportation.

## Methodology

- **Data collection:** Integrated U.S. Census population estimates, Federal Transit Administration funding and ridership data, and walkability datasets.
- **Data cleaning:** Standardized geographic identifiers, handled missing values, and combined datasets into a city-year panel.
- **Scoring:** Normalized walkability, transit ridership per capita, and transit funding per capita using min-max scaling, assigning each component equal weight.
- **Analysis:** Used descriptive statistics, correlation analysis, regression plots, and visualizations to examine trends across population tiers and geographic regions.

## Key Findings

- **Population growth was not meaningfully associated with changes in transportation convenience.** The correlation was approximately 0.03.
- **Large cities generally had higher convenience scores**, with a median score of approximately 26, compared with around 23 for small and medium cities.
- **Walkability was strongly associated with transit usage per capita**, highlighting the relationship between urban design and public transportation use.
- **Transit ridership recovered between 2020 and 2023** across all population tiers, with large cities experiencing the strongest growth at approximately 58%.

## Tools & Technologies

- Python
- Pandas and NumPy
- GeoPandas
- Matplotlib and Seaborn
- Jupyter Notebook

## Repository Contents

- `A03_Transportation_Convenience_Across_US_cities.ipynb`: Notebook containing data preparation, analysis, and visualizations.

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Download the source datasets and configure the file paths referenced in the notebook.
4. Open the notebook in Jupyter Notebook or Google Colab and run the cells in order.

## Conclusion

Population growth alone does not explain changes in transportation convenience. Comparing cities across multiple indicators provides a more informative picture of car-free mobility and highlights the importance of walkability and public transit infrastructure.

