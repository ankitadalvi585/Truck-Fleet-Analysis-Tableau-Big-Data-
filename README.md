### 🚛 Truck Fleet Analysis using Tableau (Big Data)
This project focuses on analyzing truck driver's risk factors for a fictional national trucking company, AZ National Trucking (ANT), to enhance safety and compliance. The primary goal is to identify high-risk drivers based on factors such as speeding, lane departures, and unsafe following. Using Hadoop tools for data processing and Tableau for visualizations, the project analyzes driver behavior and truck data to mitigate risks associated with trucking accidents.

#### 🔍Key Steps:

Data Collection: Geographic data (latitude, longitude, city, state) and truck fleet data (mileage, fuel consumption, events, etc.) are gathered from public resources. This data is enriched with risk factors such as speed and unsafe driving practices.

Data Processing: The data is processed using the Hadoop ecosystem (HDFS, Hive). Key tables and data structures are created to store event and driver information. A Hive table is used to ingest the data, and geographic data is loaded into Hadoop’s file system.

Analysis: Risk factors are calculated for each driver using PigScript. Drivers with a risk factor exceeding a threshold of 7 are flagged as high-risk. Tableau is used to visualize the data and create risk profiles for individual drivers and truck models. The analysis identifies high-risk behaviors such as frequent lane departures and overspeeding, which are concentrated in regions like Hollister and other cities with high accident rates.

#### 📈Results:

Driver A97 is identified as the riskiest driver, involved in multiple speeding and lane departure incidents.
![image](https://github.com/user-attachments/assets/8a5f193a-6e7a-44a9-9311-7b2fcd4be0e2)

Truck Models: The Oshkosh model has the highest risk factor, while Ford trucks exhibit the most frequent incidents.
![image](https://github.com/user-attachments/assets/11489cb3-89af-4b80-a90d-a5c30278abae)

Risk Patterns: Lane Departure and unsafe following distance are the most common high-risk events.
![image](https://github.com/user-attachments/assets/1a5b22e2-ce4b-43b8-a241-89b45f0e0fb8)

Geographic Insights: Cities like Hollister have the highest risk, with lane departures being the most common cause of incidents.
![image](https://github.com/user-attachments/assets/4a01baae-b5ca-4eee-9581-26cd91aec445)

#### 📊Technologies Used:

Hadoop Ecosystem: For data storage and processing.

HDFS: Storing large-scale truck and driver data.

Hive: Querying and managing datasets.

Tableau: For data visualization, presenting risk factors and analysis.

JDBC/ODBC Drivers: For connecting Hadoop data with Tableau for analytics.

#### 💡Advantages:

Data-Driven Insights: The project provides critical insights into driver behavior and vehicle performance, allowing the company to make data-driven decisions on risk mitigation.

Improved Safety: By identifying risky drivers and trucks, the company can focus on training and policy improvements, which helps reduce accidents and improve safety.

Operational Efficiency: With real-time tracking and risk assessments, the company optimizes driver allocation, reduces insurance costs, and enhances compliance with regulatory standards.

This project demonstrates how big data technologies are used to address real-world safety concerns in the trucking industry and showcases the potential of data to improve operational outcomes.
