# PyBer_Analysis
## Overview
The purpose of the new analysis is to illuminate additional business data for decision makers at PyBer. Instead of simply showing some graphs or charts that may not provide the best context, this summary supports the new data analysis. Clearly, analyzing ride-sharing data for PyBer highlighted the profitability of rideshare in urban, suburban, and even rural cities. 

## Results
The image below depicts the Summary DataFrame for the ride-share data, distilled with information by city type: total rides, total drives, the sum of fares, the average fare per ride, and the average fare per driver.

![](https://github.com/scottemac00/PyBer_Analysis/blob/580d013dfd9a17fd4fccfe7691ecd617cc6e399f/Analysis/Summary_DataFrame.png)

Prior analysis demonstrated how ride data varies widely based on city type, with urban cities being where rides are most widely used and rural cities being where the least amount of rides occur. Similarly (and as expected), urban cities see the most drivers offering their services. From a macro economic perspective (e.g., supply and demand) the data validates that fares vary widely based on city type, but on average are relatively similar. The total drivers by city type shows us that the fewer the drivers, the greater the average fare per ride and fare per driver, though we expect this may also have to do with rural distances being greater (on average) than those in suburban or urban cities.

Interestingly, For 1Q19 and and the begining of 2Q19, fares by city type fluctuated minimally, as depicted in the graph below:

![](https://github.com/scottemac00/PyBer_Analysis/blob/db376160a6931611d1da314d31e4c706bba0aff9/Analysis/PyBer_fare_summary.png)

This specific data tells us that fares peak across all city types towards the end of February. Perhaps this correlates to a specific holiday or occasion, and this data positively correlates our previous analysis that is captured in Figures 1 through 7 in the [Analysis](https://github.com/scottemac00/PyBer_Analysis/tree/main/Analysis) folder of this repository.


## Summary
While this data tells us much about average weekly fare costs by city type, the analysis team recommends expanding the data for an annual review. This aggregation could assist decisionmakers identify what months are most active, thus requiring more demand for drivers. Modeling this data against other social, commercial, and political factors might illuminate areas and times of year where modest adjustments in fare price and driver incentives could increase revenue by a factor of x. Additionally, further distilling the data based on time of year, city type, and including such factors as weather or local events might also provide insight as to why average fare per ride remains similar, despite the wide disparity in total rides by city type.
