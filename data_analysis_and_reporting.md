

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


<img width="1363" height="730" alt="image" src="https://github.com/user-attachments/assets/85544a08-df12-42d3-89f6-976c8e430d77" />



🔍 **Key Insights**
- **Profit margins vary significantly across different routes**, even from the same city of origin. For example, the route from Albany, New York, to Washington, D.C., has a profit margin of 72% (0.72), while the Albany to Tampa, Florida route has a profit margin of 42% (0.42). **This variation indicates that not all routes are equally profitable**.
- **Some routes demonstrate particularly high profit margins**, such as Albany to Washington, D.C. (0.72), Albuquerque to Phoenix (94%), and Albuquerque to Las Vegas (89%). **These routes generate strong returns relative to their costs**, especially considering the industry average profit margin of 36%.
- **Certain routes are unprofitable, as evidenced by their negative profit margins**. For instance, the Albany to San Francisco route has a profit margin of -1.65, and the Albuquerque to Miami route shows a profit margin of -1.66. **These figures indicate that these routes incur losses that far exceed their revenues**, presenting a serious business concern that requires the attention of senior management.

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
**Popular Routes Analysis**

Popular route analysis provides transportation and logistics businesses with crucial data to **optimize operational efficiency**, **reduce costs**, and **improve customer satisfaction**. By understanding which routes are used most often, and the factors affecting them, Tahmeed Bus Company can make smarter, data-driven decisions that impact their bottom line and competitiveness. For example, if many passengers on the Nairobi to Dar-es-Salaam route are connecting to Arusha, a direct bus to Arusha might be viable.


<img width="1365" height="727" alt="image" src="https://github.com/user-attachments/assets/87b9fbee-f571-433d-8d8d-65e7e2a14999" />

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

---
**Fare vs. Distance Analysis**

The goal of this analysis is to **illustrate the relationship between fare and distance**. Understanding this relationship will **assist in cost optimization, demand prediction, revenue forecasting,** and **resource allocation optimization**. For example, identifying the most profitable distances enables companies to use their resources more efficiently. For instance, Tahmeed Bus Company may choose to dispatch more buses and drivers to areas with a high volume of passengers or longer trips. Furthermore, for transportation providers, **expenses such as fuel, vehicle maintenance, and driver wages are directly linked to the distance traveled**. Analyzing this relationship aids in setting fares that not only cover these costs but also ensure a healthy profit margin for every trip.

