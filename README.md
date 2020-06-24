# Cousera_Capstone Project Report
## "Battle of the Neighborhoods"
Repository for capstone project from coursera


## Introduction

Finding an appropriate place to start a restuarant is of ut-most importance, for several reasons. It is a large financial commitment, and if there is not sufficient customer base, one could quickly go out of business. A hard-working entrepreneur is seeking to open an high-end authentic indian restuarant and would like it to be in the Toronto area, Ontario, Canada. This client requests to find an area to place this restaurant wherein maximal profit could result. As this client is a skilled award-winning chef, the menu will likely be on the pricier side. Thus, the target market of relatively affluent customers should reside nearby. Ideally, the client would like to house this restuarant in an area where there is not substantial competition. However, existence of only a few indian restuarants in an area may mean that there are a considerable amount of customers and market share could possibly be taken away from them with the right strategy, as long as the area wherin has more affluent individuals. Perfoming data analysis will attempt to lock in a neighborhood or an area of possible interest to the client using these key parameters. The target audience to examine the following case study are entrepreneurs who also want to open a restaurant in the future or are looking to expand in other areas of the city or nationwide. Some entrepreneurs seek only the most perfect spot, but in reality, many factors ought to be considered that may optimize the search but may never result in a completely perfect location.




## Data 

Several groups of data will need to be utilized for this study. The Foursquare database will need to be utilized to find the density of indian restuarants, as well as location and neighborhood data. Foursquare API calls will be conducted to find locations of existing indian restuarants, while location data will be obtained from an csv file originating from the Geocoder Python package. Toronto's Census data will be used to compile average income per neighborhood to meaningfully compare with current competition assessments. This data can be found at the City of Toronto's Open Data Portal. Lastly, neighborhood data will be collected from the Wikipedia page, "List of postal codes of Canada: M". A K-means clustering algorithm will be applied to group areas in accordance to the quantity of indian restuarants interplayed with the income of residents in those respective neighborhoods.


## Methodology 
Once fully understanding the problem, one then had to develop an analytical approach. To solve the problem at hand, K-means clustering algorithms were used for this task after careful consideration. This algorithm was used to create three distinct clusters in the Toronto area, accounting for income, population, and density of indian restuarants. The data was to be converted to integer format so that statistical analysis could be conducted on it. It was important for data to be collected from free online websites to reduce costs. When retrieving information from Wikipedia and from the City of Toronto, it was crucial to organize the data into dataframes in a proper way. At various intervals, the data was frequently checked for discrepancies and N/A points. After some confidence developed in this regard, the model was created. 


## Results 
(discuss the results)
inexact science
It was found that 

## Discussion 
(discuss any observations you noted and any recommendations you can make based on the results.)

## Conclusion 
(conclude the report.)

