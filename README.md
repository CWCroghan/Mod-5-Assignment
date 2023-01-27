# Overview of the analysis:

Pyber is a ridesharing application company that offers its services in a wide range of cities and towns.  They are concerned about how to best provide their services in underserved areas.  To better understand the problem, they collected data for 120 cities where people used their services and classified each city into three distinct types: Urban, Suburban, and Rural.  By examining the number of rides, the number of available drivers, and the fare cost, they hope better to understand any discrepancies in the different community types.

## Results:

Data were collected for 120 cities.  The breakdown of the different types is as follows:

### Table 1: Distribution of community types.

<table>
<tr>
<th>Type</th>	
<th>Total Cities</th>
</tr>
<tr>
<td>Rural</td>	
<td>18</td>
</tr>
<tr>
<td>Suburban</td>	
<td>36</td>
</tr>
<tr>
<td>Urban</td>	
<td>66</td>
</tr>
</table>

For each of the different community types, the total number of rides, total number of drivers, total cost of fares, the average price of fare per ride, and average cost of fare per drivers were calculated.
The results are summarized in the following table:
### Table 2: Summary of data by each community’s type
<table>
<tr> 
<th> </th>		
<th>Total Rides</th>		
<th>Total Drivers</th>		
<th>Total Fares</th>		
<th>Average Fare per Ride	</th>	
<th>Average Fare per Driver </th>	</tr>
<tr><td>Rural</td>	
<td>125</td>	
<td>78</td>	
<td>$4,327.93</td>	
<td>$34.62</td>	
<td>$55.49</td>
</tr>
<tr><td>Suburban </td>	
<td>625</td> <td>490</td>	
<td>$19,356.33</td>	
<td>$30.97</td>	
<td>$39.50</td></tr>
<tr><td>Urban</td>	
<td>1625</td>	
<td>2405</td>	
<td>$39,854.38</td>
<td>$24.53</td>	
<td>$16.57</td></tr>
</table>

The data were also examined as a time series to look for trends in the total fares on a weekly basis.  The total fare was calculated for each community’s type for each week.  The line plot is presented in Figure 1.

### Figure 1:
![Line graph displaying lines for Rural, Urban, and Suburban ride-sharing activity](https://github.com/CWCroghan/Mod-5-Assignment/blob/main/analysis/PyBer_fare_summary.png)


## Summary:

According to a 2018 Gallup U.S. Poll concerning the use of ride-sharing apps (https://news.gallup.com/poll/237965/snapshot-uses-ride-sharing-services.aspx) "Seniors, town/rural residents are least likely to use them”.
  
The Pyber data reflects those findings.

While Pyber has made good penetration into the Urban market, the Suburban market is lagging but still doing well.  The Rural market is struggling.  

The difficulty with the Rural market is threefold.

  1.	The number of drivers available is limited.
  
  2.	The distance between locations is larger than in urban or Suburban markets.
  
  3.	The median income for Rural residents is lower than for Urban residents. In addition, the poverty rate is higher for Rural residents than Urban residents. (https://www.census.gov/library/stories/2018/12/differences-in-income-growth-across-united-states-counties.html)

With limited competition and further distances, Rural residents pay more for a ride than Urban residents ($34.62 Rural;  $24.53 Urban)  while having the least resources to pay for those rides.

In addition, there is a great percentage of older residents in Rural communities than in Urban and Suburban communities.  

According to the Pew Research organization, “As a group, rural counties skew older than suburban and urban counties: 18% of rural residents are 65 or older vs. 15% in suburban and small metro counties and 13% in cities.”  (https://www.pewresearch.org/social-trends/2018/05/22/demographic-and-economic-trends-in-urban-suburban-and-rural-communities/) 

The combination of poverty, age, and greater distances needed to travel has made up-take of Pyber in Rural communities more challenging.

Our recommendations are that Pyber:

  1.	Change its fee algorithm for Rural areas charging less per mile.
  
  2.	Seek to educate the older populations about the benefits and convenience of ride-sharing.  Perhaps by partnering with some organizations for the elderly residents and offering low-cost transportation.
  
  3.	Recruit more heavily in Rural communities for drivers with more lucrative employment benefits.
  
 
These suggestions might in the short-term result in less revenue generation from Rural communities. In the long-term, better PR and more ridership will show an increase in revenue.
