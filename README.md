## Insurance Risk & Claims Analysis – Power BI Dashboard Project
# Project Overview
The Insurance Risk & Claims Analysis project was developed to help an insurance company centralize and analyze its policy holder and claims data for better strategic decision-making. Previously, policy and claims information was scattered across multiple sources, making it difficult for stakeholders to monitor performance, detect trends, and identify potential risk areas.
This project delivers an interactive Power BI dashboard that consolidates data into a single analytical view, enabling business users to track key metrics, explore customer segments, and uncover claim patterns efficiently.
# Dataset used 
- <a href= "https://github.com/ShahilFarshad/Insurance-risk-and-claims-analysis/blob/main/insurance_policies_data.xlsx"> View Insurance policies dataset </a>
## KPI’s Requirements:
1.	Total Policies – to measure the size of the active customer base.
2.	Total Claim Amount – to track the overall financial impact of claims.
3.	Claim Frequency – to analyse how often claims are being made.
4.	Average Claim Amount – to assess claim severity and potential risk exposure.
5.	Gender-wise Total Policies – to understand customer distribution across genders for better segmentation and policy targeting.
## Chart’s Requirements:
To deep dive into the data, we need to go beyond KPIs and analyse different aspects of insurance policies and claims. Charts help us visually explore patterns, relationships, and anomalies across customer demographics, car details, and claim behaviours. By analysing charts, stakeholders can identify risk factors, understand customer segments, and optimize policy decisions.
For this report, all visualizations are designed around two key dynamic measures:
•	Total Claim Amount
•	Total Policies
These measures provide the foundation to compare, filter, and segment the data effectively.
## Visualization Requirements:
1.	By Car Use (Donut Chart) – To analyse policy distribution and claim amounts based on how cars are being used (e.g., personal, commercial).
2.	By Car Make (Bar Chart) – To identify which car brands have higher policies and claims, highlighting brand-based risks.
3.	By Coverage Zone (Donut Chart) – To evaluate policies and claims by geographic zones, useful for regional risk analysis.
4.	By Age Group (Frequency Chart/Histogram) – To assess policyholders’ age distribution and identify which age brackets file more claims.
5.	By Car Year (Area Chart) – To analyse how the car’s age (year of manufacture) impacts policy counts and claim amounts.
6.	By Kids Driving (Ribbon Chart) – To compare the impact of young drivers in households on policy count and claim amounts.
7.	By Education (Pie Chart) – To understand how education levels correlate with insurance policy adoption and claims.
8.	By Education & Marital Status (Matrix Heat Grid) – To explore the combined effect of education and marital status on policies and claims, highlighting customer profiles.
- Dashboard Interaction <a href = "https://github.com/ShahilFarshad/Insurance-risk-and-claims-analysis/blob/main/Insurence%20risk%20and%20claims%20db.png"> View Dashboard </a>

# Process
- Understand business requirements and define key KPIs.
- Collect policy, claims, customer, vehicle, and coverage data.
- Clean and transform the data using Power Query.
- Create relationships and build a structured data model.
- Develop DAX measures for KPIs and dynamic calculations.
- Plan the dashboard layout and visual structure.
- Create KPI cards for summary insights.
- Build charts for demographic, vehicle, and geographic analysis.
- Add slicers and enable cross-filtering for interactivity.
- Test calculations, validate results, and optimize performance.
- Publish the dashboard and share it with stakeholders.
  
## Dashboard
<img width="1363" height="806" alt="Insurence risk and claims db" src="https://github.com/user-attachments/assets/4a456a84-3157-474b-9adf-a97d8743ba45" />

## Dashboard file 
<a href="https://github.com/ShahilFarshad/Insurance-risk-and-claims-analysis/blob/main/INSURENSE%20%26%20RISK%20DB.pbix"> Insurance risk and claims analysis dashboard </a> 

## Project Insight
- The company has 37K+ active policies.
- Total claim amount exceeds $187M, showing high financial exposure.
- Average claim amount is around $5K.
- Private vehicles generate the highest claims.
- Certain car brands contribute more to total claim amounts.
- Urban and highly urban areas have higher claim values.
- Middle-aged customers (26–55) file the most claims.
- Households with young drivers have higher claim amounts.
- Bachelor’s degree holders show the highest total claims.
- Married customers contribute more to overall claim amounts.
- Gender distribution of policies is nearly equal.
- Newer car models show increasing claim trends.


