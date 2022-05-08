# Overview of Surf's Up Project

## Purpose

The purpose of this project was to collect more information on temperature trends for the month of June and December in Oahu, Hawaii. This information will help determine whether a surf and ice-cream shop business will be sustainable year-round. The data was retrieved by filtering the temperature data for only the June and December months, creating a dateframe for the filtered data and finally, generating summary statistics for each dataframe.  

## Resources
* Data Source: hawaii.sqlite
* Software: Jupyter Notebook 6.4.5, Python 3.7.11
* Python Libraries: Pandas library, Numpy library, Matplotlib library
* Python Toolkit: SQLAlchemy
<br>

## Project Results

<p align="center">
  <img width="300" alt="temp_summstats" src="https://user-images.githubusercontent.com/97644424/167309767-932c210b-c02f-4ec9-9ec9-3171204c14ff.png">
</p>

* The average temperature for June was 3.9 degrees higher than December, but the average for both months was above 70F. 

* 75 % of the recorded temperature in June was at 77F or below whereas in December, 75 % of the recorded temperatures was at 74F or below. Comparatively, the average temperature for June (the 50th percentile) was 74F.  

* The difference between the maximum temperature for June and December was 2 degrees but the difference between the minimum temperatures was 8 degrees. 
<br>

## Project Summary 

Overall, the temperatures throughout the month of June are higher on average than the month of December. The temperature for June are mostly in the 70 - 80 degree range as reflected in the percentiles of the summary statistics. In comparison, 25 % of the recorded temperatures for December were below 70 degrees and 50 % of the recorded temperatures were only at 71F or below. The minimum temperature for June doesn't dip below 64F but the minimum temperature for December drops down to 54F. The average temperature for both months is above 70F. 


I have included two additional queries to gather more weather data for this analysis. The first query is to build a chart based on the filtered temperature data to provide a visual in order to better comprehend the spread in temperature. 

### June

![june_chart_code](https://user-images.githubusercontent.com/97644424/167309460-5836ce32-8954-4e9a-aefa-808c60144f95.png)
![june_chart](https://user-images.githubusercontent.com/97644424/167309468-a1568ec8-d903-47b2-849a-24298d427d13.png)

<br>

### December

![dec_chart_code](https://user-images.githubusercontent.com/97644424/167309467-1f3a7401-25de-43f1-a846-7f9f137296e9.png)
![dec_chart](https://user-images.githubusercontent.com/97644424/167309466-96e47d62-1ccc-4896-8784-f6b27ee38011.png)

<br>

The second query collected perceptation data in the months of June and December to get a fuller picutre of what the weather is like during these two months. 

![june_prcp_summstats](https://user-images.githubusercontent.com/97644424/167309461-6c548b06-22e2-413e-b258-aa229ed9fcc4.png) ![dec_prcp_summstats](https://user-images.githubusercontent.com/97644424/167309464-d252fc76-aac7-4031-a909-dab3252b842d.png)

  
<br>

The code used to create the summary statistics are as follows:

![june_prcp_code](https://user-images.githubusercontent.com/97644424/167309462-95c1cbf7-5527-41f1-8ea8-97865294ddf6.png)
<br>

![dec_prcp_code](https://user-images.githubusercontent.com/97644424/167309465-9fea4ee7-14ea-4f1d-8a47-0679b698ec91.png)

