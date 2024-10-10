# :chart_with_upwards_trend: California-Housing (Python) :chart_with_upwards_trend:


# **Introduction :**

The California Housing Dataset, drawn from the 1990 U.S. Census, provides a wealth of information on housing prices, demographics, and geographical parameters across districts in California. This dataset captures key variables such as median income, median house values, housing median age, proximity to the ocean, and geographical coordinates like longitude and latitude. As California is one of the largest real estate markets in the United States, understanding these variables is crucial for a variety of stakeholders, including urban planners, real estate developers, investors, and policymakers.

The housing market in California is dynamic and influenced by numerous factors, such as proximity to natural amenities like the ocean, economic factors like household income, and regional geography. The dataset presents an opportunity to analyze how these factors interplay to impact house prices and availability. By understanding how socio-economic and geographical variables are distributed and how they affect property values, key players in the housing market can make informed decisions about where and how to invest, build, and develop.

The purpose of this analysis is to uncover meaningful patterns and relationships within the dataset to address pertinent business questions. These insights will help answer vital questions related to the housing market, such as identifying income patterns, understanding the impact of ocean proximity on housing distribution, and assessing the age of housing infrastructure. By exploring these dimensions, we aim to provide a comprehensive understanding of the housing landscape in California, which will enable data-driven decision-making and strategic planning.


# **Purpose :**

This analysis seeks to address five key questions to guide business decisions:

- **Determine the average median income** of California's districts and visualize the distribution.


- **Explore the relationship between median income and house values** to understand housing affordability.


- **Plot latitude and longitude** coordinates to visualize geographic clustering and identify housing patterns.


- **Analyze proximity to the ocean** and determine the distribution of housing occurrences near various ocean proximity categories.


- **Visualize the distribution of housing median age** to understand the age of properties in different regions.


# :paperclip: **Tools :** 
**Python (Pandas, Matplotlib, Seaborn)**


# :paperclip: **Understanding the data :**


- **Longitude :** distance east or west of the prime meridian

- **Latitude :** Latitude lines circle the planet from east and west, beginning at 0° at the equator and increasing to 90°North or 90°South.

- **Housing Median Age :** Median Of Age Of People Resident to the Housing

- **Total Rooms :** Total Number Of Rooms Present.

- **Total Bedrooms :** Total Number Of Rooms Present.

- **Median Income :** Median Income Of Residant In Area

- **Median House Value :** Median Value of House in Area(measured in Dollar($))

- **Ocean Proximity :** Proximity To Ocean/Beach

- **Greenwich Mean Time (GMT)** is the mean solar time at the Royal Observatory in Greenwich, London which is measured at midnight. In English speaking nations, GMT is often used synonymously with Universal Time Coordinate (UTC).


# :key: Business Questions:



1. What is the **Average Median Income** of the data set and check the distribution of data using appropriate plots. Please explain the distribution of the plot.



2. Show with the help of visualization, **how median_income** and **median_house_values**  are related?



3. Plot **number of occurences** for houses around each ocean proximity type.



4. Draw an appropriate plot to see the distribution of **Housing Median Age** and explain your observations.



5. Plot **latitude versus longitude** and explain your observations


# **Data Analysis (Business Qiestion Solution)**


### 1. What is the **Average Median Income** of the data set and check the distribution of data using appropriate plots. Please explain the distribution of the plot.
### **Solution :**

- **Observation :**

  - The "Average Income Sales Graph" shows a histogram with a density plot. The majority of data is concentrated in the lower range of median income, with a clear right-skewness.

- **Insight :**

  - Most residents fall within a median income range of approximately **2,000 to 
 6,000.** The distribution indicates a high concentration of lower to middle-income earners, with fewer higher-income individuals in the dataset.

- **Recommendation :**

  - Target affordable housing projects in areas where income levels are lower. Policies aimed at improving job opportunities in middle-income regions could also boost housing demand and house values.


### :key: **Graph** :key:

