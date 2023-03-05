# Ford GoBike
## by Alphonse Emmanuel Y Boudouin


## Dataset

 The Ford GoBike dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. In our dataset, we have features such as the start and the end sation name and id, the start time, the user type(if the user is a subscriber or a customer) , the gender and the birth year of the member, also information about the latitude and longitude of the start and end station id, bike id, the ride duration and the bike_share_for_all_trip feauture. These are the features in the dataset. My goal was to see the relationship between some of these features and also their impact on the duration.


## Summary of Findings

 During the exploratory of the datset, i found very interestings relationship between my features. I first did some univariate plots and fooound that thursday had the highest count of rides and weekend with the lowest. A lso , the ride mostly happened in the morning and the afternoon and as i saw , the key hours were 7-8-9 am and 4-5-6 pm. I also saw that number of subscribers is more than the customers one. For the start and end stations names, they were too much, so i only took the top 10 for each of them. I also found some outliers in the age features and that the distribution was skewed. Same for the duration features. In the Bivariate part, i saw that customers duration is higher thab subscribers one, found that in the top10 destinations, Embarcadero at Sansome St had the highest duration and San Francisco Caltrain Station 2 with the lowest duration. Most users age is between 30-40, and also a negative correlation between duration in sec and the age. But with the duration in min(in which i took out some outliers), age had a positve correlation. Also customers rides mostly start on monday and mostly in the Afternoon, But for subscribers, it was more during the weekday than the weekend and in the morning. Finally in multivariate part, i saw that customers ride duration is high on sunday , low on wednesday.  For subscribers, it was high on saturday and thursday, low on monday. Both user type duration is high during the afternoon and low in the night. And from 6am, the duration increased. In top 10 start stations for males and females, sunday had the lowest duration , thursday with the highest one. In top 10 destinations for both subscribers and customes, afternoon had the hight count , then morning and night 


## Key Insights for Presentation
  For the presentation, i will show plots about the duration of rides and the relationship with other features. I will also show a plot about the top10 destinations. These informations are the mostbrelevant ones .
