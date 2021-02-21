# Coursera_Capstone
Capstone project for battle of the neighbourhoods

Introduction:
The Toronto Foursquare data set provides community preference data related to venues. One of the main questions asked for data science in geographic data is where to deploy
resources to make the most profit or return on investment (ROI).  By conducting this study, a data scientist is exploring the main methodologies that can be used for 
any business application to try and determine the best location for business opportunties.  

In this project I will attempt to find out where a coffee company, such as Starbucks, would want to explore new business opportunites in the city of Toronto based upon customer 
preference, population, and geographic location. There could be many other factors related to this decision such as demographics, customer traffic, and competition, but this
simplified model is a good starting point for this problem.

Data:
The data I will be using starts with the Foursquare data set but adds data form two new sources.  The first is a Kaggle data base that provides the Lattitude and Longitude of
existing Starbucks coffee shops.  The second is for the City of Toronto for the population estimate for each neighbourhood. In order to use this dta I need to join the data sets
through neighborhood names and postal codes. The final data set includes the neighborhoods where coffee shop of cafe are the 1st or 2nd most preferred venue, the population
estimate, and the nubmer of starbucks locations per resident of the community.

Neighborhood: A string or mutliple strings that were sorted using the Toronto Foursquare project.
Population: Census information provided as floating number values
Starbucksperperson: Population / locations per neighbourhood (new cacualted field as a floating point value)
1st Most Common Venue: A string containing standardized names.  Note that this data set includes coffee shop and cafe that I will use interchangeably.
2nd Most Common Venue: A string containing standardized names.  Note that this data set includes coffee shop and cafe that I will use interchangeably.

The file Starbuck_locations2 contains the store locations

The file torontostarbuck6 includes population data added to the neighbourhood data.

These files are shown in the Github Page as shared.

