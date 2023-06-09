# PyBer_Analysis


# Overview of the analysis:

The purpose of our analysis is to create a summary dataframe that will show ride sharing data by city type(Rural,Urban & Suburban). Once we find our data we are going to create a multiple line graph that shows total weekly fares by each city type. How we first pulled our data is by using the pandas Groupby() function with the count() and sum () to get the total number of drivers,rides and fares by city type. Once we pulled this information and assigned it to functions we were able to calculate our average fare per ride and driver. Once we had all of that information together we were able to format into a newdata frame and re-format the columns. In the second part of this excercise we used the pivot() and resample function to create a multiple line graph that shows the total fares for each week by city type between the months of January & April of 2019. 

# Results by city type:

#Quick facts by city type, seen in the image below our facts
- Rural cities has the least amount of drivers, rides and total fares.
- Urban cities have the most amount of drivers, rides and total fares.
- Suburban cities are in the middle having the 2nd most drivers, rides and total fares.
- Although Rural cities see the least amount of drivers,rides & fares the have the highest average of fare per ride and fare per driver.
- Although the Urban cities command the most drivers, rides and fares they have the lowest average of fare per ride and fare per driver.

<img width="629" alt="Screen Shot 2020-08-22 at 11 50 22 AM" src="https://user-images.githubusercontent.com/67278193/90960275-8c52e600-e46e-11ea-97c9-5b139e98ebe8.png">

## Total Fare by city type chart between January & April of 2019

<img width="634" alt="Screen Shot 2020-08-22 at 11 51 54 AM" src="https://user-images.githubusercontent.com/67278193/90960279-8f4dd680-e46e-11ea-8e04-f0205ba6c66d.png">

Summary

From our data we are able to tell what kind of fares will be commanded based on what city type the passenger is catching a ride in. Although we didn't explore every individual city we still have a great grasp on what fares will look like from week to week based on city type which is enough information decide on rates that will need to be charged after we can classify what type of city the consumer lives in. In conclusion we can effectively say that a rural area will command a higher fare because there are fewer workers that will come to this area, the travel time and distance is most likely longer making the average fare per ride & driver the most out of all city types.

# Recommendations 

1. Have your drivers assigned to different city types based off of what type of cities they typically work in.
2. Charge more per mile in urban cities because trips most likely are shorter and drivers dont earn as much per trip.
3. Make small charge increases or descreases based off of how many riders there are in the city during certain months.

Thank you for reading.
