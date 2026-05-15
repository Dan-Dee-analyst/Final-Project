<h1>Electric Vehicle in the United States</h1>

 ### [Tableau Ev Dataset](https://public.tableau.com/app/profile/gaurav.ganesha.kamath/viz/ElectricVehiclePopulationDataAnalysisinUSA/Dashboard)

 <h2>Final Report</h2>
 
 <h2>Introduction</h2>
The project objective is to evaluate the growth and distribution of electric vehicle (EVs) in the United States. Using this dataset this report shows insight into regional EV adoption, top manufacturers, EV types and eligibility for clean fuel incentives. The objective is to understand how EV treads have shifted over time and across geographies.
The analysis is created to be simple and informative for stakeholders including state transportation departments, utility providers and electric vehicle manufacturers. By examining state level treads and data, the report illustrates the current and emerging landscape of electric vehicle usage.
The purpose of this project is to give a clear picture of the growing electric vehicle market in the United State and highlight potential areas for infrastructure and business planning.

<h2>Dataset</h2>

Description: EV registration data across the U.S. including make, model year, vehicle type, geographic info and eligibility for clean-fuel vehicle programs.

<h4>Dataset Details:</h4>

- <b>Rows: 130,000</b> 
- <b>Columns: 10</b> 
- <b>Size: 1,200 kb (1.2 mb)</b> 

### - <b>Source: [Electric Vehicle Population In U.S. Dataset](https://public.tableau.com/app/profile/gaurav.ganesha.kamath/viz/ElectricVehiclePopulationDataAnalysisinUSA/Dashboard)
  
<b>Business Impact</b>

- <b>	Manufacturers: Target markets for expansion and evaluate competitive positioning.</b>
- <b>	Utility companies: Plan electrical grip capacity based on based on where EV demand is surging</b>
- <b> Policy makers: Identify high adoption regions and direct clean energy incentives accordingly.</b>
- <b>	Investors and startups: Detect geographical and technological opportunities (e.g. charging spots)</b>


 <h2>Data Analysis & Computation</h2>
 
 <h2>Data Cleaning</h2>
 
