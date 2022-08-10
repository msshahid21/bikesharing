# Bike Sharing
## Overview
The purpose of this project is to determine the viability of a biking service in Des Moines, by analyzing the Citi Bike Data from NYC. The following visualizations were constructed for analysis purposes:
- Checkout Times
- Bike Trips by Weekday/Hour
- Peak Hours
- Gender Breakdown
- Customers Breakdown

[Link to Dashboard](https://public.tableau.com/views/NYCCitiBikesFinal/NYCCitiBikes?:language=en-US&:display_count=n&:origin=viz_share_link)

## Results
### Checkout Times
Looking at the graphs for checkout times we can see that majority of the people using the Citi bikes use it for less than an hour, with most trips being around 6 minutes in length. The variation in the checkout times across genders does not vary much, with the most trips still being around 6 minutes.

<img src="https://github.com/msshahid21/bikesharing/blob/main/Images/Checkout%20Times.png" width=500></img> <img src="https://github.com/msshahid21/bikesharing/blob/main/Images/Checkout%20Times%20by%20Gender.png" width=500></img>


### Peak Hours
Most users of the bike service use the bikes before or after work, as the two modes are between 8 to 9 AM and 5 to 6 PM. Indicating that this is used primarily by customers to travel to and from work. This also explains why the checkout times for the bikes is mostly around 6 minutes in length.

![August Peak Hours](https://user-images.githubusercontent.com/67916327/183819564-af046034-317b-452e-b115-2eaf41dc73f7.png)

### Gender Breakdown and Heat Maps for Busy Periods
The visualizations below show the peak times on each weekday by the hour, and also further divided by Gender. Firstly, we can see from the pie chart that there are a lot more Male Users than Female Users, about three times as many.

![Gender Breakdown](https://user-images.githubusercontent.com/67916327/183820111-0a7eed2b-cbfb-4756-be57-debf44077b4c.png)

Furthermore, for both male and female users, the busy periods are still before and after work times on Monday to Friday, while on Saturday and Sunday the busy times are between 9 AM and 6 PM, perhaps due to people exploring the city during those days.

![Heat Map for Busy Times by Weekday and Hour](https://user-images.githubusercontent.com/67916327/183820428-1913243d-6f8f-4df5-b9ee-783e80c50d88.png)

![Heat Map for Busy Times by Weekday and Hour (Gender)](https://user-images.githubusercontent.com/67916327/183820434-b44e46c8-0b93-4e5c-a7cb-7b81e2f36d33.png)

Finally, on Thursdays it seems to be the busiest day for the Citi Bike service, as shown in the graph below.

![Heat Map by Customer Type for Peak Weekdays and Hours](https://user-images.githubusercontent.com/67916327/183820265-d95fbd2a-fadf-4a23-9601-3619e2cf7d46.png)


## Summary
The visualizations above show that the bikes service is mostly used by customers for going to and from work, while on the weekends it is used to explore the city. Additionally, the checkout times show that this is a very short term service for customers with a mode of 6 minutes. Therefore the service implemented in Des Moines should focus on targeting the same audience and set the pricing in a way where there is a higher initial fee with every extra minute being lower. This can encourage customers to use the bike longer but also capture a large enough payment for the smaller trips.

However, a key thing to note is the geographical differences between these two cities, NYC is a much larger and busier city, while Des Moines is much smaller in population. Furthermore, due to cars not being as accessible in NYC due to accommodating for pedestrians, cycling is a much better alternative than driving to work. These considerations will be important before taking all the above data at face value.

### Additional Charts
- **Checkout Times by day**: In order to see how much users of the service use the bike on weekends for touring the city this could be a useful visualization to determine if it is a good idea to have a different pricing system on weekends to encourage customers to explore the city.
- **Car Travel Times in Des Moines**: This chart could be used to determine if introducing a biking solution would be useful for the people of Des Moines, as it would provide a better alternative for getting to work if the average travel times by car are very long, due to traffic. To create this chart we could create a line chart with distance on the x-axis and time to travel on the y-axis.
