# healthcare-revenue-strategy-simulation
12-week healthcare revenue and access pathway simulation using Python


## Strategic Simulation Disclaimer

:warning: This project uses simulated healthcare data for demonstration and learning purposes only. 
It does not represent real hospital revenue.


# Project Title :pushpin:

## Healthcare Business Intelligence
## Revenue Strategy Simulation – Annual Wellness Screening Program


## Project Overview
This project presents a 12-week pilot analysis of an Annual Wellness Screening Program conducted in a private multi-specialty hospital (strategic simulation).
The objective was to evaluate which patient access pathway delivers the strongest balance between:

-	Patient enrollment volume
+	Revenue per patient
*	Operational cost
-	Financial sustainability
  
A total of 12,000 patients enrolled through three different access pathways during the pilot period.


## Business Questions
The analysis was designed to answer the following leadership questions:

1	 Which pathway drives the highest patient enrollment?

2	 Which pathway generates the strongest revenue per patient?

3	 Does higher patient engagement justify higher operational cost?

4	 How did revenue evolve over the 12-week pilot?

These insights inform program expansion strategy.



## Access Pathways Analyzed

-	**Digital Self-Enrollment**
  
Patients enroll independently through an online portal.

+	**Physician-Initiated Enrollment**
  
Physicians introduce and enroll patients during consultations.

*	**Care Coordinator–Guided Enrollment**
  
Dedicated coordinators provide personalized enrollment and follow-up support.
Each pathway requires a different level of staff involvement and operational effort.



 ## Dataset Overview
 
-	12,000 patient records
+	12-week pilot period
*	Revenue per patient
-	Services utilized
+	Estimated pathway cost
*	Contribution margin
  
This dataset is a structured simulation created for strategic analysis and portfolio demonstration.



## Key Metrics Used

**Revenue Yield per Enrolled Patient (RYP)**

- Average revenue generated per patient within each pathway.
+ Used to measure financial intensity independent of enrollment volume.
  
**Contribution Margin per Patient**

- Service revenue minus pathway-specific operational cost.
+ Used to assess whether higher engagement justifies additional staffing cost.



 ## Key Findings
1 **Enrollment Volume**

Digital Self-Enrollment recorded the highest patient volume due to scalability and low staff dependency.

2 **Revenue per Patient**

Care Coordinator–Guided Enrollment generated the highest revenue per patient, indicating stronger service uptake among engaged patients.

3 **Revenue Distribution**

Care Coordinator pathway showed the widest revenue range.
Digital pathway showed moderate spread.
Physician-Initiated pathway showed the narrowest range and lower revenue values.

4 **Contribution Margin**

Care Coordinator pathway maintained the strongest contribution margin per patient despite higher operational cost.

5 **Weekly Trend**

Revenue increased steadily across the 12-week pilot, indicating growing adoption and stable performance.



 ## Strategic Interpretation
 
Digital pathways drive scale.

Higher-engagement pathways drive revenue intensity.

Sustainable program expansion requires balancing both models.



## Recommendations

-	Continue using Digital Self-Enrollment as the primary scalable pathway.
+	Deploy Care Coordinator–Guided Enrollment selectively for higher-value segments.
*	Position Physician-Initiated Enrollment as supportive rather than primary.
-	Expand data collection to include long-term retention and service-level cost details.



## Assumptions & Considerations
This analysis is based on a 12-week pilot simulation.
The following factors were not included:

-	Payer mix variation
+	Long-term patient retention
*	Clinical outcome measurement
-	Detailed service-level cost breakdown
  
Future evaluation should incorporate these elements.



## Technical Approach

Tools used:
-	Python (Pandas, NumPy, Matplotlib)
+	Exploratory Data Analysis
*	Grouped aggregations



## Visualizations Included :bar_chart:

-	Enrollment by pathway
+	Revenue distribution boxplots
*	Weekly trend line charts



## Repository Structure :paperclip:

/data
    annual_wellness_revenue_simulation.csv

/images
     Patients by Access Pathway
     Spread_of_Service_Revenue_by_Access_Pathway
     Overall_Weekly_Revenue_Yield_per_Patient

/notebooks
    access_pathway_strategy_simulation_analysis.ipynb

/presentation
    Annual_Wellness_Screening_Revenue_Strategy.pptx

/README.md



## Author
Deborah Akhabue

Healthcare Data Analyst

Focused on healthcare performance, operational efficiency, and revenue intelligence.


