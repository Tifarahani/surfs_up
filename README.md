# Surfs_up

## Overview of the analysis:

The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one being for June and the other being December. 
Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. We can refer to [Figure 4 ](https://github.com/Tifarahani/surfs_up/blob/main/Images/June%20Temp.png) and [Figure 8](https://github.com/Tifarahani/surfs_up/blob/main/Images/Calculate%20and%20print%20out%20summary%20of%20Dec%20DF.png) for summary of the result in the following months.
### Resources  
- **Python** 
- **Pandas** 
- **SQLAlchemy** 

## Deliverable 1: Determine the Summary Statistics for June
<p align="center">  
 <img src="https://github.com/Tifarahani/surfs_up/blob/main/Images/Import%20and%20Filter%20Data%20of%20June.png"  title="hover text">
</p>
<p align="center">  
<i>Figure 1:Retrieve all the temperatures for the month of June</i>
</p>
---
<p align="center">  
 <img src="https://github.com/Tifarahani/surfs_up/blob/main/Images/Convert%20june%20temp%20to%20list.png"  title="hover text">
</p>
<p align="center">  
<i>Figure 2:Convert Data to list</i>
</p>
---
<p align="center">  
 <img src="https://github.com/Tifarahani/surfs_up/blob/main/Images/Create%20Dataframe%20from%20list%20of%20temp.%20of%20June.png"  title="hover text">
</p>
<p align="center">  
<i>Figure 3:Convert list to DataFrame</i>
</p>
---
<p align="center">  
 <img src="https://github.com/Tifarahani/surfs_up/blob/main/Images/June%20Temp.png"  title="hover text">
</p>
<p align="center">  
<i>Figure 4:Generating the summary statistics for the June temperatures DataFrame</i>
</p>

## Deliverable 2: Determine the Summary Statistics for December
<p align="center">  
 <img src="https://github.com/Tifarahani/surfs_up/blob/main/Images/December%20filtering%20Data.png"  title="hover text">
</p>
<p align="center">  
<i>Figure 5 :Retrieve all the temperatures for the month of December</i>
</p>
---
<p align="center">  
 <img src="https://github.com/Tifarahani/surfs_up/blob/main/Images/Converting%20December%20Temp%20to%20a%20list.png"  title="hover text">
</p>
<p align="center">  
<i>Figure 6:Convert Data to list</i>
</p>
---
<p align="center">  
 <img src="https://github.com/Tifarahani/surfs_up/blob/main/Images/Create%20Data%20Frame%20from%20list%20of%20December.png"  title="hover text">
</p>
<p align="center">  
<i>Figure 7:Convert list to DataFrame</i>
</p>
---
<p align="center">  
 <img src="https://github.com/Tifarahani/surfs_up/blob/main/Images/Calculate%20and%20print%20out%20summary%20of%20Dec%20DF.png"  title="hover text">
</p>
<p align="center">  
<i>Figure 8:Generating the summary statistics for the December temperatures DataFrame</i>
</p>
---

## Deliverable 3:A written report for the statistical analysis

The key differences in weather between June and December and two recommendations for further analysis.
Average temperature between June and December is 75 and 71 degrees respectively, show a moderate temperature and very little fluctuation between the two periods from an average standpoint.
the maximum temperatures of 85 (June) and 83 (December) are also remarkable similar.
the minimum temperature of 56 (December) and 64 (June) show the greatest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.

* Two recommendations for further analysis:
 Additional queries that could be run include: 
   1-Precipation difference between June and December to determine is one has more rainy weather.Hence, we need to gain more data from the area to run more queries.
   2-Comaparison between weather stations, as we may see higher/lower temperatures and precipitation levels at different locations
   3-Additional data can be gathered such as wave swells and wind condition to have more analystic overview

## Summary
December and June weather are very similar, although December has a wider range of results, with its high being close to June's but its low well below June's.
The average temperatures in June and December only differ by 4 degrees. It woul dbe advisable to open a surf and icecream shop.
