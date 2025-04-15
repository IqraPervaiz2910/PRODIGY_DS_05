# PRODIGY_DS_05
## Traffic Accident Data Analysis

### Objective:

To analyze and visualize traffic accident data in the United States, with a focus on identifying patterns related to road conditions, weather, time of day, and geographical hotspots.

### Dataset Used:

US Accidents EDA – Kaggle

Tools & Libraries:

Python

Pandas

NumPy

Matplotlib & Seaborn (for data visualization)

Folium (for interactive map visualizations)

Plotly (optional for interactive charts)

### Steps Involved:

Loaded and explored the US Accident dataset, which includes accident reports across various states with detailed information such as severity, weather, time, and location.

Cleaned the data by handling missing values in columns like Weather_Condition, Start_Time, and Visibility.

Extracted useful features such as:

Hour, Day of Week, and Month from timestamp data.

Grouped accidents by state, time of day, weather, and severity.

### Visualized accident distributions:

Bar plots for accidents per state.

Line plots to identify peak hours and days.

Heatmaps for state-wise accident frequency.

Used Folium to create an interactive map showing accident hotspots based on latitude and longitude.

### Key Insights:

Most accidents occurred during rush hours (7–9 AM & 4–6 PM).

Weather conditions like fog, rain, and snow correlated with increased accident severity.

States with dense populations (e.g., California, Florida, Texas) had higher accident counts.

Accidents were more frequent on weekdays, especially Fridays.

### Skills Applied:

Temporal and geospatial feature engineering

Data aggregation and grouping techniques

Advanced data visualization (static and interactive)

Use of maps to detect geographic trends and hotspots