![Screen Shot 2024-10-04 at 10 56 50 PM](https://github.com/user-attachments/assets/6ac7f05a-5bf5-414c-8923-a3e48ff086d2)


--------------------------------------------------------------------------------------------------------

### 2. Show with the help of visualization, **how median_income** and **median_house_values**  are related?

### **Solution :**

-**Observation :**

  - The second plot illustrates a linear relationship between median income and median house values. As median income increases, the value of housing tends to rise.

- **Insight :**

  - This positive correlation indicates that areas with higher incomes also have more expensive houses. The linearity of the relationship suggests that income is a strong predictor of house value.

- **Recommendation :**

  - For potential homebuyers, prioritize higher-income areas for long-term real estate appreciation. Real estate developers should focus luxury housing projects in high-income regions where higher house values are expected.


### :key: **Graph** :key:

![Screen Shot 2024-10-05 at 12 11 15 AM](https://github.com/user-attachments/assets/47395786-ea7f-40a1-a9ea-c3940ba66383)


--------------------------------------------------------------------------------------------------------


### 3. Plot **number of occurences** for houses around each ocean proximity type.
### **Solution :**

- **Observation :**

  - The bar chart labeled "Ocean Proximity Summary" shows that the majority of houses are located less than an hour from the ocean, followed by inland areas.

- **Insight :**


  - Proximity to the ocean is a significant factor in housing distribution. The higher number of houses near the ocean likely corresponds to higher demand for coastal properties, which are typically valued higher due to lifestyle preferences.

- **Recommendation :**


  - For buyers or developers interested in premium properties, prioritize regions that are close to the ocean. Inland areas, with fewer houses, may provide opportunities for affordable developments that cater to buyers seeking lower-priced housing away from the coast.



### :key: **Graph** :key:

![Screen Shot 2024-10-05 at 12 10 52 AM](https://github.com/user-attachments/assets/d8e1320a-21ed-43c0-abbf-cd7f99d6179f)


--------------------------------------------------------------------------------------------------------


### 4. Draw an appropriate plot to see the distribution of **Housing Median Age** and explain your observations.
### **Solution :**

- **Observation :**

  - The "Housing Median (Average) Age Graph" shows a distribution where most houses fall within a median age range of 15 to 35 years.

- **Insight :**

  - The distribution indicates that a significant portion of houses are relatively old, with fewer newer houses. This trend suggests that many regions may require renovations or upgrades to modernize the housing stock.


- **Recommendation :**


  - Urban planners and developers should focus on revitalizing aging properties and creating incentives for new housing developments. For potential homebuyers, consider investing in older homes that may increase in value after renovations.


### :key: **Graph** :key:

![Screen Shot 2024-10-04 at 10 58 05 PM](https://github.com/user-attachments/assets/f0fccdd3-00df-4f40-b82f-17d42d8a437a)

--------------------------------------------------------------------------------------------------------


### 5. Plot **latitude versus longitude** and explain your observations
### **Solution :**


- **Observation :**

  - The third plot shows the geographic distribution of housing based on latitude and longitude coordinates. Most of the housing is concentrated along the coastline and inland regions of California.


- **Insight :**

  - The map clearly highlights a clustering of housing along the coastal areas, with fewer houses further inland. Coastal regions may have higher house values due to their proximity to the ocean, while inland regions likely have more affordable housing.

- **Recommendation :**

  - For housing investments, consider coastal areas for high-value properties. For more affordable housing, inland areas can be targeted for development, which may attract middle-class families seeking lower-cost housing.



### :key: **Graph** :key:

![Screen Shot 2024-10-05 at 12 11 06 AM](https://github.com/user-attachments/assets/11a43e49-55a9-458c-88d3-24aead579577)


--------------------------------------------------------------------------------------------------------


# :key: Dashboard:


![Screen Shot 2024-10-05 at 12 10 21 AM](https://github.com/user-attachments/assets/2a7e27cb-f880-4f09-9c3b-cd5e815d365d)


# **Final Recommendations :**

- **Target coastal areas** for high-value real estate investments, while inland regions can be leveraged for affordable housing projects.


- **Focus on middle-income regions** for affordable housing solutions, given the skewed income distribution.


- **Encourage renovations** and modernization in regions where housing stock is older to attract new buyers and increase property values.


- **Leverage the income-house value correlation** to predict housing market trends and strategically invest in high-income regions where property prices are likely to appreciate.

This analysis equips stakeholders with the necessary insights to make informed housing and real estate decisions in California.



# **Conclusion :**

The analysis of the California Housing Dataset reveals significant insights into the various factors influencing the housing market in the state. Several key trends emerge from the data, offering a nuanced understanding of how median income, geographic location, and proximity to the ocean impact housing prices and distribution. The dataset highlights clear relationships between income levels and house values, showing that higher income areas are associated with more expensive properties. Additionally, coastal regions, which are in high demand due to their proximity to the ocean, have a greater concentration of houses and higher property values.

Geographical analysis of latitude and longitude confirms the clustering of properties along the coastline, with inland regions offering more affordable housing. The age distribution of houses further indicates that a significant portion of California's housing stock is aging, providing opportunities for renovation and modernization projects. This could be particularly relevant for urban planners and developers seeking to rejuvenate older neighborhoods and attract new buyers.

From a business perspective, the insights gleaned from this analysis provide actionable recommendations. Coastal regions, with their high property values, are ideal for high-end real estate investments, while inland areas could be targeted for affordable housing developments to meet the needs of middle-income families. Furthermore, the strong correlation between income and housing value serves as a predictive tool for identifying potential areas of growth in the housing market. Finally, focusing on renovating older homes could lead to significant value appreciation in many areas.

In summary, the California housing market is influenced by a complex set of socio-economic and geographical factors. By leveraging the insights from this dataset, stakeholders can make informed, strategic decisions that align with current market conditions, thereby maximizing their investments and contributing to sustainable housing development in the state. This analysis equips real estate professionals, policymakers, and investors with the tools they need to capitalize on emerging trends and respond effectively to the housing demands of California’s diverse population.
