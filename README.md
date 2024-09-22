# AirBnb NYC Project Visualized with Tableau

## Project/Goals
The aim of this project was to explore AirBnb NYC listings' data and using Tableau, create impactful visualizations, considering key points and trends. 

More specifically, we focused on better understanding the distribution of room types offered, comparing prices and the amount of beds offered, a distribution of prices (paying attention to outliers), analysing differences in neighbourhoods with respect to prices or average number of beds and finally the growth in the number of hosts in the userbase since Q2 or 2008.

## Process
### Step 1 - Importing
Importing the .xls datafile and examining all possible columns. We wanted to get a feel of what types of variables to expect. We also wanted to ensure each column/variable was the correct datatype (string, int, date etc...)

### Step 2 - General 'EDA'
Using the term EDA loosely here, we worked to just create many visualisations considering different types of variables and notice any trends. We did this to better understand our data. Throw it all at the wall and see what sticks...

### Step 3 - Dashboard and Key Points
We came down on 5 key points that our dashboard was to convey:

  * 1 - Room Type Distribution - What does the distribution of room types look like in NYC, which is the most popular?
  * 2 - Beds versus Prices - Do we notice a trend or relationship with the number of beds and average prices?
  * 3 - Distribution of Prices and any Outliers - How are prices distributed, are their any prominent outliers affecting the data? perhaps in a certain neighbourhood or across a single room type?
  * 4 - Neighbourhood versus Prices - Does the neighbourhood (location) affect the average price?
  * 5 - Growth In Number of Hosts - What has the growth in AirBnb Hosts looked like since Q2 or 2008 up to late 2015? We also included a small forecast (prediction) to extend and see.

Each of the 5 key points above we're actioned with their own visualization. In addition, we've allowed for filtering, allowing users to drilldown on details that matter to them most.

Our dashboard can be seen in the:

* 'TableauPresentationOption2AirbnbAmirmansourOliver.pdf' file.

Should you wish to download the interactive tableau workbook version, it can be seen in the:

* 'AirBnb - Dashboard_v2023.2-2.twbx' file.

## Results
As a whole, we noticed that:

  * Entire homes/appartments make up the majority of listings in the NYC Airbnb dataset, with differences across neighourhoods
  * Manhattan, as a neighbourhood has the highest average price with $198.5
  * Manhattan has the highest count of room types amongst all the neighourhoods, particulary a 64.04%, 33.24% and 2.73% split between entire home, private room and shared room, respectively.
  * Using a box blot, we saw that majority of prices sit in the range between 0 and $500 however, there are many outliers up to $5,000 and one particular outlier at $10,000.
  * There is a general increasing trend in the prices vs number of beds however, there are a few oddities where for instance, a 1 bed average price is $155.5 followed by a 12 bed with an average price of 187.5. We feel the 12 bed may be an anomoly/outlier
  * from Q2 of 2008 to 2015 there has been a steady increase in the number of hosts joining the platform, with a calculated forecast entailing a seeming further increase throughout 2016 but not without a dip in early 2016.

## Challenges 
Our main challenge was the want/need to create a density map of listings, using the zipcodes and neighbourhoods. For one reason or another, tableau wasnt able to register the zipcodes and create a map. It would have been nice to see a map representation/hot spot of listings.

It would have also been nice to have spent more time with the data, better understood it - maybe this would have had us revise our current dashboard visuals, or come up with new key points.

## Future Goals
We'd like that have been able to create a density map of NYC, plotting the different neighbourhoods by intensity, considering factors like price or abundances of listings.
