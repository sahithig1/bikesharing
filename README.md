# NYC Citibike Analysis
MODULE 14 - Citibike analysis

## OVERVIEW
### Purpose:  The purpose of the current analysis is to prepare visualizations that give potential investors a look into the highly-successful NYC Citibike bike-sharing program, so that they can see for themselves that a bike-sharing program in Des Moines is a solid business proposal.  Among others, we have prepared visualizations that 1) Show the length of time that bikes are checked out for all riders and genders, 2) Show the number of bike trips for all riders and genders for each hour of each day of the week, and 3) Show the number of bike trips for each type of user and gender for each day of the week.


## RESOURCES
  - Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv
  - Software:  Tableau, Python 3.7.6, Jupyter NB, Pandas Library


## RESULTS
#### The results of our analysis have been incorporated into a [story on Tableau Public](https://public.tableau.com/app/profile/satya3688/viz/NYCCitybikeModule14/FinalPresentation)

  - [POINT #1](Images/Pt2.png) - Looking at visualizations for **'Checkout Times for Users'** and **'Checkout Times by Gender'**, we see that most rides are for 20 minutes or less, and that the vast majority of rides are less than one hour.  We also see that this pattern is the same regardless of gender.

  - [POINT #2](Images/Pt4b.png) - The heatmap of **'Trips by Weekday per Hour'** shows a clear pattern of bicycle useage 1) during the morning weekday commute (7-9 a.m.), 2) during the evening weekday commute (4-7 p.m.) except on Wednesday evenings, and 3) all day long on weekends.

  - [POINT #3](Images/Pt5.png) - The **'Trips by Gender (Weekday per Hour)'** heatmap shows that the useage pattern is true regardless of gender, although the total numbers for males is considerably higher.

  - [POINT #4](Images/Pt6.png) - The **'User Trips by Gender by Weekday'** heatmap demonstrates the following points:  subscribers are mostly male and account for most of the weekday activity,  customers' gender are often unknown,  and useage on the weekend is more evenly split between subscribers and customers.


## SUMMARY
### The results of this analysis have given insight into the utilization of bicycles in the NYC Citibike bike-sharing program. We've seen the patterns of useage by time and by gender.  Utilization rates can now be predicted based on time of day and location.  Weekday useage is heavily concentrated around the morning and afternoon commute.  Weekend useage is more evenly spread through the day.  We would recommend further analysis for a few points.  Firstly, while we've seen that the vast majority of trips are 30 min or less, we should perform further analysis to compare weekend trip durations to weekday trip durations.  We should also look further into the patterns of useage for the bicycles that see the heaviest use, perhaps preparing maps showing all of the starting/ending routes/locations for the heaviest use bikes.  We should also prepare a visualization to determine if there are specific locations that are completely unused.

