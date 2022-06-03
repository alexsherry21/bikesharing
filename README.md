# NYC Citibike

Tableau work in Module 14

## Overview

The purpose of this module was to use Tableau to study Citibike data in New York City to help with our pitch for Des Moines, Iowa.

## Results

### Tableau Story

[Link to Tableau Story](https://public.tableau.com/app/profile/alex.sherry/viz/NYC-Citibike-Challenge_16542303844700/NYCCitibikeAnalysis)

### Visualizations and Descriptions

#### Subscriber Proportion

![customer-type](https://user-images.githubusercontent.com/100380226/171811915-c149df20-feb2-43b3-ba29-5c4de68ba1d5.png)

In August 2019, 2,344,224 Citibike Rides were taken.  Just over 1,900,000 came from Citibike subscribers, which is greater than three out of four.

#### Trips by Gender

![trips-by-gender](https://user-images.githubusercontent.com/100380226/171813161-a1ab11f5-31d3-41a2-94de-b66754999acd.png)

We had over one and a half million trips listed with a male rider, which equates to about two thirds of our sample.  Just under 10% of rides are list gender as unknown.

#### Checkout Times

![checkout-times](https://user-images.githubusercontent.com/100380226/171813174-1d49657d-7b75-42f3-939d-a22de5bda151.png)

The most common trip duration is five minutes.  This is a large spike followed by a trail to the right with relatively few rides going for longer than forty minutes.  The skewness of the trip duration distribution will drag the mean up, so it is useful to see how extremely popular trips taking four to seven minutes are.

#### Checkout Times by Gender

![checkout-times-gender](https://user-images.githubusercontent.com/100380226/171813182-e9d12df4-7fc9-4083-9635-92745956422a.png)

We see the the male and female lines match the overall pattern, but trips listing gender as unknown have a distribution with a higher average duration and much wider peak, extending from seven to twenty-three minutes in trip length.

#### Trips by Weekday per Hour

![trips-by-weekday-per-hour](https://user-images.githubusercontent.com/100380226/171813201-4ff842ea-c00b-4dd2-95f1-32ae235052cb.png)

During the work week, trips most heavily began in the hours of 7:00 AM to 9:00 AM and 5:00 PM to 7:00 PM, as these are the most common commuting times.  On weekends, bike rentals start picking up around 10:00 AM or 11:00 AM and are more evenly spread throughout the day before slowing down at 7:00 PM or 8:00 PM.

#### Trips by Gender by Weekday per Hour

![trips-by-gender-weekday-per-hour](https://user-images.githubusercontent.com/100380226/171813209-882208be-33d0-44c3-926f-6817344e9ed7.png)

The male and female heatmaps again match the larger pattern, while the "unknown" heatmap when viewed alone shows a drastic difference, with Saturday afternoon having the most volume by far out of any time of the week, followed by Sunday afternoon.  During the week there is some postwork traffic, but very little prework traffic compared to the overall heatmap.

#### User Trips by Gender by Weekday

![user-trips-by-gender-weekday](https://user-images.githubusercontent.com/100380226/171813220-71f03830-1a9e-4e22-ac62-2fccc5abb609.png)

Trips taken by male Citibike subscribers comprise our largest subgroup, with Thursday and Friday being their most frequented days.  This heatmap also shows very few subscribers not listed as male or female, while trips taken by non-subscribed customers are most likely to have gender listed as unknown.

#### User Trips by Birth Year

![user-type-by-birth-year](https://user-images.githubusercontent.com/100380226/171813255-d6ffa15b-f390-4643-9fe2-6430c33e610a.png)

The graph has its sharpest spike in birth year in 1969, which is a huge anomaly compared to the trend of either line.  The spike is sharper for non-subscribed customers than for subscribers, implying that, like gender, customers are much more likely to leave the field blank.  The birth year field appears to have a default input of 1969 that many don't bother changing.  Accounting for that, while the peak of both curves is located around 1990, the subscriber base has a much larger older portion.  The customer base was almost entirely born after 1980.

#### Average Trip Duration by Weekday by User Type

![duration-by-weekday-by-user-type](https://user-images.githubusercontent.com/100380226/171813273-9e1da309-f921-4461-97a7-c599c2934595.png)

Non-subscribed customers take much longer trips than subscribers on average.  Both groups have their shortest trips in the middle of the week.  Most days of the week, the average customer trip exceeds thirty minutes, while the average subscriber trip is shorter than fifteen minutes.

## Summary and Suggestions

### Summary of Results

Our visualizations show clear differences in behavior between subscribed and non-subscribed customers.

### Suggestions for Future Visualizations

One potentially very useful visualization would be a table of the top ten or twenty most frequent end stations for non-subscribed customers, as these could be great locations to occasionally dispatch a salesperson to advertise or sell subscriptions to people who (hopefully) just finished enjoying a Citibike.  For our purposes, if these destinations carried a theme it could help us select good station locations in Des Moines.  A similar graphic could be made with start stations instead to find more potential good station patterns.

Another visualization idea would be to 
