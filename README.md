# Tableau Web Data Connector (WDC) Framework

This repository provides a **Web Data Connector (WDC) framework** for **Tableau Public** that enables fetching data directly from APIs. It is designed to make it easier to build **real-time, updatable dashboards** with any external data source that exposes an API in JSON, CSV, or similar formats.

## Features
- Connect Tableau Public to any API with minimal configuration.
- Support for JSON and CSV endpoints.
- Automatically refresh data when the dashboard is opened or updated.
- Ready for time series, metrics, or any structured data visualization.
- Easy to extend for new API endpoints or multiple data sources.

## How to Use
1. Host your WDC HTML file on a public HTTPS server (e.g., GitHub Pages, Netlify, Vercel).
2. Open Tableau Public.
3. Go to **Connect → To a Server → Web Data Connector**.
4. Enter the URL of your hosted WDC file.
5. Click the **Connect** button on the webpage to load data.
6. Build visualizations and dashboards as usual.

## Customization
- Modify the WDC JavaScript to point to different API endpoints.
- Map JSON or CSV fields to Tableau columns.
- Add new schemas to support multiple datasets in the same WDC.

## Notes
- Tableau Public requires the WDC to be hosted via HTTPS.
- This framework is general-purpose and can be reused for any API project.
- Ideal for live dashboards, financial data, social metrics, IoT feeds, and more.

## Credits
- Tableau Web Data Connector SDK: [https://tableau.github.io/webdataconnector/](https://tableau.github.io/webdataconnector/)
