Packages needed to run pp_dashboard.ipynb: 
- plotly
- dash
- dash_bootstrap_components
- numpy
- pandas
- matplotlib

Datasets used are:
- [Country by Continent from World Population Review](https://worldpopulationreview.com/country-rankings/list-of-countries-by-continent)
- [Global Power Plant Database](https://datasets.wri.org/dataset/globalpowerplantdatabase)

Running the jupyter notebook will produce a link for a data dashboard coded with Dash and Plotly. Data allows for filtering by continent or globally, as well as graph specific options.

A merge was performed with the WPR dataset to perform analysis by continents as well as data cleaning due to discrepancies between country names. New features were also introduced with a renewable vs non-renewable energy source categorization.

The figures generated are a histogram, pie-chart, world map, and table of power plants. The features of the power plant database that were used are the primary fuel type, country, name, capacity (in MegaWatts).

This data dashboard is meant to serve as a simple introduction to the dataset, revealing basic information about the global distribution of power plants, as well as showcases the proportion of plants powered by renewable fuel sources, in line with [UN Development Goals 7, 9, 11 and 13](https://sdgs.un.org/goals).