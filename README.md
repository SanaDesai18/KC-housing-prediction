Predicting House Prices in King County
This multiple linear regression project was completed as part of Flatiron School's Data Science Bootcamp (Module 2 Final Project).

Problem statement
As a junior data scientist at real estate company PropertiesInc., I have been tasked with investigating house sales in the King County area and building a model to predict sale price. Key executives are keen to launch an advertising campaign directed towards home owners in that area who might consider selling their house, focusing on higher-end residential properties.

Before building the model, we will address the following descriptive questions through data exploration:

Which locations within the King County area have the highest average house prices?

Which house attributes increase sale price?

Does time of the year have an impact on house sales?

Components
Jupyter Notebook
The Jupyter Notebook is our key deliverable and contains details of our approach and methodology, data cleaning, exploratory data analysis and model building and validation. The key models have also been saved using Pickle.

I recommend using nbviewer to view the Jupyter Notebook.

Presentation
The presentation gives a high-level overview of our approach, findings and recommendations for non-technical stakeholders. It is aimed to be between 5 and 10 minutes long.

Data
The dataset can be found in the file "kc_house_data.csv" in the Data folder, in this repository. It was originally provided in the following repository.

Misc
We found a GEOJSON file with zip code borders, which was used as part of data exploration. It is included in the repository.


Q1 Location

Waterfront living is key, with the median house price for a house with a waterfront view being almost double that of one that does not have this feature.
We recommend focusing the campaign on the following neighbourhoods: Medina, Clyde Hill and Mercer Island (the most expensive neighbourhoods).
Location within King County is important with a noticeable disparity amongst zipcodes. The median house price ranges from $235,000 in 98002 up to $1,260,000 in 98039.
Median House Prices per Zipcode

Q2 House attributes

We recommend targetting the campaign towards houses with a higher bedroom count. However for a given house depending on its square-footage, note that adding an additional bedroom does not necessarily result in a a sale price increase.
There does not appear to be a clear relationship between the ratio sqft_living/sqft_lot and price. This indicates that there is unlikely to be an idea area to allocate to living space within a plot.
The median house price increases with grade indicating that these features are positively correlated. We suspect grade will be a good indicator of price.
For the campaign we would recommend looking at houses with a grade of 10 or above.
Median Price per Grade

Q3 Time of the year

House prices do not appear to be affected by sale month or quarter, with the median house price being almost constant throughout the year.
April and May are the most popular months for house sales. In contrast, January and February have the lowest number of sales Q2 alone accounts for 31.3% of house sales.
We would recommend launching the campaign in March/April, to gather interest with a view of completing the sale in Q2.
Number of sales per month


Contributors:
Name	GitHub
Sana Desai	https://github.com/SanaDesai
Contact
If you have any questions, you can contact me at sanandesai@gmail.com
