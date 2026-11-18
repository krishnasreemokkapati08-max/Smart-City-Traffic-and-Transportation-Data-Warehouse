# Smart-City-Traffic-and-Transportation-Data-Warehouse
This is a Data Warehousing project that collects, integrates, and analyzes city transportation data to identify traffic patterns, congestion hotspots, accident trends, and public transport usage.
Project idea
Build a centralized data warehouse combining:
- 🚗 Traffic volume and congestion data
- 🚦 Traffic signals and road junction data
- 🚌 Public transportation (bus/metro) data
- 🚧 Road construction and maintenance data
- 🚨 Accident and incident records
- ⏰ Time-based traffic patterns
What the project does
The system transforms raw transportation data into structured warehouse data and provides dashboards for analyzing:
- Peak-hour traffic
- Most congested roads and junctions
- Accident-prone locations
- Daily/monthly traffic trends
- Public transport efficiency
- Traffic comparison by area, day, and time
Technologies
- Database: MySQL
- ETL: Python
- Visualization: Power BI / Tableau
- Data Warehouse: Star Schema
- Dataset: Open city traffic / transportation datasets
Star Schema
Fact_Traffic

Traffic volume • Congestion level • Accident count • Travel time

Dim_Time
Hour, day, month

Dim_Location
Area, road, junction

Dim_Transport
Vehicle type, mode

Dim_Weather
Rain, temperature
