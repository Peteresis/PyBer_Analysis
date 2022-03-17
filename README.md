# PyBer Analysis

## 1. Overview of the analysis: Explain the purpose of the new analysis.

The goal of this challenge is to provide ridesharing data visualizations for PyBer in order to promote access to ride-sharing services and determine affordability for underprivileged neighborhoods.

The study is based on data obtained in the form of a CSV file from PyBer. This data has been processed using Python's Pandas to produce a summary dataframe (shown below) as well as a chart generated using the information in the dataframe to visualize the data.


## 2. Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

### Fig 1. Total Fare by City Type
![PyBer_fare_summary](https://github.com/Peteresis/PyBer_Analysis/blob/8a009cfc96a152c416d4bca385b9d78df2c3fcb9/analysis/PyBer_fare_summary.png)

The figure 1 chart illustrates that the quantity of money made by the service is fairly steady over the time period studied (January to May). Urban cities generate the most total revenue, followed by suburban and rural locations. When comparing urban and suburban cities, the average connection is 2:1, while the same relationship between urban and rural cities is 9:1.

The observed outcome is not surprising, given that cities are expected to generate more revenue because they have more inhabitants than suburban or rural locations.

Figure 1 does not include any information about the cost of the service to its users; for that, see Figure 2 below.

### Fig 2. Summary Dataframe by City Type
![PyBer Summary Dataframe](https://github.com/Peteresis/PyBer_Analysis/blob/407d939297c5f070d6815984562729dd029bd756/analysis/PyBer%20Summary%20Dataframe.png)

The numbers of the summary Dataframe above, show some underlying realities that Figure 1 does not reveal. First of all, there is a tremendous disparity in the number of rides in Urban cities and Surburban or Rural ones (2.6:1) and between Urban and Rural (13:1).  Also, the number of drivers in Urban areas is almost 5 times bigger than in the Suburban cities, and 31 times larger than in Rural communities.  Likewise, the number of rides per driver favors Rural and Subrban drives when compared to Urban drivers.  The relationship is `0.68 Rides/Driver in Urban cities vs 1.28 in Suburban and 1.6 in Rural`. 

When we look at the income generated though, the `Average Fare per Ride` is 20% lower in the Urban cities vs Suburban, and 30% lower in Urban vs Rural. 




## 3. Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.







