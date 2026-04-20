# UK - EU Trade Network Analysis (2019 - 2022)
#### Network Analysis · Data Science · Visualization · Python · Gephi · Tableau · Economic Data

<img width="676" alt="image" src="https://github.com/harleytran1902/UK-EU-Trade-Network-Analysis-2019-2022-/raw/12a67156f5cccbf4e1b0738c13fed3b254327892/Visualization%20Poster%20png%20(1).png">

## 1. Project Summary
Between 2019 and 2022, the European trade system experienced several major shocks, including Brexit, COVID-19, inflation, and the Russia-Ukraine war. While trade volumes have been widely studied, fewer analyses look at how the structure of trade relationships changed during this period.

In this project, network analysis and data visualization was used to explore how the trade network between the UK and EU/EFTA countries evolved, and whether the UK’s role in the network shifted after Brexit.

The goal is not only to measure trade size, but to understand how countries are connected, which countries act as hubs, and how regional trade communities formed over time.

This analysis provides insights into how geopolitical shocks reshape trade dependencies and regional economic power structures'

## 2. Problem Statement
Most trade analyses focus on total import/export values, but this approach does not capture:
- Structural changes in trade relationships
- Influence of countries inside the network
- Emergence of regional trade clusters
- Changes in strategic position after geopolitical events

This project aims to answer:
- _**How did the structure of the UK–EU/EFTA trade network change between 2019 and 2022, and how did Brexit affect the UK's position in the network?**_

### **Who This Analysis Is For?**
+ Policy makers evaluating post-Brexit trade impact
+ Companies managing European supply chains
+ Strategy teams assessing regional market dependencies

## 3. Data
<img width="676" alt="image" src="https://github.com/harleytran1902/UK-EU-Trade-Network-Analysis-2019-2022-/raw/91e3123db26dbcec1698a2509e7acda9a5602c4d/Screenshot_17-4-2026_14758_.jpeg">

- Trade data was collected from the World Integrated Trade Solutions (WITS) database, covering goods trade between the UK and 30 EU/EFTA countries from 2019 to 2022.
- The raw dataset contained thousands of rows for each year and required restructuring before it could be used for network analysis.
- To avoid bias toward large economies, trade connections were not measured by total USD value alone. Instead, each connection was weighted by the percentage of a country’s total exports going to a specific partner. This makes it easier to see how important a relationship is for each country, not just how large the trade volume is.

<img width="676" alt="image" src="https://github.com/harleytran1902/UK-EU-Trade-Network-Analysis-2019-2022-/raw/815d354f3990c3046a7153f1e777c036978274c1/Figure%203.2">

- After cleaning and transformation, the data was converted into a network format where:
  - Nodes = countries
  - Edges = trade relations
  - Weight = strength of export relationship

<img width="676" alt="image" src="https://github.com/harleytran1902/UK-EU-Trade-Network-Analysis-2019-2022-/raw/a2c4ada27b6d37f14fecf7702956bc628b67002c/Figure%203.3%20and%203.4.jpeg">


## 4. Method
- Social network analysis and visualization techniques were applied to analyze the structure of the trade network.
- Network graphs were built in Gephi using the ForceAtlas2 layout, where strongly connected countries appear closer together.
- Several network metrics were used to measure influence and position inside the network, including degree, betweenness, closeness, eigenvector centrality, and modularity.
- Additional visualizations were created using Tableau and Flourish to explore trade trends, major partners, and the UK’s trade deficit over time.
- Combining network graphs with traditional charts makes it easier to connect structural changes with real trade performance.


## 5. Results
- The overall network remained highly connected between 2019 and 2022, meaning that trade relations did not collapse despite major global events.
- However, the internal structure changed noticeably.
- Strengthening regional clusters suggest countries are reducing dependency on central trade hubs, especially among Nordic, Baltic, and Southern European countries, likely as a response to geopolitical uncertainty
- Germany, Poland, France, and Italy remained the most central countries in the network, with balanced and widely distributed trade connections.
- The UK remained an important node, but its centrality decreased slightly after Brexit. This suggests that the UK still trades with many partners, but plays a smaller role as a bridge between different parts of the European trade system.
- Trade data also shows that the UK’s imports grew faster than exports during this period, leading to a widening trade deficit and reinforcing the idea that structural changes in the network were happening alongside economic changes.

## 6. Conclusion
- This project shows that network analysis can reveal patterns that are not visible when looking at trade volume alone.
- Even though the European trade system stayed connected, its structure shifted toward stronger regional clusters, and the UK’s influence in the network decreased slightly after Brexit.
- The project demonstrates how combining data cleaning, network analysis, and visualization can turn complex economic data - into clear insights.

## 7. Strategic Implications (Business recommendations)
+ Companies should diversify supply chains beyond traditional hubs like the UK
+ Regional trade partnerships may become more critical for resilience
+ Market entry strategies should consider emerging regional clusters rather than pan-European assumptions


