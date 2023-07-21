# Next-NYC-Trader-Joes
Finds the most suitable location for the next Trader Joe's in New York City

## Project Overview
To arrive at a conclusion, I evaluated every zip code area in New York City based on the land area, population, target audience, median household income, foot traffic, number of existing Trader Joe’s stores, and number of competitors’ stores. Once the necessary data was gathered, I designed a model that assigns weights to every metric and outputs a composite score, summing up the product of weights and values for every criterion.

## Data
I used data from the following sources:
- [x] U.S. Census Bureau ([American Community Survey: 5-year Esimates](https://api.census.gov/data/2021/acs/acs5/profile)) — for land area, population, target audience, median household income.
- [x] [LOJIC Open Data Portal](https://data.lojic.org/datasets/HUD::zip-code-population-weighted-centroids/about) — for ZIP code population-weighted centroids.
- [x] [Name Census](https://namecensus.com/zip-codes/new-york/city/new-york) — for all ZIP codes in NYC.
- [x] [NYC Open Data](https://www.nyc.gov/html/dot/downloads/pdf/bi-annual-ped-count-readme.pdf) — for Bi-Annual Pedestrian Counts.

I also used [U.S. Census Bureau](https://www.census.gov/data/developers/data-sets.html) and [OpenCage GeoCoding](https://opencagedata.com/tutorials/geocode-in-python) APIs.

## Model and Results
Please see the code and the write-up for more details.
