
# 2023 MSEP WQ Monitoring Station Survey  

In July of 2023, the then-developing Mississippi Sound Estuary Program sent out a survey to determine where its stakeholders wanted new monitoring stations to be located. This survey used ArcGIS Survey123 and allowed respondents to place a point on the map representing the location of a desired station. Additional fields allowed respondents to identify which parameters they would like to see monitored at the location and why.  

There were actually 4 separate surveys, where a single location could be identified in each. Survey 1 was for the respondent's top priority station; survey 2 was for the next most important station, and so on.  

I (Kim) have compiled the data from the separate output files into a single csv, removed details about the response or respondent, and added a column for "priority" - where 1 represents survey 1, the highest priority station, and so on. Then I put the stations on a map, colored by priority. Only the compiled, anonymized results have been checked into version control and made available in this repository.   

There were 9 responses to survey 1 (i.e. 9 stations defined as top priority); 6 to survey 2; 4 to survey 3; and 3 to survey 4.

The compiled file has the following columns:  

-  *Priority* - which survey/priority was the station in answer to  
-  *ObjectID* - which answer within the survey was the station  
-  *GlobalID* - a unique identifier assigned by ESRI  
-  *WQParams* - answer to the following question in the survey: "List up to six water quality parameters you would like collected at this location, and a short explanation (1-2 sentences) why you think it is an important."  
-  *OtherParams* - answer to the following question in the survey: "List up to four physical, hydrological, or any other relevant parameter you would like collected at this station, with a short explanation (1-2 sentences) why you think it is an important parameter in addition to water quality to include at this station."  
-  *x* - Longitude, decimal degrees  
-  *y* - Latitude, decimal degrees  