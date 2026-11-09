# Transportation Convenience Across U.S. Cities (2020–2023)

**BA780 Final Project | Business Analytics**

**Contributors:** Ryan Jiang, Jingyu Zhang, Chenxi Wu, Tobey Fung

## 1. Business Problem

As U.S. cities grow, transportation infrastructure must adapt to meet the changing needs of residents. Population growth can increase demand for public transportation, walking infrastructure, and other accessible transportation options. However, a growing population does not necessarily mean that transportation systems are becoming more convenient or keeping pace with demand.

For city planners, transportation agencies, and policymakers, understanding this relationship is important when making decisions about infrastructure investment, public transit funding, and urban development.

**Our central business question:**

Are U.S. cities becoming more transportation-convenient as their populations grow, and how do transportation convenience levels differ across cities of different sizes?

To investigate this question, we developed a Transportation Convenience Score to evaluate and compare transportation accessibility across 230 U.S. cities from 2020 to 2023.

## 2. Project Objectives

This project aimed to:

- **Evaluate transportation convenience:** Develop a standardized metric to compare transportation accessibility across U.S. cities.
- **Measure the relationship with population growth:** Determine whether cities experiencing greater population growth also experience improvements in transportation convenience.
- **Compare cities by population size:** Identify differences in transportation convenience between small, medium, and large cities.
- **Identify important transportation factors:** Examine the relationship between walkability and public transit usage.
- **Evaluate post-pandemic recovery:** Analyze changes in public transit ridership between 2020 and 2023.

## 3. Data & Methodology

### Data Sources

We integrated data from three primary sources:

- **U.S. Census Bureau:** City-level population estimates.
- **Federal Transit Administration (FTA):** Public transportation ridership and funding data.
- **Walkability datasets:** Measures of pedestrian accessibility and walkable urban environments.

The combined dataset covers 230 U.S. cities over four years (2020–2023).

### Data Preparation

- Standardized geographic identifiers to ensure consistency across datasets.
- Addressed missing values and inconsistent observations.
- Calculated per-capita transportation metrics to account for differences in city population.
- Combined the datasets into a unified city-year panel for comparative analysis.

### Transportation Convenience Score

To create a consistent measure of transportation accessibility, we developed a composite score ranging from 0 to 100.

The score incorporates three equally weighted components:

1. **Walkability:** Measures how accessible destinations are by foot.
2. **Transit Ridership per Capita:** Captures public transportation usage relative to population.
3. **Transit Funding per Capita:** Measures public transportation investment relative to population.

Each component was normalized using min-max scaling and assigned an equal weight.

This approach allows us to compare transportation convenience across cities while accounting for differences in population size.

### Analytical Approach

We applied several analytical techniques:

- Descriptive statistics to compare transportation convenience across cities.
- Correlation analysis to examine relationships between population growth, walkability, and transit usage.
- Regression plots to explore patterns between population changes and transportation convenience.
- Trend analysis to evaluate public transit ridership recovery from 2020 to 2023.
- Comparative visualizations across population tiers and geographic regions.

## 4. Key Findings & Business Insights

### Finding 1: Population Growth Does Not Necessarily Improve Transportation Convenience

The correlation between population growth and changes in transportation convenience was approximately **0.03**, indicating almost no linear relationship.

**Business implication:** Population growth alone may not be a reliable indicator of transportation infrastructure improvements. City planners should evaluate whether infrastructure investment and transportation capacity are keeping pace with changing population needs rather than assuming that growth will naturally improve accessibility.

### Finding 2: Larger Cities Generally Have Higher Transportation Convenience Scores

Large cities had a median convenience score of approximately **26**, compared with approximately **23** for small and medium-sized cities.

**Business implication:** Larger cities generally offer advantages in transportation accessibility, potentially reflecting more established transit networks and walkable infrastructure. Smaller and medium-sized cities may benefit from examining infrastructure gaps as they plan for future growth.

### Finding 3: Walkability Is Strongly Associated with Public Transit Usage

Our analysis identified a strong relationship between walkability and transit ridership per capita.

**Business implication:** Transportation planning should consider walking infrastructure and public transit together. Improving pedestrian accessibility may complement public transit systems by making stations and destinations easier to reach.

### Finding 4: Public Transit Ridership Recovered Across All Population Tiers

Between 2020 and 2023, transit ridership increased across all population groups. Large cities experienced the strongest recovery, with ridership growing by approximately **58%**.

**Business implication:** Transportation agencies should account for changing ridership patterns when planning service capacity, allocating resources, and evaluating future transit investments.

## 5. Business Recommendations

Based on our findings, several considerations emerge for transportation planners and policymakers:

- **Prioritize infrastructure investment:** Evaluate whether transportation capacity and accessibility are keeping pace with population growth.
- **Integrate walking and public transit planning:** Consider pedestrian accessibility when designing and improving transit networks.
- **Tailor investment to city size:** Recognize that smaller and medium-sized cities may face different transportation accessibility challenges than larger metropolitan areas.
- **Use ridership trends to guide planning:** Monitor post-pandemic ridership recovery to inform service levels and future resource allocation.

These recommendations highlight the importance of using data-driven approaches to evaluate transportation systems and support more informed urban planning decisions.

## 6. Tools & Technologies

- **Python:** Data processing and analysis.
- **Pandas:** Data cleaning, manipulation, and integration.
- **NumPy:** Numerical calculations and statistical operations.
- **Data Visualization:** Exploratory analysis and communicating findings.

## 7. Project Takeaway

This project demonstrates how business analytics can be used to evaluate transportation accessibility, identify patterns across cities, and generate insights relevant to infrastructure planning and resource allocation.

Our findings suggest that population growth alone does not guarantee improvements in transportation convenience. Instead, walkability, transit investment, and public transportation usage provide important additional dimensions for understanding how accessible a city's transportation system is.

By combining multiple data sources into a standardized analytical framework, this project provides a foundation for comparing urban transportation systems and supporting data-informed planning decisions.
- GeoPandas
- Matplotlib and Seaborn
- Jupyter Notebook
- Google Colab

## Repository Contents

- `A03_Transportation_Convenience_Across_US_cities.ipynb`: Notebook containing data preparation, analysis, and visualizations.

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Download the source datasets and configure the file paths referenced in the notebook.
4. Open the notebook in Jupyter Notebook or Google Colab and run the cells in order.

## Conclusion

Population growth alone does not explain changes in transportation convenience. Comparing cities across multiple indicators provides a more informative picture of car-free mobility and highlights the importance of walkability and public transit infrastructure.