- <b>Removed empty or irrelevant rows (e.g. blank coordinates or unregistered state</b> 
- <b>Removed records with null or blank state, make or model year</b> 
- <b>Standardized manufacturer names to correct inconsistent capitalization.</b> 
- <b>Filtered EV types to include only BEV and PHEV</b> 

 <h2>Analysis Methods</h2>

 <h3> 1. Total Records</h3>
Established a total count of 130,000 electric vehicles. Data was filtered to maintain only valid U.S. State registered EVs for a clean analytical base.
 <h3> 2. Manufacturer Distribution</h3>
Grouped and ranked by make, show tesla with approximately 50% market share, Nissan, Chevrolet, ford and BMW follow. A bar chart clearly illustrated this dominance.
 <h3> 3. EV Records by year</h3>
Mapped model year against vehicle count. Findings show a sharp acceleration in EV adoption from 2017 to 2022, peaking in 2021. The growth patterns support global treads toward electrification.
<h3> 4. EV Type Breakdown</h3>
Data shows battery electric vehicles (BEVs) represent 65% of all records while the remainder are PHEVs, Pie chart visualization is being used to demonstrate this category.
<h3> 5. Electric Range</h3>
Electric range data shows most EVs fall between 200 and 300 miles per charge. A chart is being used to show the distribution. This supports the narrative of improving the battery technology over the past 5-7 years.
<h3> 6. CAFV Eligibility</h3>
Eligibility for clean alternative fuel vehicle (CAFV) programs were analyzed. Over 70% of EVs in the dataset were eligible. Bar charts were used.
<h3> 7. Geographic Spread</h3>
Mapped vehicle counts by state. California accounts for over 40% of EVs. Large counts were also found in Washington Texas, Florida and New York. A U.S. choropleth map highlighted clear regional clusters and underserved areas.

 <h2>Dashboard</h2>
The Dashboard Electric Vehicle Population in the U.S. is purposely intended to allow users to explore EV trends interactively. With filters for state, make and model year, users can isolate high adoption areas, top manufacturers and identify where infrastructure investment may be required.
 <h2>It presents six visualizations:</h2>
 
- <b>EVs by state (MAP)</b> 
- <b>Growth over time (LINE)</b> 
- <b>Top makes (BAR)</b> 
- <b>EV type breakdown (PIE)</b> 
- <b>Electric range distribution (HISTOGRAM)</b> 
- <b>Clean alternative fuel vehicle eligibility (BAR)</b> 

The supports a story driven approach to data consumption and is ideal for presentations, investment pitches and public policy reviews.

 <h2>Dashbord Design Takeaways</h2>
Interactive filters by state and year let user explore personalized insights.

- <b>Clear visuals make it useful for:</b> 
- <b>Public presentations</b> 
- <b>Internal business planning</b> 
- <b>Government briefings</b> 
- <b>Dashboard is built for real time storytelling, not just static reporting.</b> 

 <h2>Strategic opportunities identified</h2>
 
- <b>High growth regions can be targeted for charging infrastructure</b> 
- <b>Policy feedback loops: state with CAFV eligibility see higher EV penetration</b> 
- <b>Manufacturers can use geographic insights for regional marketing and logistics</b> 

 <h2>Future expansion possibilities</h2>
 
- <b>Integrate charging station location data for accessibility mapping</b> 
- <b>Use time series forecasting to predict EV growth over the next 5 years</b> 
- <b>Add demographics to assess wquity in EV adoption</b> 
- <b>Blend in climate action data for emissions modelings and sustainability metrics</b> 

 <h2>Challenges</h2>
 
- <b>The dataset lacked complete information in some fields, especially Electric Range, Base MSRP and Geographic coordinates.</b> 
- <b>Another issue was tableau not showing ‘ Number of Records’ by default.</b> 
- <b>Some states had surprisingly low counts despite high populations. This may reflect dataset coverage rather than true adoption rates.</b> 
- <b>Outliers in Model year and non-standard vehicle makes were filtered and grouped under Other to prevent skew.</b> 

 <h2>Conclusion & Future Work</h2>
 <h2>Conclusion</h2>
The dataset revealed key insights about the EV market in the U.S.

- <b>EVs are mostly BEVs, not hybrids</b> 
- <b>Most vehicles offer 200-300 miles of range</b> 
- <b>Majority qualify for CAFV, supporting the impact of incentive programs</b> 
- <b>EV growth is exponential since 2017</b> 
- <b>Tesla dominates the market then followed by a few others such as Nissan, Chevrolet, Ford and BMW</b> 
- <b>California leads in adoption by 40% of EVs, then Washington, Texas and Florida</b> 

This analysis confirmed that Ev adoption is growing rapidly and unevenly suggesting the need for targeted strategies by state, manufacture and infrastructure provider.</b> 


Future Work
Future studies could integrate:

- <b>Charging station availability</b> 
- <b>Vehicle resale value data</b> 
- <b>Emissions reductions by EV type</b> 
- <b>State level policy comparisons</b> 
- <b>Predictive modeling (EV growth forecasting by region)</b> 
This would enhance policy and business decision- making in the clean transportation section.


<h2>Graphical interface overview:</h2>

<p align="center">
<br/>
 <img src="https://github.com/Dan-Dee-analyst/Final-Project/blob/main/Screenshot%202026-05-15%20at%2011.16.02.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />



<p align="center">
<br/>
 <img src="https://github.com/Dan-Dee-analyst/Final-Project/blob/main/Screenshot%202026-05-15%20at%2011.19.23.png?raw=true"height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
<br/>
 <img src="https://github.com/Dan-Dee-analyst/Final-Project/blob/main/Screenshot%202026-05-15%20at%2011.19.44.png?raw=true"height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
<br/>
 <img src="https://github.com/Dan-Dee-analyst/Final-Project/blob/main/Screenshot%202026-05-15%20at%2011.22.02.png?raw=true"height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
