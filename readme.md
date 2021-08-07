# Ford GoBike Data Exploration
## by Rafeek Abadir


## Dataset

I have used the "Ford GoBike System Data" provided in the class room.
The dataset consists of 183,142 observations of bike-share trips in the duration between 1st - 28th of Feb 2019. Each observation shows the trip duration, trip start time and location, trip end time and location, and characteristics of the user.
I have removed 8337 observations due to unrealistic values and missing data.


## Summary of Findings


I found relationship between duration and age, Longer trip durations are associated with younger users. I discovered also an interesting relation between trip start time and durations. whenever durations exceeds a specific threshold, users tend to weight to the next morning to end the trip rather than ending it late at night.
I have also found less than expected numbers on Feb 13t, it turned out that there was a winter storm on that day.


## Key Insights for Presentation


The main threads presented re the Duration-Age relationship, and the Duration-Trip start hour relationship, and the mysterious few numbers of 13th of Feb.

I started by presenting univariant plots to give the audiance an idea of how distributions look like., then looked deeper to bivariant plots to show the relationships mention.

Multivariant scatter plots were used to show the effect of user characterisics on the relationships.

With a clustered barplot, I was able to show how the average trip durtion was affected on Feb 13th 2019.

## Resources

1. Pandas user guide: https://pandas.pydata.org/docs/user_guide/index.html#user-guide
2. Seaborn website: https://seaborn.pydata.org/index.html
3. Matplotlib user guide: https://matplotlib.org/stable/users/index.html
4. Refernce for a winterstorm in San Fransico on 13th of Feb 2019: https://floodlist.com/america/usa/winter-storm-california-february-2019#:~:text=A%20winter%20storm%20brought%20torrential,and%20died%20at%20a%20hospital.


