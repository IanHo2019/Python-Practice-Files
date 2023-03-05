# Python Practice Files
This repository collects datasets for Python practice. The following will provide some basic information on each dataset.

I sincerely thank Professor [Kim J. Ruhl](https://kimjruhl.com/) for his Python lecture in 2021 Fall at University of Wisconsin-Madison.

## DateTime Package
### osk.csv
The file 'osk.csv' contains daily closing prices for OshKosh Corp. and the S&P 500.

### vix.csv
The file 'vix.csv' contains daily end-of-trading values of the [VIX](https://finance.yahoo.com/quote/\%5EVIX/?guccounter=1&guce_referrer=aHR0cHM6Ly9iYWRnZXJkYXRhLm9yZy8&guce_referrer_sig=AQAAAGtmhy0y0QfSQdCJf8Er-baVzd7DUCovLhp8nu_gguzBZvILAGo2EVFOpkkqez6pjrHXxDwd4FrQMFqzQUdJfUI1lBlVcqDqKKfY25q307CkLBz4vrx809bi7fgNe_2mJuTpQe7gsyDZmU7zl_-7jG4LCufuhHO1WYTlZYGp1Ex0), a measure of expected market volatility as implied by S&P 500 options. Business news like to refer to it as the "fear index". The idea is that expected volatility rises when people are worried about the future.

## Fuzzy Merging
### gb_salaries.csv & gb_stats.csv
These two data files are from the [pro football reference](https://www.pro-football-reference.com/teams/gnb/2020_roster.htm) on the Green Bay Packers' roster. They are "matched" on the player names, but there are some errors in those names.

## Indexing
### CPS_March_2016.csv
The data is from the [Current Population Survey](https://www.census.gov/programs-surveys/cps.html), which surveys about 60,000 households each month.

### two_digit_by_port.csv
The file 'two_digit_by_port.csv' contains U.S. the dollar value of imports by two-digit commodity code and port of entry for December 2013. The data were retrieved from the [Census trade API](https://www.census.gov/data/developers/data-sets/international-trade.html). For example, imports into port number 3703 (Green Bay, WI) of commodity 72 (Iron and Steel) where $9,208,917 in December 2013. You can learn more about port codes [here](https://www.census.gov/foreign-trade/schedules/d/distcode.html).

## Machine Learning
### iris.csv
The iris data set is one of the most famous data set and classifier example. It even has its own [Wikipedia](https://en.wikipedia.org/wiki/Iris_flower_data_set) page! An iris is a flower, made up of sepals and petals. There are three types of irises in the data set: Iris-setosa, Iris-versicolor, and Iris-virginica. We can see four characteristics: sepal length, sepal width, petal length, and petal width.

### winequality-red.csv
The data file records characteristics and quality rankings of Portuguese wine from the [Wine Quality Data Set](http://archive.ics.uci.edu/ml/datasets/Wine+Quality) from the UCI Machine Learning Repository.

### wi_mn_counties.csv
In this data file, the variables include
  * *GEOID*: geographical ID.
  * *Description*: name of city and state (only WI and MN). 
  * *income*: in thousands of USD, for 2018.
  * *population*: number of persons, for 2018.
  * *ALAND*: area of the county in square meters.

## Matplotlib
### banking_data.csv
This dataset constains information on number of banks and banking offices in the US in 1934-2017.

### bea_gdp.csv
This file collects data on US annual GDP and its subcomponents from 1929 to 2019.

### VIXCLSD-1.csv
This dataset collects daily [VIX](https://en.wikipedia.org/wiki/VIX) index from 1990 Jan 2 to 2019 Oct 10.

## pandas
### banks_and_branches.csv
This dataset contains data on the number of commercial banking institutions, branches, and offices in the United States at the end of each year between 1934 and 2017. The data are from Table CB01, which is maintained by the Federal Deposit Insurance Corporation (FDIC). FDIC data can be downloaded from https://www.fdic.gov/open/datatools.html.

### GDPCA.csv
This dataset contains annual real GDP of the United States from 1929 to 2021, with some missing data.

### movies_merged.csv
This dataset was cleaned from the [MovieLens](https://grouplens.org/datasets/movielens/) "*ml-latest-small*" dataset, which was released by the GroupLens. It is meant to help build recommendation algorithms, like the ones you see in Netflix or Spotify. The GroupLens organization has other ratings datasets, too, on music, jokes, and books.

### airline_products_2017.csv
The data are taken from the Airline Origin & Destination Survey (DB1B) but has been substantially cleaned by Dennis McWeeny, a Senior Economist at Bates White Economic Consulting. The dataset contains information on a sample of airline itineraries for flights departing from one of seven airports in the San Francisco Bay region and arriving at one of the other large cities in the United States in the second quarter of 2017. Each observation contains information on the origin airport, destination airport, airline, nonstop or connecting itinerary type, average one-way fare in dollars, and distance between the origin and destination (in miles).

## Regressions
### sleep75.dta
This data set corresponds to Problem 3 in Chapter 3 of Wooldridge's *[Introductory Econometrics](https://www.cengage.com/c/introductory-econometrics-a-modern-approach-7e-wooldridge/9781337558860PF/)* (7th edition) and it's already cleaned. Professor [Kim J. Ruhl](https://kimjruhl.com/) contemplated adding some junk to the files to make it more interesting.

### wage1.dta
This data set corresponds to Problem C2 in Chapter 6 of Wooldridge's *Introductory Econometrics* (7th edition).

### pntsprd.dta
This file contains data about Vegas betting. The complete variable list is [here](http://fmwww.bc.edu/ec-p/data/wooldridge/pntsprd.des). For example, *favwin* is equal to 1 if the favored team won and zero otherwise, and *spread* holds the betting spread. In this context, a spread is the number of points that the favored team must beat the unfavored team by in order to be counted as a win by the favored team.

### apple.dta
The data dictionary for this file can be found [here](http://fmwww.bc.edu/ec-p/data/wooldridge/apple.des). The variable *ecolbs* is purchases of eco-friendly apples.

## Reshaping Dataset
### dogs.csv
In the dataset 'dogs.csv', there are different dimensions: variables (walks, snacks); dogs (Buster, Su); and time. The column 'value' are the data associated with the dog-variable-time triplet.

### WEOOct2019all.csv
The file 'WEOOct2019all.csv' is from the IMF's [World Economic Outlook](https://www.imf.org/external/pubs/ft/weo/2019/02/weodata/download.aspx), which contains historical data and the IMF's forecasts for many countries and variables.


## seaborn
### auto_data.dta
This file contains data on automobile characteristics in the European market. The unit of observation is a automobile model at a point in time. We can see prices and quantities sold and characteristics about the model.

## Wisconsin Maps
### 1000-largest-us-cities-by-population-with-geographic-coordinates
This is a dataset (in four different forms) with some information on Wisconsin cities. The data include the location of the cities and their populations. There are 20 Wisconsin cities that rank among the 1000 largest cities. We can use '1000-largest-us-cities-by-population-with-geographic-coordinates.shp' with geopandas in Python to plot maps for Wisconsin cities.

### result.csv
To plot voting patterns in the 2016 presidential election, I downloaded result data from [Wisconsin Elections Commission](https://elections.wi.gov/elections-voting/results/2016/fall-general). It is a mess. I saved a cleaned-up version of the file to 'results.csv'.
