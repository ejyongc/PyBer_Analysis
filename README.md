# PyBer_Analysis

###### Overview of the analysis: The purpose of the new analysis is well defined. (3 pt)
        
## Overview of the Analysis-

In this analysis we are working with Pyber executives to combine two important datasets (city_data and ride_data) utilizing *Python* and *Pandas*. In this new combined dataset, we segmented important KPIs like *"Total Rides", "Total Drivers", Total Fares", "Average Fare per Ride", and "Average Fare per Driver"* for each *city type*. 

The Pyber Analysis can be spearted into two separate outcomes: The *pyber_data_df* dataframe that breaks down KPIs by City Type, and the *weekly_fares_graph* that provides us a visual representation of how *fares* weekly fluctuate on each one of the three different city *types*. 

###### Results:There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)
   
## Results   
   
### Pyber Data Summary  
   
![image](https://github.com/ejyongc/PyBer_Analysis/blob/main/Analysis/pyber_summary_df.png)

In the first outcome of the Pyber Analysis we can identify some key differences between *Rural, Suburban,* and *Urban* city *types*. The first significant diffrences are the *Total Rides* and *Total Drivers*. Urban Drives are 2.16X the size of Suburban and Rural rides combined. Very similarly the total amount of drivers on a Urban City is 4.23X the size of Suburban and Rural cities combined. 
The significant differnce of *Total Rides* and *Total Drivers* amoing the city types leads to a high sum of *Total Fares* on Urban cities as well.  In this case, Urban cities generated +63% or $16k more in *Total Fares* than the Suburban and Rural city types combined.

We can see how how naturally more heavily populated cities can generate much higher revenues in terms of Fares, but we'd also wanted to consider other KPIs like *"Average Fare per Ride", and "Average Fare per Driver"* in order to identify opportunites on the way drives are geting compensated.

On our analysis we discovered that the *"Average Fare per Ride"* could flucuate between $4-$10 dollars depending on the city type. This could be explpained by idea that rides on rural cities are longer distances than those in Urban cities. 

An interesting observation we came across was the significant gap between *Rural* and *Urban* *"Averages Fare per Driver"*. This metric could raise the question that drives in *Rural* cities could be potentially generating more money than drivers in *Urban* cities. Although we don't know this for certain, we'd want to make sure drivers that chose to work for Pyber are fairly being compensated based on their work and not based on where they are located.  

### Weekly Fares by City Type
![image](https://github.com/ejyongc/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png) 

The second outcome of this analysis is our *"weekly_fares_graph"*. This graph allow us to see the Jan 2019 - April 2019 weekly trend of the total fares for each city type. Similarly to our firsts outcome (pyber_summary_df), this graph also determines that the *Total Rural Fare* is consitently higher week-over-week compared to the suburban and rural city types. 


###### Summary:There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

## Summary

In this analysis we have identified the natural correlation between the population density and the numbers of drivers, rides, and fare on a city. Although this natural correlation can sound selfintuitive, it holds additional pieces of information that we believe will be valuable to Pyber executives. 
For instance, we can conclude that the *Average Fare per Driver* on a *Rual City* is 3.4x times higher than a *Urban city.* 
With this information at hand, Pyber executives could feel inclined to investigate deeper into thier algorythm with their engineering teams how *"city type"* can be integrated into their pricing algorythm.

A second recommendation that can be drawn from this analyis could help the marketing team create a program to incentivize drivers to work on *Rural* areas where they could potentially make more in fares. 
