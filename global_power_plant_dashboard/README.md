
This interactive dashboard is designed to facilitate in-depth **data exploration and analysis**. It provides a dynamic environment for examining the Global Power Plant Database through a series of **intuitive** visualizations and **interactive** tools. 
Designed with user experience in mind, the dashboard integrates various data analytics tools and visual representations to offer deep insights into a large dataset. Each component of the dashboard is designed to present data intuitively and interactively, making it easier for users to inform themselves on **patterns in global energy production**.
Furthermore, information about **renewable energy** sources is added in accordance with the [UN Development Goals 7, 9, 11 and 13](https://sdgs.un.org/goals).

Among the interactive visualizations are:
- **Histograms** to explore distribution patterns and detect underlying trends.
- **Pie Charts** to analyze categorical data and understand proportions.
- **Interactive Maps** to visualize data geographically and uncover regional insights.
- **Data Tables** for detailed examination and exploration of raw data

Datasets used are:
- [Country by Continent from World Population Review](https://worldpopulationreview.com/country-rankings/list-of-countries-by-continent)
- [Global Power Plant Database](https://datasets.wri.org/dataset/globalpowerplantdatabase)

Running the jupyter notebook will produce a link for a data dashboard coded with Dash and Plotly. Data allows for filtering by continent or globally, as well as graph-specific options.

A merge was performed with the WPR dataset to perform continent-based analysis as well as data cleaning due to discrepancies between country names. A new feature was also introduced with a renewable vs non-renewable energy source categorization.

The features of the power plant database that were used are the primary fuel type, country, name and capacity (in MegaWatts). Due to data missing for >40% of records, for all remaining features, these were not used for analysis.

Once run, the dashboard looks like [this](dashboard_screenshot.png).
