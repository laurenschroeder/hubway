# Hubway Infographic

Five large benefits of using Hubway are listed on the Hubway website (https://www.thehubway.com/how-it-works). 

These are fun, time, money, exercise, and environment. The benefits are described and are extremely valuable, but there really isn't any explicit examples, or 'proof'that the user will see these type of benefits.

I created an infographic based on these type of tangible benefits. Using data available through Hubway, I was able to understand about the quanitity and style of trips taken by different users. There's a lot of insight that can be gathered from this data, but I've outlined the five statistics I pulled below.

How I got my stats

# Have Fun

I calculated the number of 'fun' trips by comparing the number of trips that started at the same place they ended. I did this by filtering the dataframe based on entries with a calculated distance value equal to 0.

# Save Time

I got the average bike speed by taking the average speed of all trips. This was calculated by first calulating speed for all trips that ended in a different location than they started (dividing distance (miles) by time (hours). I then took this average value. It is unlikey that users were biking the endire time that the bike was checked out but when averaged across all users, this value is a reasonable estimate.

# Save Money
Average U.S. light duty vehicle fuel efficiency (mpg)
21.4 mpg
Bureau of Transportation Statistics
https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/national_transportation_statistics/html/table_04_23.html

Boston gas at https://ycharts.com/indicators/boston_retail_price_of_gasoline
$2.4/gallon per day

1.75 miles
6901.598 miles/21.4mpg*2.4=$/trip
subscriber trips: 137734   
total trips: 179731

#Exercise
Using the Light Cycling definition.

http://www.livestrong.com
Bicycling 10 to 11.9 mph is regarded as a “light effort” by the Wisconsin Department of Health. When you bicycle 10 to 11.9 mph, you burn about 47 calories per mile if you weigh 190 pounds, about 38 calories per mile if you’re 155 pounds and about 32 calories per mile if you’re 130 pounds.

Hubspot has previously used 43 calories/mile in statistics. With the value falling in this same range of light cycling, I chose to use it.

Average travel distance (mean):
1.75083654945 miles
1.75*43=74.82
3.1 trips/pie
Commuting to work - 10 trips/week
3+ slices
Commute - 1

Boston creme pie, Calories: 232
http://nutritiondata.self.com/facts/baked-products/4889/2


# Go Green
For 44 days (may 10th-June 23rd):
179731 miles travelled
6901.598 miles per day

https://www.epa.gov/sites/production/files/2016-02/documents/420f14040a.pdf
Greenhouse Gas Emissions from a
Typical Passenger Vehicle:

The average passenger vehicle emits about .411 kilograms of CO2 per mile. 
2767.54 kilograms saved per day (2767)
6100.191 pounds
