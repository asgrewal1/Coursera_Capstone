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
When examining the K-means algorithm results, it was clear there was a high concentration of indian restuarants in Scarborough, a city north-east of downtown Toronto. Very north of downtown Toronto has a small number of indian restuarants, but the income level is considerably lower. The downtown Toronto area had the second-most number of restuarants, but it is a heavily traveled area with a large population.  



## Discussion 
Just north of Toronto downtown seemed like a good candidate, due to a small number of restuarants, but the income level is considerably lower in this area. It is suggested that the client NOT launch their restaurant in the Scarborough due to extremely high competition. Income levels in the selected ideal area are also higher in comparison with certain other areas, ensuring that the restuarant has visibility to its target customers. Because it is important to be near high levels of population in neighborhoods such as Wellesley, Dundas, and College but somewhat distant from clusters of indian restuarants, it is suggested that the client choose Rosedale-Moore Park or Yonge-St.Clair as the ideal location for their restuarant. 

## Conclusion 
Several factors were not taken into account, such as the leasing of the land was not taken into account. This may impact the selection of the restuarant location. Due to limited amount of time to work on this project, many factors were ignored that may very well play an integral factor in restaurant selection. Such factors include parking, crime rates, affordability, and accessibility, to name a few. 
