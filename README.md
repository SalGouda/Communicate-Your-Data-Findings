# communicate-your-data-findings
# (Ford GoBike System Data)
## by (Salma Gouda)


## Dataset

> This dataset contains information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
> After cleaning, there are 174,952 trips in the dataset with 13 columns:
 ('duration_sec', 'start_time', 'end_time', 'start_station_name', 'end_station_name', 'bike_id',
 'user_type', 'member_birth_year', 'member_gender', 'bike_share_for_all_trip', 'age', 'month',
 'duration_min'). 
> Some variables are numeric in nature, while others are categorical.


## Summary of Findings

EDA Summary

Univariate:
> most trips range from 8 to 12 mins.
> The number of  Subscribers (+14k) is way larger than the number of Customers (2k).
> The age distribution has a peak around 28 to 32 ages.
> There is a higher contribution of males than females in this dataset.
> Only a small portion of users actualley used the bike share system.
> San Francisco Caltrain Station 2 is the top 1 favorite destination.

Bivariate:
> There are higher contributions of the male gender because the user in this dataset are mostly males.
> The larger no. of trips and trip durations belong to people around 30 as most users in the dataset are around this age.
> The most frequent stations in the dataset has no obviuos relationship with trip durations.

Multivariate:
> The number of trips decreases as age increases, with a peak around the age of 30.
> Subscribers are more consistent than customers as they both get older.
> San Fransisco Ferry Building Station has the most frequent trips taken by all genders.

## Key Insights for Presentation

> For the presentation, I focused on plot visualizing the different relationships between trip duration, age, user type, and gender.

> As my EDA was quite polished, I only enlarged the figure size of my visualizations to make them ready for presentation.


Acknowledgments:
- Egypt fwd community and tutors for support and help in better understanding the project (https://nfpdiscussions.udacity.com/).
- stackoverflow community for answering all questions related to code and python (https://stackoverflow.com/)
- slack community especially session leads for their amazing effort in connect sessions.
- Udacity Data Analysis nanodegree program tutors for leading each step to the final project (https://www.udacity.com/).
- Python documentation (https://pandas.pydata.org/pandas-docs/stable/).
- Pandas documentation (https://docs.python.org/3/).
- dirkkadijk repository also added to better understanding of the structure of the project (https://github.com/dirkkadijk/Ford-GoBike-Data-Exploration-and-Communication-of-insights).
