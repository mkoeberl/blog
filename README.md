# blog
Exploring some Inside Airbnb data
The results from the analysis in the notebook in this repository can be found at [Medium](https://medium.com/@martin.koeberl/how-covid-19-makes-it-cheaper-and-easier-to-get-a-place-to-stay-in-vienna-fbff17cf70f6).

## Questions investigated
We were interested in answering the following questions:
- Is there a noticeable change in the booking situation as of Mid-February to as of Mid-March 2020? Does it seem to be different than in other months because of Covid-19?
- Is there a noticeable price difference between apartment prices as of mid-February ot as of mid-March 2020 because of Covid-19?
- What are the important factors in deciding whether somebody is a superhost or not?

## Data used
We used data on Vienna from [Inside Airbnb](http://insideairbnb.com/). Specifically, we looked at
- calendar data from 2019 and 2020 (those are monthly snapshots capturing the availability and the price for all listings for the following 365 days)
- the listings data from March 2020 (a dataset containing information on all listings in Vienna including the texts, some information about the host, the amenities etc.)

## Necessary packages
To run, you need Python 3.7 and the standard packages for data analysis in Python:
- pandas for handling tabular data
- numpy for handling numeric data and arrays
- sklearn for modelling
- matplotlib for plotting
- seaborn for plotting
- bs4 for getting the data
- requests for getting the data
- tqdm for progress bars

## Conclusions
For comments and remarks, see the notebook file, short summary:
- We see that the availability has gone up from February to March, possibly because of many cancellations due to travel restrictions and curfews in Austria and justified worries about Covid-19.
- We see that prices for bookings for end of March, beginning of April have gone down from February to April. While this is true for many pairs of consecutive months, the difference is bigger than in the other cases.
- The most important factors seem to have to do with the experience of the host and the quality of the listing, such as since when the host is a host, how many reviews they got and the ratings of the apartment.

## Files
- Airbnb_exploration.ipynb: Notebook exploring the three above questions
- README.md: this file

No data is provided in this repository but must be downloaded from Inside Airbnb. The notebook contains a cell doing that for you.