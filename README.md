\---

title: "Airline Price Prediction Dashboard - Power BI"
author: "Harsh Arora"
tools: \["Power BI", "Power Query", "DAX", "Excel", "GitHub"]
date: "May 2026"
license: "MIT"
dataset: "Assignment.xlsx"
description: "Interactive Power BI dashboard analyzing Indian airline ticket pricing patterns across routes, airlines, departure times, and travel classes."
---

##### ✈️ Airline Price Prediction Dashboard — Power BI

An interactive Power BI dashboard built to analyze **Indian airline ticket pricing patterns**, including fare trends by airline, route, departure time, number of stops, and travel class.

The dashboard enables travelers and analysts to evaluate **price drivers**, identify **best booking windows**, and explore **route-level fare comparisons** for smarter travel decisions.

\---

##### 🔍 Project Summary

* **Objective:** Provide a unified view of airline fare patterns across Indian routes and airlines.
* **Audience:** Travelers, pricing analysts, revenue managers, and data enthusiasts.
* **Data Source:** Excel dataset — `Assignment.xlsx`
* **Scope:** Covers 6 airlines, 6 cities, economy vs business class, stops, and departure/arrival time segments.

\---

##### 📊 Dashboard Overview

###### 🏠 Home View

!\[Home Overview](dashboard-home-overview.png)

###### 📋 Grid View

!\[Grid Overview](dashboard-grid-overview.png)

\---

##### 🎯 Key Insights

|KPI|Description|
|-|-|
|**Total Flights:** 300K|Total flight records analyzed|
|**Avg Economy Fare:** ₹6,572|Mean economy ticket price|
|**Avg Business Fare:** ₹52,540|Mean business class ticket price|
|**Price Premium (2 Day):** 38%|Surge when booking just 2 days before departure|
|**Busiest Route:** Delhi → Mumbai|Highest traffic route in the dataset|

##### Additional Insights

###### ✈️ **Airline Performance**

* **Vistara** commands the highest average fare at **₹30K**.
* **AirAsia** is the most budget-friendly airline at **₹4K** average.
* **Air India** follows Vistara at **₹24K** average ticket price.

###### 🕐 **Time-Based Pricing**

* **Night departure** flights are the most expensive at **₹23.1K** average.
* **Late Night** is the cheapest departure window at **₹9.3K** average.
* **Evening arrival** flights command the highest fares at **₹23K** average.

###### 🗺️ **Route \& Stops Analysis**

* **Bangalore → Delhi** is the most expensive single route at **₹25,082**.
* Surprisingly, **Non-stop flights** (₹9.4K) are cheaper than **1-stop** (₹22.9K).
* **Business class** accounts for **89%** of average fare value vs Economy at **11%**.

##### \---

##### 🧭 Dashboard Pages

###### **1️⃣ Home Page**

* KPI summary cards (Total Flights, Avg Fares, Price Premium, Busiest Route)
* Avg Ticket Price by Airline (bar chart)
* Price Trend by Days Before Departure (line chart)
* Price by Departure Time
* Price by Arrival Time
* Price Variation by Class (donut chart)
* Price by Number of Stops

###### **2️⃣ Grid Page**

* Route Price Matrix (city-to-city heatmap — Orange = highest, Blue = lowest)
* Departure × Arrival Time cross-tab matrix
* Avg Price by Airline \& Class (grouped bar chart)

###### **3️⃣ Filters Panel**

* Select Airline
* Source City
* Destination City
* Days Before Departure (slider: 1–49)
* Select Class (Economy / Business)
* Select Stops (Non-stop / 1 Stop / 2+ Stops)

##### \---

##### 🛠️ Tools \& Technologies

|Tool / Technology|Purpose|
|-|-|
|**Power BI Desktop**|Dashboard development|
|**Power Query**|ETL: cleaning \& transforming data|
|**DAX (Data Analysis Expressions)**|KPIs \& calculated measures|
|**Excel (Assignment.xlsx)**|Data source|
|**Git \& GitHub**|Version control and portfolio hosting|

\---

##### 🧮 Data Model Overview

**Fact Table:** Flight pricing records  
**Dimensions:**

* Airline
* Source \& Destination City
* Departure \& Arrival Time
* Travel Class (Economy / Business)
* Number of Stops
* Days Before Departure

\---

##### 📂 Repository Structure

```
Airline-Price-Prediction-Dashboard-PowerBI/
│
├── Airline Price Prediction Dashboard.pbix
├── Assignment.xlsx
├── dashboard-home-overview.png
├── dashboard-grid-overview.png
├── LICENSE
└── README.md
```

\---

##### 🚀 How to Use

1. Clone or download this repository:

```bash
   git clone https://github.com/Harsharora-data/Airline-Price-Prediction-Dashboard-PowerBI
   ```

2. Open the Power BI file:
**`Airline Price Prediction Dashboard.pbix`**
3. If prompted for data connection:

   * Go to **Transform Data → Data Source Settings → Change Source**
   * Select your local path for **`Assignment.xlsx`**
4. Refresh the data and explore the dashboard interactively.

\---

##### 📈 Skills Demonstrated

* Power BI dashboard design
* DAX measure creation
* Data modeling
* ETL using Power Query
* Business insights \& storytelling
* Excel-based data preparation
* GitHub documentation \& code management

\---

##### ⚙️ Future Enhancements

* Add **real-time fare tracking** integration
* Add **month-over-month** price trend comparison
* Introduce **price prediction using Power BI AI visuals**
* Add **seat availability** data for a fuller demand picture

\---

##### 👨‍💻 Author

**Harsh Arora**  
📧 harsharora.data@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/harsh-arora-80445167)  
🐙 [GitHub](https://github.com/Harsharora-data)

\---

⭐ **Acknowledgment**  
Dataset used for educational and project demonstration purposes.

\---

##### 📜 License

This project is licensed under the MIT License.  
See the **LICENSE** file for more details.

\---

##### ✅ Metadata Summary

|Field|Details|
|-|-|
|**Project**|Airline Price Prediction Dashboard - Power BI|
|**Author**|Harsh Arora|
|**Created**|May 2026|
|**Tool**|Microsoft Power BI|
|**Category**|Data Visualization / Analytics|
|**License**|MIT|
|**Dataset Source**|Assignment.xlsx|
|**Status**|Completed|



