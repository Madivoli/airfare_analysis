## U.S. Airfare and Route Pattern Analysis: 1993-2024

![chuttersnap-xDjcU1Pglro-unsplash](https://github.com/user-attachments/assets/620e6067-4e7c-4eeb-9034-7559e9627020)


**Introduction**

This project leverages the U.S. airline passenger and fare dataset (1993-2024) to demonstrate how data-driven insights can be a competitive advantage for the bus industry in Kenya. By applying advanced data analysis techniques, this analysis will reveal popular routes, passenger travel patterns, seasonal trends, and competitive dynamics in the airline market.

The findings can be used as a strategic blueprint for Tahmeed Bus Company's senior managers to:
- **Evaluate current routes for potential high-demand corridors.**
- **Identify opportunities for new routes where demand is high, and a competitive pricing strategy could attract passengers.**
- **Optimize pricing strategies by understanding seasonal fluctuations and competitor pricing.**
- **Gain a competitive advantage by anticipating market shifts and making informed, proactive business decisions.**
  
The analysis highlights how a structured approach to data can move Tahmeed Bus Company from being reactive to proactive, ensuring sustainable growth and market leadership in the East African transportation industry and beyond. The project involved data cleaning and transformation, exploratory data analysis (EDA), data analysis with DAX, and data visualization using Tableau. 

The analysis aimed to answer the following business questions:
1.	**Which is the most profitable and popular route?**
2.	**Is there a correlation between distance and fare? If there is a relationship, what is the type of relationship?**
3.	**Which is the busiest city and airport? Both outgoing and incoming?**
4.	**What are the fare and passenger travel patterns over the years?**
   
By analyzing travel patterns, pricing strategies, and the industry’s competition, Tahmeed Bus Company can optimize existing routes, launch new routes and services, and capitalize on underserved markets — enhancing passenger experience, reducing operational costs and increasing market share.

---

**Data Analysis and Reporting**

---

**Profitable Routes Analysis**

The purpose of this analysis is to **calculate the profit margin of each route**, specifically **determining how much profit each route generates for every dollar of revenue**. By understanding the profit margin for each route, **Tahmeed Bus Company can allocate resources such as buses, fuel, and drivers to routes that are financially viable**, resulting in **a better return on investment (ROI)**.


<img width="1365" height="727" alt="image" src="https://github.com/user-attachments/assets/fe8d7614-0aab-4754-a48e-96e24a7fa2bc" />


🔍 **Key Insights**
- **Profit margins vary significantly across different routes**, even from the same city of origin. For example, the route from Albany, New York, to Washington, D.C., has a profit margin of 72%, while the Albany to Tampa, Florida route has a profit margin of 42%. **This variation indicates that not all routes are equally profitable**.
- **Some routes demonstrate particularly high profit margins**, such as Albany to Washington, D.C. (72%), Albuquerque to Phoenix (94%), and Albuquerque to Las Vegas (89%). **These routes generate strong returns relative to their costs**, especially considering the industry average profit margin of 36%.
- **Certain routes are unprofitable, as evidenced by their negative profit margins**. For instance, the Albany to San Francisco route has a profit margin of -16.5%, and the Albuquerque to Miami route shows a profit margin of -16.6%. **These figures indicate that these routes incur losses that far exceed their revenues**, presenting a serious business concern that requires the attention of senior management.

📉 **Business and Operational Implications** 
- **The routes with negative profit margins are essentially being subsidized by the profitable ones**. However, this situation is **unsustainable in the long run**. Continuing to operate these unprofitable routes drains the company’s resources and overall profitability.
- Resources such as aircraft, fuel, and pilots are being allocated to routes that are not financially viable, resulting in a **misallocation of resources**. This prevents the company from investing more in its highly profitable routes, which yield a better return on investment (ROI).
- The significant disparity in profitability indicates that **the company's pricing model may not accurately reflect the costs or market demand for each route**. Therefore, the company should **consider reviewing its pricing models and strategies**.

💡 **Recommendations for Managers**
- The company should **investigate routes with negative profit margins**, such as those from Albany to San Francisco and Appleton to Tampa Bay. This is **to identify the specific reasons for their unprofitability** — whether it is due to low demand, high operational costs, or intense competition.
- Based on the findings from this investigation, the company must decide whether to **optimize these routes to improve profitability**, which may include _increasing fares, reducing costs through efficiency, decreasing flight frequency_, or **changing the size of the aircraft**. Alternatively, if these routes cannot be made profitable, the company may **consider discontinuing them altogether**.
- Additionally, the company should **analyze the characteristics of its most profitable routes**, such as Albany to Washington, D.C., and Albuquerque to Phoenix. By understanding what makes these routes successful, the company can attempt to **replicate their success on other routes** or **explore new routes with similar characteristics to maximize overall profitability**.
- To expand profitable operations, the company should **reevaluate its entire pricing structure**, especially for loss-making routes. This reevaluation will **help ensure that prices are more closely aligned with costs** and **market value for each route**, thereby _standardizing profit margins_ and _preventing significant losses on any single route in the future_.

---
---
**Popular Routes Analysis**

Popular route analysis provides transportation and logistics businesses with crucial data to **optimize operational efficiency**, **reduce costs**, and **improve customer satisfaction**. By understanding which routes are used most often, and the factors affecting them, Tahmeed Bus Company can make smarter, data-driven decisions that impact their bottom line and competitiveness. For example, if many passengers on the Nairobi to Dar-es-Salaam route are connecting to Arusha, a direct bus to Arusha might be viable.

<img width="1365" height="729" alt="image" src="https://github.com/user-attachments/assets/f7d5cdac-a359-4ec4-9479-95f7cb372b55" />



🔍 **Key Insights**
- Several routes are particularly popular, including **Chicago - New York City with 1 million passengers**; **Los Angeles - San Francisco with over 2 million passengers;** and **Boston - Washington, with over 700 thousand passengers**. These figures indicate **a high volume of travelers on these routes**.
- In contrast, **some routes experience very low passenger counts**, forming what is often referred to as **a "long tail"**. For example, Chicago, IL - Spokane, WA and Los Angeles, CA - Savannah, GA, each had slightly over a thousand passengers during the analysis period.
- The top five most popular cities in terms of passenger traffic are Chicago, IL; Los Angeles, CA; Boston, MA; New York City, NY; and Dallas/Fort Worth, TX.

📉 **Business and Operational Implications**

- The top routes like Chicago, IL and Los Angeles, CA **are likely experiencing high demand**, which **could lead to potential issues like overcrowding, delays,** and **capacity constraints** if not managed properly.
- The **less popular routes** such as Belleville, IL. and Bloomington/Normal, IL. **might represent untapped markets** or **niche travel needs**. Conversely, it **could also represent routes that are not profitable** and **should be discontinued**.
•	High-demand routes offer an **opportunity for dynamic pricing to maximize revenue**, while low-demand routes might require **promotional pricing to attract more passengers** or **need to be evaluated for profitability**. 

💡 **Recommendations for Managers**

- **Increase flight frequency** and **assign more staff to the most popular airports** and **routes** to handle the high volume of passengers efficiently and improve customer satisfaction.
- **Conduct a cost-benefit analysis** on the less popular routes or destinations. Determine which ones are still profitable despite low passenger counts and which ones should be discontinued or merged to free up resources.
- For the top-tier routes or destinations, **use dynamic pricing models to adjust ticket prices based on real-time demand and supply**, **competitor prices**, and **consumer behavior**, maximizing revenue. 
- **Analyze the origin and destination data for the most popular routes to identify potential new direct routes** that could serve connected cities, capturing new market share. For example, if many passengers on the Chicago, IL route are connecting to Dallas/Fort Worth, TX, a direct flight to Dallas/Fort Worth, TX might be viable.
- **Invest in amenities and services on the busiest routes** and **at the busiest airports** to **handle the high volume of passengers** and **improve on customer experience**. This could include things like improved lounge or drop and pick passenger services for frequent travelers.

---
---
**Fare vs. Distance Analysis**

The goal of this analysis is to **illustrate the relationship between fare and distance**. Understanding this relationship will **assist in cost optimization, demand prediction, revenue forecasting,** and **resource allocation optimization**. Identifying the most profitable distances enables companies to use their resources more efficiently. For instance, Tahmeed Bus Company may choose to dispatch more buses and drivers to areas with a high volume of passengers or longer trips. Furthermore, for transportation providers, **expenses such as fuel, vehicle maintenance, and driver wages are directly linked to the distance traveled**. Analyzing this relationship aids in setting fares that not only cover these costs but also ensure a healthy profit margin for every trip.

<img width="1365" height="726" alt="image" src="https://github.com/user-attachments/assets/f68ae8e8-6ed4-44d1-b52d-87d4d2a27984" />


🔍 **Key Insights**
- There is **a positive correlation between fare and distance**, meaning that **as the distance traveled (nmiles) increases**, **the fare also tends to increase**.
- For example, in Los Angeles, CA, a distance of 120 miles typically incurs a fare of USD 102. In contrast, a route from Boston, MA, covering 2,705 miles charges an average fare of USD 295.
- **The data points group routes into distinct categories or tiers**. The green cluster represents routes with **shorter distances and lower fares** (typically under $200), while the red cluster indicates **longer-distance routes with higher fares**. The orange area in between denotes **medium-haul routes, which act as a transition zone**.
- Although the overall trend shows an increase in fare with distance, **there is significant variability, particularly for medium and longer distances**.
- For instance, some routes with a distance of around 1,500 miles have fares ranging from approximately $238 to over $249. **This variation suggests inconsistencies in fare pricing, indicating that factors other than distance also influence the final fare**.
- For instance, **competition, airport type, demand and carrier, play a major role**.
- **Variability grows with distance:** Short-haul routes have tighter fare ranges; long-haul routes show wider fare spreads.

📉 **Business and Operational Implications**
- **The scatter plot supports the company's core pricing strategy by effectively linking fare to distance**. This connection is essential for **maintaining a fair and transparent pricing system**.
- However, **the significant variation in fares for similar distances suggests an opportunity for revenue optimization**. The company may be underpricing some long-distance routes, which results in potential lost revenue.
- This **inconsistency in pricing could lead to customer confusion and dissatisfaction**. If two passengers traveling similar distances pay vastly different prices, they might perceive the pricing as arbitrary and unfair. 

💡 **Recommendations for Managers** 
- **Develop a more structured, standardized, and consistent pricing model.** The managers should **consider implementing a tiered system** or **a clear formula where the base fare increases predictably with distance**.
- This approach will **ensure fairness** and **make the pricing more transparent for customers**. 
- Next, **investigate the routes that are outliers in the scatter plot** — specifically, **those routes that have a relatively lower fare compared to their distance**.
- For example, the Miami, FL route, which covers a distance of 2,724 miles, charges $267, whereas the Eagle, Cotomiami, FL route, with a distance of 1,810 miles, charges $430.
- This analysis could **uncover factors influencing pricing beyond distance alone**, such as _demand_, _operational costs for specific routes_, or _competitive pressure_.
- **If there are legitimate reasons for the fare discrepancies** — such as peak travel times, express routes, or routes that involve tolls — **these should be clearly communicated to customers**.
- Providing this transparency can help **mitigate potential negative customer perceptions and dissatisfaction**.


---
---
**Traffic Analysis**

The objective of the analysis is to **classify and identify the busiest airport hubs by both inbound and outbound passenger traffic**. By understanding traffic patterns, Tahmeed Bus Company can **assign fleets and resources to the right routes**. For instance, Tahmeed’s resources, including marketing, bus scheduling, and maintenance, will be concentrated on high-traffic routes. This focus will help **maximize the return on investment**.

**Outbound Traffic**

<img width="1362" height="728" alt="image" src="https://github.com/user-attachments/assets/5c5d3240-7fdb-4d85-bfd6-4ecfc99e1f2e" />


🔍 **Key Insights**
- The analysis shows that **Boston, MA** (with airports BOS, MHT, and PVD) and **Chicago, IL** (with airports MDW and ORD) **are the company's two primary outbound hubs**, **handling more passenger traffic than other airports**.
- These cities have the **highest passenger volumes**, with multiple airports in each contributing significantly to overall traffic.
- In contrast, **some cities**, like Detroit, MI, **have very low outbound passenger counts across their airports** (for example, DET and DTT with counts of 128 and 230, respectively).
- This **suggests that these areas either have low demand for air travel** or that **the company's services in these locations are not attracting enough passengers**.
•	**Within the same city, certain airports outperform others considerably**. For instance, in Dallas/Fort Worth, DFW serves 8,016 passengers, making it a much busier hub than DAL, which serves 6,882 passengers, and FTW, which only serves 7.
This level of detail is **crucial for effective route planning**.

📉 **Business and Operational Implications** 
- The airline's **resources, including marketing, flight scheduling, and maintenance, should be concentrated on high-traffic hubs** such as Boston and Chicago. This focus will help maximize the return on investment.
- **Low-traffic hubs may be operating at a loss** and could be **subsidized by the profitable routes** from the main hubs, which creates an unsustainable business model.
- The analysis indicates **a need for targeted marketing strategies**. The company should **avoid a one-size-fits-all approach**.
- In Boston and Chicago, **marketing efforts should concentrate on maintaining and expanding the existing customer base**, while different strategies are needed in cities like Detroit or Houston to **build awareness and attract new passengers**.

💡 **Recommendations for Managers**
- Managers should **prioritize enhancing the passenger experience at busy hubs** like Boston and Chicago. This could include **increasing the frequency of popular routes** or **adding new ones to meet high demand**.
•	Additionally, managers should **conduct a thorough review of low-performing hubs to identify the reasons for the low traffic**. Is it due to strong competition, or is there simply a lack of interest in airtravel travel in those areas?
•	Managers should **utilize airport-level data to make more informed decisions**. For instance, in Dallas/Fort Worth, they should focus operations at DFW while reassessing the necessity of maintaining services at FTW, considering its very low passenger count.

----
**Inbound Traffic**
<img width="1365" height="728" alt="image" src="https://github.com/user-attachments/assets/b1ae1742-ff66-436b-bc18-3dd09433f6f4" />

🔍 **Key Insights**
- **Washington, D.C. and New York airports collectively received a significant number of inbound passengers**, making these routes **the airline's most important destinations**. In total, these airports handled 68,536 incoming passengers.
- In contrast to the outbound data, which was heavily skewed toward cities like Boston, Chicago, and Dallas, t**he inbound traffic is more evenly distributed.**
- The top cities for inbound passenger counts include Washington, D.C., Dallas/Fort Worth, Houston, Los Angeles, and Miami, all showing strong and consistent numbers.
- Similar to outbound traffic, **certain airports within a city are more popular than others**. For instance, in Los Angeles, LAX airport had the highest number of passengers, with 4,444, followed closely by ONT with 4,405, SNA with 4,401, BUR with 4,322, and LGB with 3,903.

📉 **Business and Operational Implications**
- **The high volume of incoming traffic to cities** such as Washington (31,623), San Francisco (22,096), New York (36,913), and Los Angeles (21,475) **indicates that these are crucial markets for the airline**.
- Therefore, **the airline must ensure that its services to and from these cities are reliable** and of **high quality to retain this customer base**.
- The **significant inbound traffic across multiple cities suggests a healthy and diversified market**. The airline could **consider expanding its services in these areas** or **developing new routes that connect to these major hubs**.
- This data is **vital for operational planning**, particularly **in terms of logistics and scheduling**.
- It enables the company to **prepare for peak arrival times at various airports**, ensuring that they have the necessary fleets and pilots available to efficiently manage passenger loads.

💡 **Recommendations for Managers**
- Given the significant inbound traffic to New York and Washington, **the airline should consider investing in its services to and from these hubs**.
- This investment could involve **adding more frequent flights, enhancing amenities, or launching a targeted marketing campaign** to establish itself as the preferred carrier for flights to and from New York and Washington.
- The analysis identifies specific airports that are priorities for inbound traffic. **The airline should ensure that its routes and services to airports such as LAX and JFK receive top priority**.
- Managers need to **conduct a comparative analysis by examining inbound data alongside analyzed outbound data to gain valuable insights into the relationship between the two**.
- For example, a route with high inbound traffic but low outbound traffic — or vice versa — may indicate **an imbalance that needs to be addressed, potentially through adjustments to pricing strategies or service offerings**.

---
---
**Seasonal Trends**

The goal is to **analyze the total passengers count over time** (from 1993 to 2024) **to identify seasonal peaks and troughs in travel demand**.  By leveraging this information, Tahmeed Bus Company can **optimize operations, pricing, and marketing to maximize revenue and improve service quality**. For example, during predictable peak seasons, such as December holidays, Tahmeed can **implement dynamic pricing to increase fares and maximize profits**. For off-peak seasons, they can **offer promotional discounts to stimulate demand and fill otherwise empty seats**.

<img width="1361" height="727" alt="image" src="https://github.com/user-attachments/assets/61d05b07-30f4-4ebc-9c8d-416dd8c39a27" />

🔍 **Key Insights**
- **There was a significant decline in passenger travel**, dropping from 1,538,138 in 1993 to 397,667 in 1994. This represented **a decrease of over 70% in just one year, which was a major red flag**.
- This decline may have been **influenced by a series of high-profile air disasters** (such as USAIR Flight 427, American Eagle Flight 4184, China Airlines Flight 140, and Aeroflot Flight 593) and **safety concerns in 1994**, which **contributed to a temporary decrease in public confidence and travel demand for airlines.**
- From a peak of 2,710,824 in 2006, **there was a general, though inconsistent, upward and downward trend in passenger travel**. For example, in 2020, the number dropped to 1,131,511, **primarily due to the COVID-19 travel restrictions**.
- However, it **rebounded** to 2,979,369 in 2021 a**fter the easing of those restrictions**. Since the 2020 decline, the industry has recovered to a high of 3,202,075 in 2023.


📉 **Business and Operational Implications**
- **The significant drops in passenger numbers during 1993-1994 and 2019-2020 periods resulted in substantial revenue loss for airlines**. With fewer passengers, their income was greatly affected, **jeopardizing financial stability** and **potentially leading to operational cutbacks**, such as staff reductions.
- Additionally, **the long-term, gradual decline in passenger numbers indicates a shrinking overall demand for air travel**.
- Operating a fleet of aircraft with significantly fewer passengers can lead to **operational inefficiencies** and **poor resource allocation, where costs may exceed revenue.**

💡 **Recommendations for Managers**
- Airline management needs to **conduct a root cause analysis to understand the significant drops in passenger counts in the years 1994, 2001-2003, 2020, and 2024**.
- It's important to identify the major events that occurred during or just before these years, such as new competition, service quality issues, changes in public transportation policies, or global events like a pandemic.
- Additionally, **performing a competitor analysis will help identify the company's competitors, their pricing strategies, and their service offerings**.
- This will **aid in determining whether the decline in passengers is due to a shift in customer preferences or the result of a more competitive market.**
- Based on this analysis, **airlines should consider re-evaluating their current routes to better match demand**. Some routes may need to be **scaled back or discontinued**, while new **routes in high-demand areas could be explored to increase ridership and improve efficiency**.
- To regain customers, **airlines should focus on enhancing the passenger experience**. This may involve **upgrading the fleet**, **ensuring timely arrivals and departures**, and **implementing a customer feedback system to proactively address service issues**.

