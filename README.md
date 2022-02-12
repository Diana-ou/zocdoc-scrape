# Mapping Primary Care Providers on Zocdoc in NYC

This project scrapes and maps information on primary care providers in New York City to explore geographic disparities in access to the online medical scheduling platform Zocdoc. It was completed for the Fall 2021 class Data & Databases taught by Jonathan Thirkield at Columbia Journalism School.

Click [here](https://juliaingram.github.io/zocdoc-scrape) to navigate a map that aggregates the data by zip code. Clicking on a zip code will display a list of providers in that zip code, the number of upcoming available appointments and the soonest available appointment, as well as the number of providers who speak Spanish or Chinese. The [map](/map) directory contains the geo data and HTML to display the map.

The [notebooks-files](notebooks-files/) directory contains two jupyter notebooks, one with the code to scrape providers from the Zocdoc website within a 1-mile radius of a given zipcode, and another to transform that data into a geojson to be mapped with Mapbox GL JS. It also contains a csv database of zipcodes and the citywide data from the website as of December 10, 2021.

The map shows a high concentration of primary care providers and appointment availability in Manhattan, and a dearth of providers in Staten Island and The Bronx. In Queens, providers are clustered in Forest Hills.
