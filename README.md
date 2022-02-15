# Finding Indicators of Traffic Volume using matplotlib EDA


* I'm going to analyze the westbound traffic on the I-94 Interstate highway. It is an east–west Interstate Highway connecting the Great Lakes and northern Great Plains regions of the United States.
<div>
<img src="attachment:osm-tegola,a,a,a,290x240@2x.png" width="300"/>
</div>




* John Hogue made the dataset available, and you can download it from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume).

* The goal of our analysis is to determine a few indicators of heavy traffic on I-94. These indicators can be weather type, time of the day, time of the week, etc. For instance, we may find out that the traffic is usually heavier in the summer or when it snows.

* The dataset documentation mentions that a station located approximately midway between Minneapolis and Saint Paul recorded the traffic data.

* The station only records westbound traffic (cars moving from east to west)

* The results of our analysis will be about the westbound traffic in the proximity of that station. In other words, we should avoid generalizing our results for the entire I-94 highway.

## Questions :
### <span style = 'color:purple'>Does daytime and nighttime influence the traffic volume? </span>
-- Task : Analyze using histograms after isolating the dataset based on time 
### <span style = 'color:purple'>Monthly , Day of Week , Hourly influence </span>
-- Task: Use group by to evaluate the trends using line plots 
### <span style = 'color:purple'>Weather indicators </span>
-- Task : Use correlation and bar graphs to find out the indicators
