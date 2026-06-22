# 📦 Shipment Analytics Dashboard

An interactive **Shipment Analytics Dashboard** built to visualize and analyze global logistics operations. This dashboard provides actionable insights into shipment volumes, carrier performance, destination trends, and shipment weights using intuitive charts and KPI metrics.

## 📌 Project Overview

The Shipment Analytics Dashboard helps logistics and supply chain teams monitor shipment activities across multiple countries and carriers. It converts raw shipment data into meaningful visual insights, enabling faster and data-driven decision-making.

The dashboard tracks Air Waybills (AWBs), shipment weights, carrier market share, destination performance, and country-wise shipment trends in a single interface.

## 🎯 Objectives

* Monitor global shipment performance.
* Analyze carrier utilization and dependency.
* Track destination-wise shipment trends.
* Compare shipment weights across countries.
* Support logistics decision-making.
* Improve operational visibility.

## ✨ Features

### 📊 KPI Metrics

* Total AWBs: **2,176**
* Total Weight: **9,860 kg**
* Average Weight per AWB: **4.5 kg**
* Top Carrier: **DHL**
* Top Destination: **United States**

### 🌍 Shipment Analysis

* Country-wise shipment distribution
* Top destination analysis
* Shipment volume tracking

### 🚚 Carrier Analysis

* Carrier market share
* Carrier-wise shipment totals
* Carrier contribution comparison

### 📈 Data Visualization

* Bar Charts
* Doughnut Charts
* Stacked Bar Charts
* Scatter Plots
* Performance Tables

## 🛠️ Tech Stack

| Technology       | Purpose              |
| ---------------- | -------------------- |
| React.js         | Frontend Development |
| JavaScript (ES6) | Application Logic    |
| HTML5            | Structure            |
| CSS3             | Styling              |
| Chart.js         | Data Visualization   |
| React Icons      | Icons                |
| GitHub           | Version Control      |

## 📂 Project Structure

text
shipment-analytics-dashboard/

├── public/

├── src/

│ ├── components/
│ │ ├── Dashboard.jsx
│ │ ├── KPIcards.jsx
│ │ ├── ShipmentsByCountry.jsx
│ │ ├── CarrierShare.jsx
│ │ ├── CarrierTotals.jsx
│ │ ├── WeightDestination.jsx
│ │ ├── CarrierBreakdown.jsx
│ │ ├── WeightVsAWB.jsx
│ │ └── CountryTable.jsx

│ ├── data/
│ │ └── shipmentData.js

│ ├── App.js

│ ├── App.css

│ └── index.js

├── package.json

├── README.md

└── LICENSE

## 📊 Dashboard Components

### 1️⃣ KPI Cards

Displays:

* Total AWBs
* Total Weight
* Top Carrier
* Top Destination

### 2️⃣ Shipments by Country

Shows shipment distribution across:

* United States
* United Kingdom
* Germany
* UAE
* Canada
* Australia
* Singapore
* Netherlands
* France
* Japan

### 3️⃣ Carrier Share

Displays carrier market share:

* DHL: 39%
* FedEx: 21%
* UPS: 9%
* Other: 31%

### 4️⃣ Carrier Totals

Shows the total number of shipments handled by each carrier.

### 5️⃣ Weight by Destination

Compares shipment weights across countries.

### 6️⃣ Carrier Breakdown

Stacked comparison of all carriers by destination.

### 7️⃣ Weight vs AWBs

Scatter plot showing the correlation between shipment count and shipment weight.

### 8️⃣ Full Country Breakdown

Detailed country-wise shipment analysis.

## 📈 Key Insights

* United States is the top destination.
* DHL is the leading carrier.
* Shipment volume is directly related to shipment weight.
* Germany, UK, and UAE are key logistics markets.
* Data visualization improves operational monitoring.

## 💼 Business Benefits

This dashboard helps organizations:

* Improve shipment planning
* Optimize transportation strategies
* Reduce carrier dependency risks
* Enhance operational efficiency
* Support strategic decision-making
* Increase supply chain visibility

## 🚀 Future Enhancements

* Real-time shipment tracking
* API integration
* Advanced filtering options
* Predictive analytics
* Automated reporting
* Interactive maps

## 👩‍💻 Author

**Shambhavi Tripathi**

**Project Type:** Logistics & Supply Chain Analytics Dashboard

**Organization:** Airvault Express & Logistics (Internship Project)

## 📄 License

This project is intended for educational, internship, and portfolio purposes.
