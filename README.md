#Infobeermatics

This project used several data sources:
* OpenBrewery API
* Google Places API
* Openweather API
* weatherData.csv

to observe average brewery ratings by state, brewery ratings by type (e.g. microbrewery, brewpub) and the count of the different types of breweries each state had.

Additionally we determined if there was a relationship between a brewery's rating on Google and the following independent factors and average temperature of the state.

We used python to pull data from the APIs and stored the data in pandas dataframes.  We then used those dataframes to create the necessary graphs and charts for our analysis.

The charts include:
* Average Brewery Rating by State
* Average Brewery Rating by Type
* Average State Brewery Rating vs. State Temperature °F             Regression
* Brewery Rating vs. City Temperature °F Regression
* Brewery Rating vs. State Temperature °F Regression
* Brewery Types by State