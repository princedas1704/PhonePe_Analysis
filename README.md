# PhonePe Pulse Data Analysis Dashboard

## Overview
This repository contains a comprehensive Power BI dashboard analyzing the **PhonePe Pulse** dataset. The dashboard provides deep insights into India's digital payment ecosystem from 2018 onwards, highlighting transaction trends, user behaviors, and regional payment adoption across states and districts.

## Data Source
The data utilized in this project is sourced from the official [PhonePe Pulse GitHub Repository](https://github.com/PhonePe/pulse). This open-data initiative by PhonePe provides aggregated and anonymized data on:
- **Transactions:** Count, total amount, and categories (e.g., Peer-to-Peer, Merchant payments, Recharges).
- **Users:** Registered users and app opening statistics.
- **Geographical Data:** State-level, district-level, and postal code-level metrics.

*(Disclaimer: The data represents only PhonePe transactions and users in India within the specified timeframe and is aggregated for privacy).*

## Dashboard Features
This Power BI (`.pbix`) report encompasses several analytical views designed with a modern Fluent2 theme:
1. **Geographical Visualization:** Map-based insights detailing transaction hotspots and user concentration across Indian states and districts.
2. **Transaction Analysis:**
   - State-wise and District-wise volume and value comparisons.
   - Breakdown of transactions by category to understand spending behavior.
   - Trend analysis over years and quarters.
3. **User Demographics & Growth:**
   - Year-over-year registered user growth.
   - Analysis of app engagement metrics.
4. **Top Performers (Scorecards):**
   - Identification of top 10 states, districts, and pin codes based on transaction volume, value, and registered users.

## Prerequisites
To explore and interact with this dashboard, you need:
- **Microsoft Power BI Desktop:** [Download Here](https://powerbi.microsoft.com/desktop/) (Windows only)

## Instructions for Use
1. Clone or download this repository to your local machine.
2. Open the `.pbix` file using Power BI Desktop.
3. The report is divided into multiple pages (accessible via the bottom navigation tabs) focusing on different analytical aspects (e.g., Geo-Map, Transaction Trends, User Insights).
4. Utilize the interactive slicers (Year, Quarter, State) on each page to filter the visuals dynamically.

## Limitations
- The accuracy and completeness of the insights are strictly dependent on the data provided by the PhonePe Pulse repository.
- Geographical mapping represents estimated regions and may not perfectly align with exact political boundaries.
