***Air Quality Analysis - Power BI Project***

***Project Overview***
This project analyzes air quality data across various cities in India from 2015 to 2020. The analysis examines key pollutants, Air Quality Index (AQI) values, seasonal variations, and pollution trends using Power BI dashboards. The goal is to provide actionable insights that can aid policymakers, environmental agencies, and urban planners in mitigating air pollution and improving public health.

***Dataset Details***
- **Source**: Kaggle ("Clean Air - India’s Air Quality" dataset)
- **Records**: 25,555 rows, 16 columns
- **Timeframe**: 2015 - 2020
- **Cities Covered**: 21 major cities in India
- **Key Attributes**:
  - City: Location of air quality measurements
  - Date: Record timestamp
  - Pollutants: PM2.5, PM10, NO, NO2, NOx, CO, SO2, O3
  - AQI: Air Quality Index value
  - AQI_Bucket: Categorization (Good, Moderate, Poor, etc.)

***Objectives***
- **Monitor air quality trends** across cities and regions.
- **Identify pollution hotspots** and high-risk periods.
- **Analyze seasonal variations** in pollutant concentrations.
- **Develop Power BI dashboards** for interactive data visualization.
- **Support policy-making efforts** with data-driven insights.

***Data Preparation***
- **Handling Missing Values**:
  - Mean/median imputation for PM2.5, PM10
  - Forward-fill and backward-fill for time-series gaps
  - Mode imputation for categorical AQI_Bucket values
- **Data Cleaning**:
  - Standardization of city names
  - Verification of pollutant measurement units
  - Removal of outliers using statistical analysis
- **Transformations**:
  - Extraction of Year, Month, and Day from Date
  - Regional categorization (Northern, Southern, Coastal)
  - Calculation of average pollutant levels

***Power BI Dashboard Features***
- **Interactive Filters**:
  - City-wise, year-wise, and pollutant-wise filtering
- **Visualizations**:
  - **Bar Charts**: AQI severity and pollutant levels per city
  - **Line Graphs**: Seasonal and yearly trends
  - **Pie Charts**: AQI distribution across regions
  - **Maps**: Geographic visualization of AQI buckets
- **Key Insights**:
  - Northern cities exhibit higher AQI values than southern cities.
  - PM2.5 and PM10 are primary contributors to "Severe" AQI levels.
  - Higher pollution levels are observed in winter due to temperature inversions.
  - Coastal cities show higher PM10 due to natural factors like sea salt.

***Findings & Recommendations***
- **Delhi, Ahmedabad, and Kolkata** exhibit consistently high AQI levels.
- **Bangalore and Chennai** have moderate pollution but require monitoring.
- **Stronger emission regulations** are needed for high-risk regions.
- **Public awareness campaigns** can help in reducing pollution sources.
- **Urban planning strategies** like green zones and reduced traffic congestion can improve air quality.

***Technologies Used***
- **Power BI** for dashboard creation and data visualization
- **Python & Pandas** for data cleaning and preprocessing
- **Excel/CSV** as primary data source format

***Usage Instructions***
1. **Open the Power BI file** (PBIX format) in Microsoft Power BI Desktop.
2. **Interact with the filters** to explore trends by city, year, or pollutant.
3. **Analyze AQI severity levels** to identify pollution hotspots.
4. **Use insights for decision-making** in environmental policies.

***Future Enhancements***
- **Real-time data integration** using APIs for live air quality tracking.
- **Machine learning models** for AQI forecasting.
- **Mobile-friendly dashboards** for easy accessibility.
- **Expanded geographic coverage** beyond India.

***Contributors***
- **Varshini S H**
- **Mohammed Aadhil A**
- **Sasvath K R**

***Contact***
For any queries, please reach out to the project contributors.

---
This README serves as documentation for the Power BI-based Air Quality Analysis project, summarizing key insights, data sources, methodology, and recommendations for future improvements.

