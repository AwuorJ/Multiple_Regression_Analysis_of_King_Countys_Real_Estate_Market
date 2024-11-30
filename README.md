# An Overview of King County's Real Estate Market Dynamics

![Real Estate Market Dynamics](https://github.com/user-attachments/assets/cbbdb829-86d6-4837-9f9b-3180e5ce7942)


### Introduction

King County is the most populated county in Washington State and is home to Seattle, a growing tech hub that is currently drawing more people into the county. However, the real estate sector has not been sufficiently responsive to meet the housing demand needs of this growing population. So, how can urban and real estate developers work to cater to the suppressed supply of homes in the region?

By leveraging data-driven insights, this project aims to uncover structural and environmental factors that have contributed to inflated house prices and provide strategic solutions to address the concurrent housing demand and supply problems. 


### Problem Statement

**Background:**
King county recorded the highest median home price of $1 million in 2022 which was driven by the growing, tech-influenced population. While very little can be done by the private sector to stifle the economic factors limiting affordable supply of homes, urban and real estate developers should incorporate structural factors that will mitigate the existing astronomical home prices without compromising comfort, in order to meet the increasing demand.


### Objectives:

**1. Analyze the impact of market entry and exit on house pricing:**

Investigate whether seasons have any impact on house pricing by analyzing the month sold. Determine whether house prices were influenced by the timing of their market entry.

**Findings:** 
House prices in King County have exhibited frequent shifts, indicating alternating periods of growth and decline within the real estate market. Notably, prices peaked around 1905 and reached their lowest point in 1944. Since 2013, there has been a steady increase in house prices.

These fluctuations suggest market volatility, potentially driven by shifts in demand or economic factors such as mortgage interest rates, inflation, and fiscal policies.

On the other hand, house prices have been relatively constant across the months. This indicates that the prices are independent of seasonal effects.


**2. Assess the role of outdoor space in house prices:**

Evaluate the condition of the outdoor spaces, including waterfront and view, and their contribution to the overall pricing of homes.

**Findings:** 
Houses with access to waterfronts have significantly higher prices compared to those without. Their prices have also been steadily increasing over the years, which may indicate either a growing preference by buyers for waterfront properties or economic factors such as rising land values in waterfront areas.

Similarly, houses with views are priced higher than those without, and these prices have been steadily increasing since 1940.

In general, the condition of outdoor spaces significantly contributes to high house prices.


**3. Explore the relationship between home layout and house prices:**

Analyze the impact of home layout, the number of bedrooms, bathrooms and floors, on pricing. Identify areas where the layout can be modified to enhance affordability without compromising comfort.

**Findings:** 
The number of bedrooms directly affects home prices, with houses that have more bedrooms costing more than those with fewer bedrooms. However, there were exceptions. For instance, in the 1930s and 1940s, 4-bedroom homes were priced higher than 5-bedroom homes, while in the 2010s, 2-bedroom homes had slightly higher prices than 3-bedroom homes.
In those few instances, factors such as the size of the bedrooms and the overall size of the homes may have played a significant role in determining their prices.

There is a direct association between the number of bathrooms and home prices. Homes with more bathrooms generally cost more. Despite this, only 4.71% of the homes have 4 bathrooms, while 66.60% have 2 bathrooms.

Finally, the number of floors does not have a direct effect on price. Houses with four floors are priced similar to, or lower than, those with three or fewer floors. However, houses with only one floor are priced the lowest in this group.

4-storey houses make up only 0.03% of the total, while those with 1 and 2 floors account for 49.77% and 47%, respectively.


**4. Develop a multiple regression model to predict future house prices:**

Build and evaluate a multiple regression model to forecast house prices. Provide real estate and urban developers with a predictive tool for estimating housing prices and supporting strategic decision-making in urban development.

**Findings:** 
The multiple regression model achieved an **R-squared score of 0.6449** on the test set. This indicates that 64.49% of the variance in house prices can be explained by the predictors used.

However, 35.51% of the variance is not captured by the model, meaning  that other factors influencing pricing are not included in this regression analysis. Such factors, as mentioned earlier, could mainly be economic factors.

Nevertheless, the predictors included in this analysis are features that real estate and urban developers can adjust to help accommodate the growing demand for affordable housing.
