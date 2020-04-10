# Covid-19 Data Visualization

In the notebooks provided in this repo, I'll explore both worldwide and US-centric datasets of the Covid-19 virus to try to visualize its spread. I'll use plotly and ipywidgets to create interactive maps and charts, and voila to publish the results in an interactive dashboard.

### Worldwide Data
Worldwide data is published daily on the [ECDC website](https://www.ecdc.europa.eu/en/geographical-distribution-2019-ncov-cases). I enriched the data for visualization purposes with [Wikipedia's ISO country codes](https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes) and [Statistics Time's breakdown of countries by region/continent](http://statisticstimes.com/geography/countries-by-continents.php)

### United States Data
United States  county and state-level data is updated daily on the [New York Times' github](https://github.com/nytimes/covid-19-data).


## Notebooks

### Walkthrough
The world_data_walkthrough.ipynb is a step-by-step explanation of how to get started with plotly, first generating static maps and then adding animations, and how to work with ipywidgets to add useful interactivity to explore the data further. I also cover two other chart formats, namely bar charts and scatter plots.

### Dashboard
The two dashboard notebooks, world_data_dashboard.ipynb and usa_data_dashboard.ipynb, only contain final versions of the charts developed in the walkthrough. They are meant to be directly published as dashboards using voila, and as such have a different logic when it comes to using ipywidgets interactions.


## More Information on Covid-19

* [ECDC](https://www.ecdc.europa.eu/en/covid-19-pandemic)
* [CDC](https://www.cdc.gov/coronavirus/2019-ncov/index.html)
* [Google Covid-19 Information](https://www.google.com/covid19/)
