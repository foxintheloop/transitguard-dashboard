# TransitGuard Dashboard

**Real-time safety analytics for Chicago CTA operations.**

Web dashboard for visualizing crime hotspots, ridership patterns, and predictive safety alerts across the Chicago Transit Authority system.

![Dashboard Screenshot](assets/dashboard-screenshot.png)

## Features

- **Live safety metrics** - Incident counts, trends, and hotspot maps
- **Predictive alerts** - XGBoost-powered risk forecasting by station and time
- **Spatial clustering** - DBSCAN-identified high-risk zones
- **Historical analysis** - 10 years of CTA crime data (2014-2024)

## Part of TransitGuard

This dashboard is one component of the TransitGuard platform. See also:

- [TransitGuard Mobile App](https://github.com/foxintheloop/transitguard-app) - SMS/push alerts for riders
- [TransitGuardRAG](https://github.com/foxintheloop/TransitGuardRAG) - GenAI RAG API chatbot backend
- [TransitGuard (main)](https://github.com/foxintheloop/transitguard) - Project overview and documentation

## Getting Started

### Prerequisites

- Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

### Installation

Follow these steps to get the project running locally:

```sh
# Step 1: Clone the repository
git clone <REPOSITORY_URL>

# Step 2: Navigate to the project directory
cd transitguard-dashboard

# Step 3: Install dependencies
npm i

# Step 4: Start the development server
npm run dev
```

## Data

All data sourced from the [City of Chicago Data Portal](https://data.cityofchicago.org/):
- CTA crime incidents (50K+ records)
- Ridership data (L stations, bus routes)
- 311 reports (streetlight outages, graffiti)

## Stack

`Python` `Streamlit` `Pandas` `Folium` `Plotly` `scikit-learn` `XGBoost`

## Team

Northwestern University MSDS 498 Capstone (2025)

## License

MIT
