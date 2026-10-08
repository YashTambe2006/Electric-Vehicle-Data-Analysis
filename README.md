# Electric Vehicle Data Analysis – Tableau

📊 Project Overview

This project presents an interactive Tableau dashboard for analyzing electric vehicle data and identifying important patterns across vehicle types, manufacturers, models, model years, geographic distribution, electric range, and CAFV eligibility.

The dashboard transforms vehicle-level data into an interactive business intelligence report that provides both high-level KPIs and detailed vehicle-level analysis.

The project demonstrates practical skills in data analysis, data visualization, Tableau dashboard development, calculated fields, interactive filtering, geographic analysis, and analytical storytelling.


📸 Dashboard Preview

Electric Vehicle Data Analysis Tableau Dashboard


🎯 Project Objectives

The main objectives of this project are to:

- Analyze the overall electric vehicle population
- Compare Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs)
- Analyze EV growth across different model years
- Identify leading electric vehicle manufacturers
- Analyze the geographic distribution of electric vehicles across states
- Calculate and analyze average electric driving range
- Analyze Clean Alternative Fuel Vehicle (CAFV) eligibility
- Identify the most represented EV models
- Compare individual vehicle models and manufacturers
- Build an interactive dashboard for exploratory data analysis


📁 Dataset

The project uses a vehicle-level electric vehicle population dataset containing information related to vehicle specifications, manufacturers, models, model years, location, electric range, EV type, CAFV eligibility, and other attributes.

The dataset contains multiple dimensions that allow analysis from different perspectives, including:

- Vehicle
- Manufacturer
- Model
- Model Year
- Electric Vehicle Type
- Electric Range
- CAFV Eligibility
- State
- City
- County
- Electric Utility
- Geographic Information


Key Dataset Columns

| Column | Description |
|---|---|
| VIN (1-10) | First 10 characters of the vehicle identification number |
| County | County associated with the vehicle |
| City | City associated with the vehicle |
| State | State associated with the vehicle |
| Postal Code | Postal/ZIP code of the vehicle |
| Model Year | Model year of the vehicle |
| Make | Vehicle manufacturer |
| Model | Vehicle model |
| Electric Vehicle Type | Classification of the vehicle as BEV or PHEV |
| CAFV Eligibility | Clean Alternative Fuel Vehicle eligibility status |
| Electric Range | Estimated electric driving range in miles |
| Base MSRP | Base manufacturer's suggested retail price |
| Legislative District | Legislative district associated with the vehicle |
| DOL Vehicle ID | Vehicle identification record maintained by the Department of Licensing |
| Vehicle Location | Geographic location of the vehicle |
| Electric Utility | Electric utility associated with the vehicle location |
| 2020 Census Tract | Census tract associated with the vehicle |


🛠️ Tools & Technologies

- Tableau Desktop
- Tableau Public
- Data Visualization
- Exploratory Data Analysis
- Calculated Fields
- Data Aggregation
- Geographic Visualization
- Interactive Dashboard Design
- CSV Dataset


🔄 Project Workflow

Raw EV Dataset
     ↓
Data Understanding
     ↓
Data Cleaning & Preparation
     ↓
Data Exploration
     ↓
Calculated Fields & Aggregations
     ↓
Tableau Visualizations
     ↓
Dashboard Design
     ↓
Interactive Filters
     ↓
Final EV Analytics Dashboard


🧹 Data Preparation

The dataset was prepared and analyzed before building the final Tableau dashboard.

The preparation and analysis process included:

- Understanding the dataset structure
- Reviewing available dimensions and measures
- Identifying relevant vehicle attributes
- Handling and evaluating missing or unknown values
- Preparing categorical fields for analysis
- Validating vehicle type classifications
- Preparing geographic fields for map visualization
- Creating aggregated measures
- Preparing fields required for dashboard filtering
- Organizing data for trend, manufacturer, model, and eligibility analysis

The prepared dataset was then used in Tableau to create the interactive visualizations and dashboard.


📐 Key Calculated Metrics

The dashboard uses calculated and aggregated metrics to provide meaningful analytical insights.

### Total Vehicles

Counts the number of vehicle records represented in the dashboard.

### Average Electric Range

Calculates the average electric driving range across the analyzed vehicle population.

### BEV Vehicles

Identifies the number of Battery Electric Vehicles represented in the dataset.

### PHEV Vehicles

Identifies the number of Plug-in Hybrid Electric Vehicles represented in the dataset.

### BEV Percentage

Calculates the percentage contribution of BEVs to the overall vehicle population.

### PHEV Percentage

Calculates the percentage contribution of PHEVs to the overall vehicle population.

### Vehicle Count by Model Year

Aggregates vehicles by model year to analyze EV population trends over time.

### Vehicle Count by Manufacturer

Aggregates vehicle records by manufacturer to identify leading EV brands.

### Vehicle Count by State

Aggregates vehicle records geographically to analyze state-level EV distribution.


📊 Dashboard Features

The dashboard is designed as an interactive single-page analytical report.

### KPI Cards

The dashboard provides the following high-level metrics:

- Total Vehicles
- Average Electric Range
- Total BEV Vehicles
- Total PHEV Vehicles
- BEV Percentage
- PHEV Percentage


### Interactive Filters

Users can dynamically filter the dashboard using:

- CAFV Eligibility
- Electric Vehicle Type
- Model
- State

These filters allow users to explore specific subsets of the EV population and analyze the dashboard from different perspectives.


### Visualizations

The dashboard includes:

- Total Vehicles by Model Year
- Total Vehicles by State
- Top 10 EV Manufacturers
- Total Vehicles by CAFV Eligibility
- Total Vehicles by Model
- BEV vs PHEV distribution
- Manufacturer contribution analysis
- Model-level vehicle distribution
- Geographic EV distribution


