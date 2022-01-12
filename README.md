# bikesharing

## Overview
The purpose of this analysis was to convince investors that creating a bike-share program in Des Moines, Iowa is a good business proposal. One of the key stakeholders requested to see a bike trip analysis. To do this, the data was analyzed and visualized through Tableau using appropriate filters to help the data tell a story. Specifically, the length of time that bikes were check out were analyzed for all riders and further analyzed by the gender of the riders. Additionally, the length of the bike trips were analyzed for all rides based on their gender for each hour and each day of the week. Moreover, the number of bike trips for each user type and their gender were analyzed for each day of the week. In order to due this, we used the August 2019 ride data collected from New York City's CitiBike bike-share program. First, the CSV file holding the data was converted to a DataFrame with Python Pandas. Then it was imported into Tableau and filtered out accordingly to create the relevant visualizations. Finally, the visualizations were compiled into a Tableau story along with the _______ and the ____ _ visualizations to really show the investors how might it be pertinent and translate to the success rate to a bike sharing program in Des Moines.

## Results
The results can be analyzed in the visualizations below:

### Checkout Times for Users
![checkout_times_users](Resources/checkout_times_users.png)

Based on this visualization it appears that the most frequent duration of bikes checked out appear to be within 5-10 minutes, with the peak number of bikes reaching close to 150,000. This means that most riders who check out bikes usually only ride for around 5-10 minutes. There is a sharp decrease in bikes checkout out after this time frame, indicating that after aroun5-10 minutes, many of theese riders gradually begin to finish their ride and return the bikes.

### Checkout Times by Gender
![chceckout_times_gender](Resources/checkout_times_gender.png)

Similar to the previous visualization, it appears that the highest number of bikes checked out at the highest minute duration is around 5-10 minutes, with male bikers encompassing the majority of the checkout times. However all genders follow a similar pattern in the amount of the time that is spent checked out and riding, with the peak time somewhere around 5-10 minutes. Beforehand, there is a sharp increase and after the peak, there is a sharp decrease seen across all genders. There are very minimal to no riders regardless of gender who have bikes checked out past around 55 minutes.

### Trips by Weekday for Each Hour
![weekday_trips_each_hour](Resources/weekday_trips_each_hour.png)

This heatmap visualization is a great way to display the hot spots of when trips are at their highest or loewst points by weekday and per each hour. The darker the shade, the more trips that were active. Lighter shades indicate lower trip activity. From this heatmap we can see that during the weekdays, there appeared to be the highest amount of trip activity between the hours of 5PM-6PM, probably as a means for people to get home on their evening commute or perhaps a leisurely evening bike ride after work. The shades on Saturday and Sunday showed there was consistent ridership throughout the daytime hours. And as expected, the lowest amount of trip activity was during the late night and early morning hours, regardless of the day of the week.  

### Trips by Gender (Weekday per Hour)
![gender_weekday_trips_hour](Resources/gender_weekday_trips_hour.png)

Thi visualization is similar to the previous one except that the genders are split into their own heatmaps. However, we can still see that the pattern is the same. The weekdays experienced peak bike trips during the 5PM-6PM time range, the daytime hours of Saturdays and Sundays were active, and the nightime to early morning hours were the least active across all genders. It is noteworthy that the shades are much darker for the males heatmap, indicating that males are overall more avtice in ridership than females.

### User Trips by Gender by Weekday
![weekday_trips_gender](Resources/weekday_trips_gender.png)

Based on this visualization it appears that 

###
![mentorship](Resources/mentorship.png)

Based on this visualization it appears that 

###
![mentorship](Resources/mentorship.png)

Based on this visualization it appears that 

## Summary
