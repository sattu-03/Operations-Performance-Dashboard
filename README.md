# Operations-Performance-Dashboard
Built an end-to-end logistics operations dashboard in Power BI  analyzing 28K+ orders across 6 hubs, 55 drivers, and 45 vehicles  — uncovering key delay drivers and fleet reliability risks.

As someone building my path in data analytics, I challenged 
myself to go beyond tutorials and build something that 
reflects real-world business work.

📊 SwiftRoute Logistics — Operations Performance Dashboard
Built using Power BI | DAX | Data Modeling

What I built:
→ 4-page interactive Power BI dashboard
   (Overview, Hubs, Drivers, Vehicles)
→ DAX measures for KPIs, Month-over-Month growth,
   and performance tracking across 28,000+ records
→ Data model connecting 4 tables using proper 
   relationships (Orders → Drivers, Hubs, Vehicles)
→ Slicers for dynamic Year & Month filtering

What I learned:

📌 Data Modeling & Table Relationships
   Learned how to join multiple tables using primary 
   and foreign keys — connecting Orders to Drivers, 
   Hubs, and Vehicles to create a unified data model.

📌 Reading a Case Study Like an Analyst
   Learned how to read a business requirement document,
   understand the stakeholder's goals, and translate 
   them into the right visuals and KPIs — not just 
   build charts for the sake of it.

📌 Extracting Meaningful Insights
   Moved beyond surface-level observations to identify 
   patterns that actually matter to the business:

   → Austin Hub carried the lowest on-time delivery 
     rate at 77.9%
   → A single driver accounted for 324 delays — 
     flagged for performance review
   → Vehicles aged 5+ years showed significantly 
     higher breakdown frequency
   → Vans handle 62% of all deliveries, making 
     fleet availability a critical operational risk

📌 Giving Business Recommendations
   Learned that insights alone are not enough.
   Took it a step further by translating each finding 
   into a concrete, actionable recommendation —
   the way a real analyst would present to management.

   → Recommended redistributing orders away from 
     the overloaded Austin Hub
   → Suggested retiring high-breakdown vehicles 
     aged 5+ years with 20+ recorded breakdowns
   → Proposed a performance review process for 
     drivers with consistently high delay counts

This project taught me that a dashboard is not the 
deliverable — the decision it enables is.


The Problem Statement :
SwiftRoute Logistics operates across 6 hubs in Texas with 55 drivers and 45 vehicles. The business needs to identify what's causing delivery delays, which hubs and drivers are underperforming, and whether aging vehicles are a reliability risk — so operations can be improved and customer satisfaction scores can be raised.

Insights :

1. Austin Hub is the weakest hub Austin has the lowest on-time rate at 77.9% — 2.7 points below the top performer El Paso (80.6%). It also processes 4,065 orders with only 220 capacity, meaning it's consistently overloaded.
2. One driver is responsible for a disproportionate number of delays Charles Thompson has 324 delays — nearly 20% more than the #2 driver Karen Rodriguez (274). These two alone account for a significant chunk of total delays and need immediate coaching or reassignment review.
3. Experience does NOT clearly predict performance Looking at the scatter, drivers with 1–2 years experience have ratings ranging from 1 to 5. Same story at 7–10 years. This means experience alone isn't the issue — training quality or route assignment likely matters more.
4. Older vehicles break down significantly more Vehicles aged 5+ years average 18–25 breakdowns, while vehicles under 3 years average only 5–10. FT-010 (5 yrs, 28 breakdowns) and FT-002 (5.2 yrs, 25 breakdowns) are critical risks. 12 out of 45 vehicles are currently in maintenance.
5. Vans carry the entire operation Vans handle 17,480 orders out of 27,979 total — that's 62% of all deliveries. Trucks handle 23%. If van availability drops, operations collapse. Yet breakdowns are spread across all types.
6. Dallas and Houston hubs are overloaded relative to capacity Dallas processed 7,345 orders with a capacity of only 250/day. Houston processed 6,875 with 380/day capacity. These two hubs alone handle 51% of all orders — a single disruption there affects half the network.
7. Road Construction and Vehicle Breakdown are the top 2 delay causes — both at 623 delays These are tied at the top. Road construction is external (hard to control), but vehicle breakdown is 100% internal and preventable with proper maintenance scheduling.


My Suggestion:

FT-002, FT-010, FT-020 continue to break downRetire or remove vehicles with 5+ years and 20+ breakdowns.
 Austin Hub lowest on-time rateRedistribute orders from Austin to Fort Worth or San Antonio.
 Charles Thompson – 324 delaysFlag for performance review, compare route difficulty before concluding





#PowerBI #DataAnalytics #DataModeling #DAX
#SupplyChainAnalytics #LearningInPublic
#AspiringDataAnalyst #Portfolio #BusinessIntelligence




