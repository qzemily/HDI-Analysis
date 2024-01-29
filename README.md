# HDI Analysis

## Introduction

The analysis follows the six phases of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act. The goal is to identify correlations and insights between the Human Development Index (HDI) and the provided dataset.

## Ask

According to the UN, the HDI is a composite measure of a country's average achievements in three basic aspects of human development: Health, Knowledge, and Standard of living. The HDI sets goalposts for each dimension, with a higher value indicating higher human development.

[UN Human Development Index](https://hdr.undp.org/data-center/human-development-index#/indicies/HDI)

## Prepare

### Data Source

Data was obtained from Kaggle, specifically from the dataset titled "Wikipedia Country Statistics 2023." The dataset, sourced from various Wikipedia pages using BeautifulSoup, offers a consolidated and accessible resource for global country statistics.

[Dataset Link](https://www.kaggle.com/datasets/jiteshkumarsahoo/wikipedia-country-statistics-2023)

### Key Columns and Metrics

- **Country**: The name of the country.
- **Total in km2**: Total area of the country.
- **Land in km2**: Land area excluding water bodies.
- **Water in km2**: Area covered by water bodies.
- **Water %**: Percentage of the total area covered by water.
- **HDI**: Human Development Index.
- **%HDI Growth**: Percentage growth in HDI.
- **IMF/World Bank/UN Forecast GDP(Nominal/PPP)**: Economic indicators.
- **Internet Users**: Number of internet users.
- **Population 2022/2023/Population %Change**: Population metrics.
- **UN Continental Region/UN Statistical Subregion**: Geographic classifications.

### Limitations

Some countries have missing data.

## Process

1. **Examine the Data**: Initial exploration of the dataset.
2. **Fix 'Water in km2' Column**: Addressing issues in the water area column.
3. **Add Population Density Column**: Calculating population density.
4. **Add HDI Difference Column**: Calculating the difference between the highest HDI and each country's HDI.
5. **Explore Missing Values**: Imputing the mean for missing values.

## Analyze

The detailed analysis is provided in the code within the 'World_Stats.ipynb' file under the 'Analysis' tab.

## Share

[Tableau Visualization](https://public.tableau.com/app/profile/emily.quiroz/viz/HumanDevelopmentIndexInteractiveDashboard/Dashboard4)

## Act

The analysis provides valuable insights into global HDI variations. Notable observations include regional disparities, with Europe having the highest HDI and Africa facing significant challenges. Actions include developing targeted initiatives for Africa, focusing on healthcare, education, and economic opportunities. Continuous monitoring is recommended to assess the impact of interventions.

Additionally, the analysis highlights disparities in internet usage, especially in lower-HDI regions. Proposed actions include digital inclusion initiatives, knowledge and skills development programs, and collaboration with the private sector to invest in digital infrastructure.
