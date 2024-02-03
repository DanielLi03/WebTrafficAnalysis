# WebTrafficAnalysis

Analysis of web traffic data at statforecasting.com. Data was taken from [kaggle]([https://www.kaggle.com/datasets/bobnau/daily-website-visitors/data]). Performed Data Cleaning, EDA/Data Visualization, Data Transformation, and A/B testing to identy certain trends in the data. Below is a snippet of what the data looks like.

![image](https://github.com/DanielLi03/WebTrafficAnalysis/assets/54047781/68ee9c0f-d437-48db-8d5a-0a62ba16108f)

### Overview of the Data

- Row: Refers to the row number
- Day: Day of the week in which the data was recorded
- Day.Of.Week: same as above but in numeric form where Sunday = 1, Monday = 2 and so on
- Date: Date in which the data was collected
- Page.Loads: Number of time the page was visited
- Unique.Visits: Number of unique users that visited the page (based on IP address which can undercount the real number of unique visits)
- First.Time.Visits: Number of users that visited the page for the first time (again based on IP address)
- Returning.Visits: Number of non-first time users, important to note that Returning.Visits = First.Time.Visits - Unique.Visits

### Interesting findings

- Weekdays eperienced more traffic than weekends With the peak around Tuesday-Wednedsday gradually declining to Sunday before another spike at Monday
- In terms of week by week traffic, every 51-54 weeks there'd be a drastic drop in web traffic (most likely) corresponding to the New Year/Holidays
- In thers of seasonal trends, there would be a 6 month cycles, where there'd be regular dips in the middle of each 6 month cycle, corresponding to (presumably) summer and winter holidays.

