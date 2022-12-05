# Redlining in Norfolk, Now vs Then

## Data Sources

- The polygons for the redlined areas in Norfolk, VA were obtained as a GeoJSON file from [Mapping Inequality](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58).
- 2019 Income, Housing, and Demographic data are from the 2019 ACS 5-Year Estimates and were downloaded from the [U.S. Census](https://data.census.gov/).
- Census Tracts used in process were downloaded from [U.S. Census](https://www.census.gov/geographies/mapping-files/time-series/geo/cartographic-boundary.html).
  
## What is Redlining?

According to the Oxford English Dictionary, redlining means to

> "refuse (a loan or insurance) to someone because they live in an area deemed to be a poor financial risk"

The following is how Wikipedia defines redlining.

> "In the United States, redlining is a discriminatory practice in which services (financial and otherwise) are withheld from potential customers who reside in neighborhoods classified as "hazardous" to investment; these neighborhoods have significant numbers of racial and ethnic minorities, and low-income residents."

I personally like the Wikipedia version as it broadens the potential impact of redlining by using the term "services (financial and otherwise)" whereas the dictionary leads one to belive that only loans and insurances can be withheld from an area. While withholding home loans and home insurance was heavily practiced in the 1930s, 40s, and 50s by the Home Owners Loan Corporation (HOLC), it is important to note that redlining can happen with many other types of services.

## Why?

I wanted to create this map so that people could explore the redlined areas of Norfolk, VA as well as try to show how redlining has impacted those same areas some 80 years later.

## Process (Work in Progress)

- Download data
- Clean data
- Calculate %
- Calculate adjusted income [BLS Consumer Price Index (CPI) Calculator](https://data.bls.gov/cgi-bin/cpicalc.pl?cost1=1&year1=194001&year2=201901)
- Join census data to tracts
- join attributes by location
- export as GeoJSON
- Upload GeoJSON to Mapbox
- Create tileset
- Create style
- Create HTML files
