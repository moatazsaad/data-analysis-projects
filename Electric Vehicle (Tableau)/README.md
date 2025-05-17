# Electric Vehicle Analysis Dashboard

## Dataset Overview

This project uses data sourced from [Data.gov](https://catalog.data.gov/dataset/), containing detailed electric vehicle registration information. Key dataset columns include:

- **VIN (1-10):** First 10 characters of the Vehicle Identification Number  
- **County, City, State:** Vehicle registration location  
- **Postal Code:** Postal code of registration  
- **Model Year:** Vehicle manufacturing year  
- **Make, Model:** Vehicle manufacturer and model  
- **Electric Vehicle Type:** Classification of the electric vehicle  
- **Clean Alternative Fuel Vehicle (CAFV) Eligibility:** Program eligibility status  
- **Electric Range:** Driving range of the vehicle  
- **Base MSRP:** Manufacturer’s Suggested Retail Price  
- **Legislative District, 2020 Census Tract:** Geographical identifiers  
- **DOL Vehicle ID:** Department of Licensing Vehicle ID  
- **Vehicle Location:** Physical location details  
- **Electric Utility:** Associated electric utility provider  

## Project Overview

An interactive Tableau dashboard was developed to provide insights into electric vehicle ownership patterns. Key features include:

- Built interactive Tableau dashboards visualizing trends in vehicle model years, geographic distribution by postal code, and top counties by vehicle ownership.
- Created calculated fields, applied filters (e.g., Washington-only data), and used hierarchies for drill-down analysis (Make → Model).
- Used bar charts, stacked bar charts, and geographic maps with custom formatting and user-driven filters.