📈 Dashboard Analysis

### Total Vehicles by Model Year

A time-series visualization shows how the EV population changes across different model years.

The analysis helps identify periods of increasing EV adoption and highlights the strong growth observed in more recent model years.


### Total Vehicles by State

A geographic map visualizes the distribution of electric vehicles across U.S. states.

This helps identify regions with higher concentrations of electric vehicles and provides a geographic perspective on EV adoption.


### Top 10 EV Manufacturers

The manufacturer analysis ranks the leading vehicle manufacturers based on the number of vehicles represented in the dataset.

The dashboard includes manufacturers such as:

- Tesla
- Nissan
- Chevrolet
- Ford
- BMW
- Kia
- Toyota
- Volkswagen
- Volvo
- Jeep


### CAFV Eligibility Analysis

The dashboard categorizes vehicles based on Clean Alternative Fuel Vehicle eligibility.

The analysis includes:

- CAFV Eligible
- CAFV Not Eligible
- CAFV Eligibility Unknown

This provides an overview of the distribution of vehicles across different eligibility categories.


### Total Vehicles by Model

A detailed model-level table provides:

- Vehicle Model
- Manufacturer
- Electric Vehicle Type
- Total Vehicles
- Percentage of Total Vehicles

This enables detailed comparison between individual EV models.


🔍 Key Insights

The dashboard highlights several important patterns in the analyzed EV population:

- BEVs represent the majority of vehicles compared with PHEVs.
- The dashboard reports approximately 77.8% BEVs and 22.2% PHEVs.
- The average electric range across the displayed vehicle population is approximately 64.24 miles.
- EV representation increases significantly across recent model years.
- Tesla has the highest representation among the manufacturers shown in the Top 10 analysis.
- EV distribution varies significantly across different U.S. states.
- A considerable portion of vehicles falls under the CAFV eligibility unknown category.
- A small number of manufacturers account for a large share of the vehicles represented in the dataset.
- The model-level analysis shows that a limited number of EV models contribute a significant portion of the total vehicle population.


🎛️ Interactive Analysis

The dashboard allows users to perform interactive exploratory analysis.

For example, users can:

- Select a specific state and analyze its EV population.
- Compare BEVs and PHEVs.
- Analyze a specific manufacturer.
- Explore individual EV models.
- Filter vehicles based on CAFV eligibility.
- Examine EV population trends across model years.
- Compare manufacturer and model-level contributions.

The dashboard automatically updates the visualizations based on the selected filters.


📊 Dashboard KPIs

The current dashboard displays:

- Total Vehicles: 159,396
- Average Electric Range: 64.24 Miles
- Total BEV Vehicles: 124,089
- Total PHEV Vehicles: 35,307
- BEV Share: 77.8%
- PHEV Share: 22.2%


📂 Project Files

| File | Description |
|---|---|
| `Electric_Vehicle_Data_Analysis.twbx` | Tableau packaged workbook containing the dashboard |
| `Electric_Vehicle_Population_Data.csv` | Dataset used for analysis |
| `Dashboard.png` | Dashboard preview image |
| `README.md` | Project documentation |


🚀 Skills Demonstrated

This project demonstrates practical experience with:

- Tableau
- Data Visualization
- Exploratory Data Analysis
- Data Cleaning
- Data Preparation
- Calculated Fields
- Data Aggregation
- KPI Development
- Interactive Dashboard Development
- Geographic Visualization
- Trend Analysis
- Comparative Analysis
- Business Intelligence
- Data Storytelling
- Dashboard UI/UX Design
- Analytical Thinking


💡 Business & Analytical Applications

The dashboard can be used to support analysis related to:

- EV market research
- Automotive industry analysis
- EV adoption trends
- Manufacturer comparison
- Geographic EV distribution
- Clean vehicle eligibility analysis
- Vehicle model comparison
- Electric mobility research
- Business intelligence reporting


🔮 Future Enhancements

Potential improvements to the project include:

- Year-over-year EV growth analysis
- EV adoption growth rate
- Average electric range by manufacturer
- Average range comparison between BEVs and PHEVs
- Price vs electric range analysis
- Manufacturer market-share trends
- State-level EV growth analysis
- EV adoption forecasting
- Predictive analysis using machine learning
- Population-normalized state-level EV adoption
- Additional geographic and demographic analysis
- Advanced Tableau parameters and calculated fields


⚠️ Limitations

The analysis should be interpreted within the context of the available dataset.

- The dataset represents the vehicle population captured in the source data and may not represent the complete U.S. EV market.
- CAFV eligibility contains unknown classifications for some vehicles.
- Electric range values represent reported/recorded values and may differ from real-world driving conditions.
- The dataset includes both BEVs and PHEVs, which have different electric driving characteristics.
- The dashboard is primarily focused on descriptive and exploratory analysis rather than predictive modeling.


👤 Author

Yash Tambe

B.Tech – Artificial Intelligence & Data Science

Interested in:

Data Analytics | Data Science | Machine Learning | Business Intelligence | Data Visualization


⭐ Project Highlights

- 159K+ vehicle-level records in the source dataset
- Interactive Tableau dashboard
- 159,396 vehicles represented in the dashboard
- BEV vs PHEV analysis
- 77.8% BEV and 22.2% PHEV distribution
- Average electric range analysis
- Model-year trend analysis
- State-level geographic analysis
- Top 10 manufacturer analysis
- CAFV eligibility analysis
- Vehicle model-level analysis
- Interactive dashboard filters
- Tableau calculated metrics
- Business intelligence dashboard design
- Data storytelling and exploratory analysis
