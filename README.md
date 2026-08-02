# England Historical Property Price Analytics (1995–Present)
Automated Lakehouse pipeline ingesting UK Land Registry data using Medallion Fabric, PySpark transformations, and central error alerting and automated Power BI.

![England Historical Property Price Dashboard](/captures/property_price_dashboard11.PNG)

## Overview
This project models historical transaction logs to evaluate long-term real estate price trends:
**Longitudinal Trends:** Property price trajectory vs. total sales volume from 1995 onward.
**Geographic Intensity:** Map analysis showing median property price density across English counties.
**Property Dynamics:** Market share by property type and build condition.

## Data Engineering & Pipeline Orchestration
The ingestion, transformation, and semantic refresh are fully orchestrated using an automated Fabric pipeline:

![Orchestration Pipeline](/captures/Orchestration_Pipeline.PNG)

## Data Architecture & Star Schema Model
The underlying data model follows a **Star Schema** to ensure fast DAX performance and clear filter propagation across visuals.

![Semantic Model Star Schema](/captures/Semantic_Model_EnPP.PNG)

## Analytical: Density, Supply Friction, and Market Segmentation
![England Historical Property Price Dashboard](/captures/property_price_dashboard2.PNG)

The historical data from 1995 to 2026 illustrates how internal migration toward high opportunity economic hubs shapes property dynamics across English counties. Greater London (£69.79bn total value) and the surrounding Home Counties like Surrey (£46.93bn) and Hertfordshire (£31.52bn) show an extreme concentration of market capital and sustained price appreciation compared to northern regions like West Yorkshire (£15.40bn) or Lancashire (£13.99bn). This relentless demand driven by urban density highlights the natural efficiency of human agglomeration, concentrating energy consumption and economic output. However, as shown in the long-term trend line, while total transaction volume has experienced sharp cyclical drops, median prices have maintained a steady upward trajectory, proving that underlying regional demand consistently outpaces available property supply.

I would say that when rapid inward migration collides with rigid structural constraints on housing supply, urban land values skyrocket. As demand concentrates heavily within metropolitan zones, property prices for both residential and commercial real estate escalate sharply, transforming geographic efficiency into an acute affordability crisis for working populations. This supply and demand disparity is further exacerbated by a shifting social consciousness that increasingly prioritizes risk aversion, strict safety guarantees, and protection against market cycles over rapid development. While well intentioned, public sentiment often demands stringent regulatory overlays, expanded zoning restrictions, and tenant protection mandates aimed at shielding the vulnerable. In practice, these policies frequently destroy the financial incentives for private capital to construct new housing and commercial spaces by raising costs and capping potential returns.

<br><br>
---
**License Notice**
>Under the Open Government Licence, the data is freely available for commercial and non-commercial reuse purposes. The users of the data have an obligation, under the Open Government Licence, to ensure that their use of the data does not breach the Data Protection Act 2018 or the Privacy and Electronic Communication (EC Directive) Regulations 2003. At the moment, we do not intend to impose any more restrictions on the use of the data for direct marketing purpose.<
