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
<div class='tableauPlaceholder' id='viz1706636041181' style='position: relative'><noscript><a href='#'><img alt='Human Development Index ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Hu&#47;HumanDevelopmentIndexInteractiveDashboard&#47;Dashboard4&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='HumanDevelopmentIndexInteractiveDashboard&#47;Dashboard4' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Hu&#47;HumanDevelopmentIndexInteractiveDashboard&#47;Dashboard4&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1706636041181');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} else { vizElement.style.width='100%';vizElement.style.height='1577px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
[Tableau Visualization](https://public.tableau.com/app/profile/emily.quiroz/viz/HumanDevelopmentIndexInteractiveDashboard/Dashboard4)

## Act

The analysis provides valuable insights into global HDI variations. Notable observations include regional disparities, with Europe having the highest HDI and Africa facing significant challenges. Actions include developing targeted initiatives for Africa, focusing on healthcare, education, and economic opportunities. Continuous monitoring is recommended to assess the impact of interventions.

Additionally, the analysis highlights disparities in internet usage, especially in lower-HDI regions. Proposed actions include digital inclusion initiatives, knowledge and skills development programs, and collaboration with the private sector to invest in digital infrastructure.
