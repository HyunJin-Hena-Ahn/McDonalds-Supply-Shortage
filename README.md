# McDonalds-Supply-Shortage
### Focusing on sustainable practices: Hub-and-Spoke Supply Chain Model & Strategic Supplier Partnerships 

## Executive Summary
This report addresses the critical challenges faced by McDonald's Corporation in its global supply chain, focusing on optimizing operational efficiency and enhancing resilience. By analyzing the **strong correlation (85%) between agricultural productivity—particularly in potatoes**—and **McDonald's sales performance across its top 20 markets,** the report highlights the significant impact of climate change on revenue fluctuations. These insights underscore the need for strategic interventions to strengthen supply chain stability.

The proposed recommendations are
- **Global Hub-and-Spoke Supply Chain Model:** Establish a subsidiary to centralize crop procurement and logistics, group countries regionally for efficient distribution, and mitigate disruptions by leveraging interconnected hubs. Advanced tracking and forecasting tools will enhance proactive management and reduce costs.
- **Strategic Supplier Partnerships:** Build long-term relationships with reliable local suppliers, promote sustainable farming practices, and ensure a steady supply of high-quality ingredients to strengthen supply chain resilience.

These strategies aim to secure supply chain stability, maintain ingredient quality, and drive continuous improvement initiatives in response to climate and market challenges.

## Problem Analysis 
McDonald's Corporation is facing significant supply chain challenges, as evidenced by shortages of key ingredients in various countries worldwide. The reliance on external suppliers for 100% of its supply chain exposes McDonald's to risks from environmental factors, market fluctuations, and supply shortages.

Each year, McDonald's Korea sources approximately 4,200 tons of lettuce, primarily from Gangwon Province. However, extreme weather conditions, including heatwaves and heavy rainfall, have impacted local farms, leading to insufficient lettuce production and subsequent price hikes. For example, at the Garak-dong agricultural and fishery wholesale market in Seoul, the price of lettuce surged by 65.9%, with a 134% increase compared to the previous year's prices (Jae-heun, 2022). This disruption resulted in McDonald's Korea's inability to provide hamburgers with lettuce to customers, necessitating temporary solutions such as offering free drink coupons instead.

In Indonesia and Malaysia, McDonald's faced limitations on French fry orders due to supply constraints. Similarly, McDonald's Japan encountered difficulties with potato imports from North America, impacting its menu offerings. McDonald's stores in Taiwan experienced shortages of hash browns, affecting their morning menu options. In Kenya, supply disruptions led to alternative side dishes being offered by competitors, and South Africa experienced chip shortages due to weather-related crop yield challenges. (JC, 2022)These instances across multiple countries demonstrate the widespread nature of supply chain issues affecting McDonald's operations globally.

## Problem Statement 
McDonald’s faces supply chain issues due to heavy reliane on local suppliers, causing disruptions during environmental stress and market fluctuations.

## Data Analysis 

### Linear Regression 
#### Data Sources
The data sources used for the linear regression analysis include:
1. FAOSTAT (Food and Agriculture Organization of the United Nations Statistical Database) for obtaining potato production data by country.
2. News articles and publications for gathering revenue data related to McDonald's in the selected countries.
#### Methodological Approach
The regression model focused on the following variables:
- Dependent Variable: Revenue difference (2022 Revenue - 2021 Revenue) in USD.
- Independent Variable: Potato Production difference (Potato Production in 2022 - Potato Production in 2021) in tons.
The linear regression equation was formulated and analyzed within Excel to assess the relationship between changes in potato production and revenue changes.
#### Result 
[image]
- **Multiple R(0.8499):** The multiple correlation coefficient of 0.8499 indicates a strong positive correlation between changes in potato production (from 2021 to 2022) and revenue changes during the same period across all observations. This suggests that as potato production varies, revenue also experiences significant changes.
- **R Square(0.7224):** The coefficient of determination at 0.7224 indicates that approximately 72.24% of the variation in revenue changes can be explained by changes in potato production. This high R Square value signifies that potato production changes explain a substantial portion of revenue fluctuations observed.

These findings imply that changes in potato production from 2021 to 2022 have a considerable impact on revenue changes in countries facing potato shortages, such as those analyzed. The strong positive correlation and high R Square value provide evidence of the relationship between potato production and revenue. However, it's essential to note that while potato production changes explain a significant portion of revenue variation, other factors not included in the model may also influence revenue changes. Further analysis incorporating additional variables may provide a more comprehensive understanding of revenue dynamics.

### Clustering
#### Data Sources 
The data sources used for the clustering analysis include:
1. FAOSTAT (Food and Agriculture Organization of the United Nations Statistical Database) for obtaining potato production data by country.
2. McDonald's restaurant data to identify the top 20 countries based on the number of McDonald's restaurants, used as a criterion for selecting countries for clustering.
#### Methodological Approach 
The clustering analysis focused on the following variables:
- Independent Variable: Potato Yield Difference (Potato Yield in 2022 - Potato Yield in 2021) in tons.
- The clustering algorithm used was K-means, with the number of clusters set to 3 based on initial analysis and insights.
#### Result 
[image]
1. **Cluster 0: Countries with Positive Yield Differences** - These countries exhibited an increase in potato yield from 2021 to 2022, suggesting stable or improved potato production.
2. **Cluster 1: Countries with Negative Yield Differences** - These countries experienced a decrease in potato yield from 2021 to 2022, indicating potential potato supply shortages or production challenges.
3. **Cluster 2: Countries with Minimal Yield Differences** - These countries showed minimal changes in potato yield, indicating relatively stable potato production.

The clustering results align with the French fries shortage in certain regions, providing evidence of potato supply challenges in countries with negative yield differences. Specifically, Malaysia, South Korea, and Japan faced French fries shortages, and the clustering identified these countries as Cluster 2 (negative yield difference),consistent with the observed events.
This analysis contributes to understanding the impact of potato production changes on supply chain dynamics and potential disruptions in the potato supply chain affecting industries like fast food. The clustering's 60% accuracy rate in matching observed events related to French fries shortages suggests its utility in identifying regions susceptible to potato supply challenges. However, for a more comprehensive assessment, further analysis considering additional variables and external factors may be necessary to enhance the accuracy of the findings.

## Strategic Recommendations 
- **Implementation of a Global Hub-and-Spoke Supply Chain Model** Centralize distribution by establishing a dedicated subsidiary as the hub to manage crop supplies, procurement, and logistics. Regionally group countries based on logistical routes and modes, with interconnected hubs ensuring timely redistribution of supplies during disruptions. This system is expected to mitigate risks from bad harvests or extreme weather by leveraging supplies from unaffected regions. Advanced tools for real-time tracking and demand forecasting enable proactive management, reducing logistics costs, optimizing transportation, and enhancing overall supply chain resilience.
- **Strategic Supplier Partnerships** Develop strong, long-term relationships with local suppliers to ensure a stable and consistent supply of critical ingredients such as potatoes, tomatoes, and lettuce. By identifying and partnering with reliable suppliers, McDonald's can negotiate favorable contracts that provide a steady and predictable market for farmers, reducing sales uncertainty and securing their income. Additionally, promote sustainable farming practices, encouraging suppliers to adopt methods that support long-term harvest stability. This approach will not only ensure high-quality ingredients but also strengthen the resilience of the supply chain while fostering mutual growth and sustainability.
 





