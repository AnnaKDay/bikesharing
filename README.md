# bikesharing
bike share data with tableau visualizations

### Links
#### Challenge Viz
https://public.tableau.com/views/Citibike_Challenge_16556913340810/NYCCitibike?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

#### Module Viz
https://public.tableau.com/views/CitiBikeAnalysis_16546451822760/ModuleDashboard?:language=en-US&:display_count=n&:origin=viz_share_link

# Overview
- This analysis was completed in order to examine trends in the New York City bikesharing service to prepare for a business proposal to set up a similar service in Des Moines, Iowa.

# Results
![2022-06-19](https://user-images.githubusercontent.com/100614266/174518832-e6dd8c10-85a1-4bb8-9ecd-7eb3b1c00181.png)
The above visualization shows the length of trip duration (in minutes) for every bikeshare ride in August, 2019. Overwhelmingly, bike rides peak at 5 minutes, and most fall within 1-15 minutes. The longest bike ride caps at the hour mark. Beyond the second hour no more bike rides continue. 

![2022-06-19 (1)](https://user-images.githubusercontent.com/100614266/174518847-3c64b5bf-7e93-41c4-a6e5-a7f8368cd781.png)
This next visualization shows the length of trip duration (in minutes) filtered by gender. The majority of bike rides are taken by males.

![2022-06-19 (2)](https://user-images.githubusercontent.com/100614266/174518860-c4bd4692-28b6-40cb-9c6f-d96ed7941125.png)
This visualization is a heatmap of peak times and weekdays for all rides in August, 2019. During the workweek, morning peak times tend to be between 6AM-9AM, while evening peak times are between 5PM-7-PM. There is a slight decrease in rides on wednesday during normal evening peak times. Weekends see more rides from 9AM-7PM.

![2022-06-19 (3)](https://user-images.githubusercontent.com/100614266/174518865-47835527-f7d2-4fe6-96d5-b76d11e5652e.png)
The above visualization is the same heatmap of peak times and weekdays for all rides, separated by gender. The trend remains much the same as the previous visualization across both genders and the unknowns.

![2022-06-19 (4)](https://user-images.githubusercontent.com/100614266/174518874-f97d2376-280a-4ac0-a7ef-044dd7731609.png)
This final visualization shows the peak weekdays by user type and gender. Subscribers prefer Thursday and Friday, and use the bikeshare considerably less on weekends (in comparison), while it seems tat Customers tend to use the bikeshare more on the weekends than during the workweek.

![2022-06-19 (7)](https://user-images.githubusercontent.com/100614266/174518895-6c44191a-f0d3-404d-8372-3c375cdd82c0.png)
This additional dashboard visualization shows a snap shot of Gender Breakdown, User Type Breakdown, Peak Hours of All Rides in a Bar Chart, and the Avg. Trip Duration by Age. From this we see a condensed form of the previous visualizations to quickly see that Males are the majority of riders, and that Subscribers are the main user type. We can also see that peak hours follow the average work day distribution in America. As an extra, we also get to see the Average Trip Duration by Age. It seems that the elderly born in the the 1890's (this data needs to be checked for errors, but I am reporting results as dictated by the module) have the highest average trip duration. They are followed by those born in the late 1960's.

# Summary
In New York City, we can understand that the majority of users are men, and fall under the subscriber user type. Peak hours are in the mid-morning and the early evening. Based on this information, I would conclude that the majority of CitiBike users are NYC residents who have signed up for subscriptions due to the high frequency of use. They are most likely using bikesharing often during the week to travel to and from work. Considering that the weekend trends are inverted from the weekday trends, and that customers reflect this inversion, it is highly likely that customers are tourists and visitors who are using the bikeshare during the weekends. Thus, when planning for a bikesharing system in Des Moines, the relevant parties will need to consider that local, male workers will be their primary clientele. Second to that will be local, female workers. Tourists and visitors will make up a miniscule number of clients, in comparison. Furthermore, when considering tourists and visitors, Des Moines and NYC cannot be accurately compared. Also, while there are many parts and neighborhoods of Des Moines that are condenensed, there are some industrial areas that are less accesible, which will be important to the bike sharing route planning. 
- An additional visualization that I think would benefit this analysis would be showing ride count by gender and age (in a format similar to Checkout Times for Users). It is important to know which age demographic is more likely to use this service, and how to make it the most accessible for them. 
- A secondary visualization that could add to this analysis would also be a heatmap of Trips by Age (Weekday per Hour) to give another view of age demographics.
