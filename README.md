# Seattle Airbnb Analyis

## Overview

The present analysis was made to get an insight into the behaviour of the host and users in seattle using information about the corresponding listings, occupancy, and user reviews. I came up with four questions i wanted to answer in order to fullfill my analysis:

1) Using the features: summary, name, description, neighborhood_overview, and space: What are the words that are most useful in attracting people into the post and what are those that repel them? For this, i will use the number of nights a particular id has been available.

2) Inspecting the airbnb post the price, amenities, and host_verifications also appear. Are those features having an impact in the occupancy of a house? 

3) Using the user reviews, What are the most important words people used to describe their experiences? 

4) Using the location of each listing, what are the differences in the listing geographical distribution based on the occupancy?

## Libraries

The libraries needed to run this notebook are: pandas, numpy, matplotlib, seaborn, wordcloud, collections, PIL, and IPython

## Files

There are a number of files needed for this notebook:

1) calendar.csv: contains information of the listing_id, the date it was booked, if it was available or booked in a particualr day and the booking price.

2) listings.csv: contains all the information about the listing and the host, like the description of the listing,  the neighborhood, amenitities, prices, superhost, etc.

3) reviews.csv: contains information about the listing_id the date it was booked and the comments and id of the reviewer.

## Results

After the analysis i concluded that people want to feel like home when they book an airbnb, it is not always the number of amenitites or how many things the house have, the location or prices, although important, what people want is to feel comfortable and have services around for them to move and hang out. 

The fremont area is a very hot destination besides downtown which is overwhelmed by so much listings. 

It is very important to have a great name and description for your listing, so in the analysis, for the most important fields like name, summary, description, neighborhood overview and space, i showed a number of words you can use that were used by the most booked listings in Seattle.




