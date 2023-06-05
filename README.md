# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project was to become familiar with building statistical models in python.
Some database querying and modifications to dataframes were also required knowledge. The dsataset was a API and python generated dataframe to gain insights on bicycle stations in Paris

## Process
### (your step 1)
Step one was building the dataframe from json objects retrieved using python requests. A python request would return a dicitonary json object which was altered and converted to a dataframe.
### (your step 2)
The dataframe that was resulted was cleaned up on export from an sqlite database for fitting in a regression model. The model was done with a linear regression on the empty bike availability.
## Results
The yelp had much better results than the foursquare. City bikes was the easiest API to work with as it did not require an access token. Latitude is a better predictor than longitude for empty bikes in paris.

## Challenges 
My biggest challenge was building the regression model. i am familiar with the dat operations but the model building was something i havent done before throuroughly. 

## Future Goals
I would like to rebuild the most using the forward approach and improve accuracy. I would also try to get more data and re-categorize my columns as much as i can.
