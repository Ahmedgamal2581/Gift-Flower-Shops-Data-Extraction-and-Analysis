# Gift & Flower Shops Data Extraction and Analysis

## 📖 Project Overview
This project showcases a comprehensive workflow for extracting, analyzing, and visualizing data for gift and flower shops located in Riyadh. The process involved leveraging Python to connect with Google Maps, extracting shop-specific data, creating an interactive dashboard for performance analysis, and exporting the data to KML format for integration with Google Earth.

This project highlights practical applications of data extraction and geospatial visualization, catering to client-specific needs for business decision-making.

---

## 🔍 Features and Workflow

### 1. **Data Extraction**
- Extracted data points using Python and Google Maps integration:
  - **Shop Name**: The name of each shop.
  - **Address**: Full address including street, city, and region.
  - **Phone Number**: Contact information for each shop.
  - **Website**: URL of the shop’s website if available.
  - **Ratings**: Average customer ratings for the shop.
  - **Geographical Coordinates**: Latitude and Longitude for mapping purposes.

### 2. **Data Storage**
- The extracted data was organized and stored in an Excel file (`shops_data.xlsx`) for further analysis.
- Data fields include structured columns for better readability and integration.

### 3. **Interactive Dashboard**
- Built a dashboard to analyze key performance indicators (KPIs), such as:
  - Distribution of shops across different regions.
  - Comparison of customer ratings.
  - Shop density and geographic trends.
- The dashboard provides actionable insights to optimize business strategies.

### 4. **File Conversion for Google Earth**
- Converted the Excel file into KMZ format to enable:
  - Visualizing shop locations directly on Google Earth.
  - Adding layers of data for more dynamic analysis.

### 5. **Visualization and Insights**
- Generated maps and screenshots of the extracted data points.
- The visualizations assist in identifying key areas of operation and potential opportunities.

---

## 🗂️ Project Structure
```
project-root/
|-- data/
|   |-- shops_data.xlsx       # Extracted data in Excel format
|
|-- output/
|   |-- shops_data.kmz        # KML file for Google Earth visualization
|
|-- screenshots/
|   |-- data_extraction.png   # Screenshot of data extraction process
|   |-- dashboard.png         # Screenshot of the dashboard
|   |-- google_earth.png      # Screenshot from Google Earth
|
|-- dashboard/
|   |-- dashboard_file        # File for the interactive dashboard (e.g., Excel, Power BI)
|
|-- scripts/
|   |-- data_extraction.py    # Python script for data extraction
|
|-- README.md                 # Detailed documentation for the project
```

---

## 🚀 Technologies Used
- **Python**: For automating data extraction and processing.
- **Google Maps API**: For fetching shop details and coordinates.
- **Excel**: For data organization and dashboard creation.
- **Power BI/Excel Dashboards**: For KPI visualization.
- **Google Earth**: For geospatial analysis using the KML file format.

---



## 🎯 Key Insights
- **Data Accessibility**: The extracted dataset provides a comprehensive overview of gift and flower shops in Riyadh, enabling better business insights.
- **Performance Visualization**: The dashboard offers actionable KPIs, allowing businesses to identify trends and improve decision-making.
- **Geospatial Analysis**: The KMZ file enables visual exploration of shop distribution across the city, identifying high-potential areas.


