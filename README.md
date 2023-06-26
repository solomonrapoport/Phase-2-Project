![300px-Map_of_Washington_highlighting_King_County svg](https://github.com/solomonrapoport/Phase-2-Project/assets/112587683/4bdcb90f-1fc6-4374-ac9e-e31b3a85b693)


# Phase 2 Project - Solutions to Maximize Real Estate in King County, Washington
Author: Solomon Rapoport

# Overview
This project analyzes real estate in King County, using data-driven solutions from a dataset of 30,155 homes to provide concrete business suggestions for a real estate development company in KC.

# Business Problem
Real estate developers in King County, Washington, might be able to gain better insight in regards to factors that might impact the price of a home, be those more obvious factors such as home location and size, or more subtle ones such as bathroom count or patio size, and use these insights to improve their sales and profit margins.

# Data
The King County dataset is comprised of a list of over 30,000 homes in King County purchased between 2021 and 2022, and includes information on each home such as year built (some homes as early as 1900, some as recent as 2022), location, price paid, and various other specifications (number of floors, bedrooms, and bathrooms, square footage, year last renovated, etc.).

# Methods
This project uses linear regression and data visualizations find trends among variables as well as over time, in order to identify and provide recommendations and solutions to real estate developers in King County.

# Results

-**There is a strong correlation between waterfront properties and price.** One model that was run showed that a waterfront home is correlated with an increase of $1,136,000 in value versus a home that is not waterfront! Compared  with the mean of the average home price in the dataset, the price of a waterfront home is about 1.755 standard deviations higher. In a normally distributed dataset, that would align with the top 5% of home prices.

-**Living space has a much bigger impact on home price than other property space.** One model showed that the coefficient for square foot living space was over three times as high as the coefficient for square foot space as a whole. This means that the each square foot of living space is correlated with a much higher increase in property value!
<img width="666" alt="Screen Shot 2023-06-21 at 3 02 32 PM" src="https://github.com/solomonrapoport/Phase-2-Project/assets/112587683/918c851e-ac90-41e6-b3a7-98fcf85bd162">

-**Analysis seems to indicate the clear impact a view (or more specifically, the lack thereof) has on the sale price of a home.**
The jump from no view to an average view alone comes with an average price difference of +$433,386, a massive %42.5 increase!
Homes with an “excellent” view are sold at an average of %200 more than homes with no view (nearly $2 million more!)
<img width="649" alt="Screen Shot 2023-06-21 at 4 44 01 PM" src="https://github.com/solomonrapoport/Phase-2-Project/assets/112587683/df8489bd-c7c3-48b7-88f3-1e42cbc7b8a4">

# Conclusions



This analysis leads to three recommendations for improving the business of our real estate debvelopment company in Kansas City:

1. **House with a view, any view:** Merely the presence of any sort of view is correlated with a massive price increase in average sale price compared with homes that have no view. Develop properties with favorable views (be it property  location, window placement, etc.

2. **Square feet of living space is paramount.** Our models showed that square feet of living space is correlated with a higher price per square foot than any other part of the property. So in development, skip the patios, big garage, large basement, etc.

3. **Waterfront properties are a gold mine.** The basic data, confirmed by one of the models produced, show that the average home price that is a ‘waterfront property’ is over $1.5 million more than homes with no waterfront! Prioritizing the development of waterfront properties could bump up sale price significantly.


# Next Steps

## What further types of data could we use to provide better business suggestions to our real estate development company?
-Development costs: Of course, it would be great for sale price to develop properties with waterfronts, nice views, and big living spaces, but what are the costs in King County of such properties/modifications? At what point do the costs outweigh the added revenue?

-Data which breaks down average property prices per neighborhood/town

-Other independent variables, which may or may not impact price, but would be interesting to take a look at, such as:

+ Exterior paint color/design

+ Presence of home amenities/luxuries (e.g. pool, gym, sports court)
  
+ Local crime rates
  
+ Distance from commercial hubs (e.g. Seattle)
  
+ Property taxes

# For More Information

See the full analysis in the Jupyter Notebook to review this presentation

For additional information, contact Solomon Rapoport at solomonrapoport@gmail.com
