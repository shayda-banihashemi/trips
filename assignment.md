# Trip
## Background
Your job is to build a database and application that helps people exploring 
the US to find intersting places to visit. 

The first version of this application will use the points of interest data
from Kaggle (see 
https://www.kaggle.com/datasets/ehallmar/points-of-interest-poi-database?resource=download
)

Build the database and application using test driven development that can run 
tests with fake data for the backend piece of this application. The tests 
should mock the actions a user will take (but without the UI).

The user should be able to search places on interest using meaningful searches.
The places should be saved in a user's trip file (one for each trip).

Then, for each / any trip, the user should be able to search for hotels near 
to the points of interest. Use the API at https://docs.hotelapi.co/free-hotel-api
and save the hotels with each point of interest on the trip.

## What to do
1. Design and build the database
1. Write tests for all the features
1. Populate the database with test data
1. Wire the app up to the genuine data sources and test

*Reemeber that this application will be extended over time.*