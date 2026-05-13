### Introduction <br>
Access to reliable water is a right protected under law. However, despite policy and regulation, violations still persist and many face threats to their water supply due to pollution, infrastructure failures, or noncompliance. Past environmental justice studies have uncovered disparity in water violations, describing increased violations in low-income and rural areas (Fedinick et al, 2019). 
<br>
In my home state of Oregon, certain areas have reported rising contaminant levels and excessive strain on water systems due to rising demands. To better understand the state of water accessibility and environmental justice in Oregon, public water system (PWS) violations were analyzed alongside various predictors to see where there is unreliable water and why. 
<br>
The main objectives of the project were to understand how PWS violations were spatially distributed. The project will also address if there are relationships between the amount of violations and the number of connections, primary water source, distance to water source, surrounding dominant landcover, and surrounding mean income. 
<br>
<br>

### Results: 
<br>
Multiple tests with Moran's I and Getis-Ord G statistics were done to assess the distribution of PWS violations. Chi testing, correlation tests, and model fitting was done to investigate possible explanatory factors for PWS violations. Key findings are listed below.
<br>
* PWS violations have a clustered spatial distribution with high clusters <br>
* Hotspots (PWSs with many violations) are scattered along parts of the southern coastline, Medford, northwestern region, and far eastern region of the state <br>
* Coldspots (PWSs with few or no violations) are scattered across the Willamette Valley and Bend. 
* There are significant relationships between total number of violations and distance from water source, surrounding mean income, and number of connections <br>
* Surrounding mean income level, number of connections, and having groundwater as a primary source instead of surface water have statistically significant negative relationships with the number of total violations
<br>
A map of hotspots and coldspots for PWS violations is shown below.
<br>
<br>
<img width="3300" height="2550" alt="Hotspot Analysis" src="https://github.com/user-attachments/assets/4a506203-4094-4ffd-b444-09b4876bc9df" />
<br>
Bivariate maps of the significant predictor variables and PWS violations can be seen below.
<br>
<br>
<img width="3300" height="2550" alt="Bivariate_income" src="https://github.com/user-attachments/assets/45aa20b4-3da8-4c61-8412-cb74b8ae85fc" />
<br>
<img width="3300" height="2550" alt="Bivariate_gw" src="https://github.com/user-attachments/assets/e02eea46-8a94-451d-88a1-37dedef38410" />
<br>
<img width="3300" height="2550" alt="Bivariate_dist" src="https://github.com/user-attachments/assets/8194f1b3-bbd3-4078-872a-ff11acffe4bd" />
<br>
<img width="3300" height="2550" alt="Bivariate_connections" src="https://github.com/user-attachments/assets/154341da-c8a9-4b24-9680-f0ec5e25631e" />
<br>
<br>

### Discussion 
<br>
Results of testing ultimately suggested that the distribution of violations is not uniform or random, and is instead influenced by other factors. There are clusters of high PWS violations, meaning that certain areas suffer from more violations than others. 
<br>
Investigation into the possible factors that could explain the number of violations in an area revealed relationships with the surrounding mean income, number of connections, and mean distance to water source. 
<br>
Results also showed that having higher income, more connections, and groundwater instead of surface water as a primary source were associated with a fewer violations. It is important to note that the fitted model had an extremely low psuedo R-squared value, meaning that there are likely <b>many other unaccounted variables at play affecting PWS violations<b>. Nonetheless, these predictors do explain a small part of how violations are distributed across Oregon. 
<br>
The results highlight environmental justice concerns about water access and reliability. There are areas that suffer disproportionately from more violations. These findings are backed by other studies describing how smaller water systems (Aikene al, 2023) and low income communities (Acquah et al, 2023) suffer from more contamination and violations, perhaps due to having less resources and infrastructure to maintain regulatory standards. Other concerns such as surface water pollution are raised from the findings that areas depending on surface water sources suffer from more violations compared to areas depending on groundwater sources. 
<br>
Overall, the study has emphasized the need for investment into surface water health as well as small PWSs located in low income communities. 
<br><br>

### Data Sources <br>
PWS Violations data were retrieved from OHA. Income and population data were retrieved from US Census Bureau. Landcover was retrieved from USGS. Groundwater and surfacewater surface areas were retrieved from Oregon DEQ. 
<br>
Oregon Health Authority. (2026). Drinking Water Data Online: Violations,
 https://yourwater.oregon.gov/violcounty.php . Accessed on 13 Mar 2026 <br>

Oregon Health Authority. (2026). Online Maps: Oregon Public Water Systems,  https://experience.arcgis.com/experience/02c5d88395404ad081884c98067a3565 . Accessed on 2 Feb 2026 <br>

U.S. Census Bureau. "Income in the Past 12 Months (in 2024 Inflation-Adjusted Dollars)." American Community Survey, ACS 5-Year Estimates Subject Tables, Table S1901,  https://data.census.gov/table/ACSST5Y2024.S1901?q=s1901&g=040XX00US06$1400000,32$1400000,41$1400000,53$1400000 . Accessed on 14 Mar 2026 <br>

U.S. Census Bureau. "ACS Demographic and Housing Estimates." American Community Survey, ACS 5-Year Estimates Data Profiles, Table DP05,  https://data.census.gov/table/ACSDP5Y2024.DP05?q=dp05&g=040XX00US06$1400000,32$1400000,41$1400000,53$1400000.  Accessed on 14 Mar 2026<br>

	
U.S. Geological Survey (USGS), 2024, Annual NLCD Collection 1 Science Products (ver. 1.1, June 2025): U.S. Geological Survey data release,  https://doi.org/10.5066/P94UXNTS . Accessed on 14 Mar 2026<br>

Oregon Department of Environmental Quality. (2020). Resources: Geographic Information Systems: Groundwater Drinking Water Source Areas in Oregon .  https://www.oregon.gov/deq/Get-Involved/Pages/GIS.aspx . Accessed on 2 Feb 2026<br>

Oregon Department of Environmental Quality. (2025). Resources: Geographic Information Systems: Surface Water Drinking Water Source Areas in Oregon.  https://www.oregon.gov/deq/Get-Involved/Pages/GIS.aspx . Accessed on 2 Feb 2026

 
