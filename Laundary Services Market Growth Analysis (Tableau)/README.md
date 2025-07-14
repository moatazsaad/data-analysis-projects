# WeWashYouSleep: Laundry Pick-Up Service Analysis  

## Overview  

WeWashYouSleep is a small laundry pick-up service startup facing strong competition from major players. To gain an edge, the company is focusing on smaller cities. Currently, it operates in **140 locations** and recently expanded to **190 more cities**, spanning across **two distinct sales regions**.  

📊 **Link to Dashboard:** [Tableau Dashboard](https://public.tableau.com/app/profile/moataz.osama/viz/Laundry-PickupServices/Dashboard1#1)  

## Objective  

- **Compare sales regions** based on:  
  - Average revenue per city  
  - Average marketing spend per city  
  - Average return on marketing investment (ROMI) per city (*revenue/marketing spend*)  
- **Identify the top 10 new locations** with the highest potential for increased marketing investment.  

## Approach and Findings  

### **Sales Region Analysis**  
- Visualized average **revenue, marketing spend, and ROMI** per city for each region.  
- **Region 1** outperforms with **higher average revenue, lower marketing spend, and higher ROMI**.  

### **Population and Expansion Data Integration**  
- Merged **population data** with expansion metrics.  
- Used **clustering techniques** based on revenue, marketing spend, and population.  

### **Cluster Analysis**  
- **Red Cluster**: Low population and revenue.  
- **Orange Cluster**: Revenue increases with population.  
- **Blue Cluster**: High revenue, dense population.  

### **Trend Line Analysis**  
- **Cluster 1:** Loss per dollar spent on marketing.  
- **Cluster 2:** Moderate revenue increase per marketing dollar.  
- **Cluster 3:** **Highest ROI**, ideal for further marketing investment.  

### **Conclusion**  
Prioritizing marketing funds in **Cluster 3** locations ensures the **best return on investment**, making it the most effective strategy.  
