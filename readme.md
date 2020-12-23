# (FordGoBike Data Exploration and Visualization)
## by (Christine Magdy Ghobrial)


## Dataset

> Ford GoBike is a regional public bicycle sharing system in the San Francisco Bay Area, California. Ford GoBike,consists of a fleet of specially designed,The bikes can be unlocked from one station and returned to any other station in the system, making them ideal for one-way trips. The bikes are available in any time and riders have access to all bikes in the network when they become a member or purchase a pass. Ford GoBike, like other bike share systems, consists of a fleet of specially designed, sturdy and durable bikes that are locked into a network of docking stations throughout the city. The bikes can be unlocked from one station and returned to any other station in the system, making them ideal for one-way trips. People use bike share to commute to work or school, run errands, get to appointments or social engagements and more. It's a fun, convenient and affordable way to get around.

### Data Wrangling process
>fix multiple fields that are not in the correct dtype,  start_time, end_time should be datetime
add new columns for trip duration in minute, trip start date in yyyy-mm-dd format, trip start hour of the day, day of week and month
add a new column calculating riders' age from 'member_birth_year'
filter out outlier ages from visual examination of the member age distribution and statistical percentile
 casting the  'member_birth_year' and 'member_age' to integer instead of float type


## Summary of Findings

> There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm.
There was a lot of subscribers using the bike sharing system than casual customers overall.
where a large number of people can benefit from this program:
Environmentally friendly, budget friendly, and lifetsyle friendly.
Renting a bike from theFord GoBike System is a fantastic (healthy and environmentally friendly) way of moving around in the city, both for enjoyment and work.


## Key Insights for Presentation

> The more relaxing and flexible pattern of customer use shows that they're taking advantage of the bike sharing system quite differently from the subscribers  and a different usage pattern/habit between the two type of riders are seen from the exploration. Subscribers use the system heavily on work days customers ride a lot on weekends, especially in the afternoon. Many trips concentrated around 8-9am and 17-18pm on work days for subscribers, yet customers tend to use more in the late afternoon around 17pm Monday to Friday. The efficient/short period of usage for subscribers, indicating the use is primarily for work commute. 