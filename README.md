# Healthcare Revenue Strategy | Strategic Simulation Analysis
*****


## Strategic Simulation Disclaimer

:warning: This project uses simulated healthcare data created for demonstration and portfolio purposes only. 
It does not represent real hospital revenue.


## Table of Contents
- [Project Title](#project-title)
- [Project Overview](#project-overview)
- [Business Questions](#business-questions)
- [Access Pathways Analyzed](#access-pathways)
- [Dataset Overview](#dataset-overview)
- [Key Metrics Used](#key-metrics)
- [Key Findings](#key-findings)
- [Strategic Interpretation](#strategic-interpretation)
- [Recommendations](#recommendations)
- [Assumptions & Considerations](#assumptions)
- [Technical Approach](#technical-approach)
- [Visualizations Included](#visualizations)
- [Repository Structure](#repo-structure)
- [Author](#author)


<a id="project-title"></a>
## :pushpin: Project Title

## Revenue Strategy Simulation – Annual Wellness Screening Program

<a id="project-overview"></a>
## :open_book: 1. Project Overview
This project presents a 12-week pilot analysis of an Annual Wellness Screening Program conducted in a private multi-specialty hospital (strategic simulation).
The objective was to evaluate which patient access pathway delivers the strongest balance between:

-	Patient enrollment volume
+	Revenue per patient
*	Operational cost
-	Financial sustainability
  
A total of 12,000 patients enrolled through three different access pathways during the pilot period.

📊 The full executive presentation is available here [Annual Wellness Revenue Strategy](https://github.com/AkhabueDeborah2/healthcare-revenue-strategy-simulation/tree/main/presentation)


<a id="business-questions"></a>
## :question: 2. Business Questions
The analysis was designed to answer the following leadership questions:

1	 Which pathway drives the highest patient enrollment?

2	 Which pathway generates the strongest revenue per patient?

3	 Does higher patient engagement justify higher operational cost?

4	 How did revenue evolve over the 12-week pilot?

These insights inform program expansion strategy.


<a id="access-pathways"></a>
## :hospital: 3. Access Pathways Analyzed

-	**Digital Self-Enrollment**
  
Patients enroll independently through an online portal.

+	**Physician-Initiated Enrollment**
  
Physicians introduce and enroll patients during consultations.

*	**Care Coordinator–Guided Enrollment**
  
Dedicated coordinators provide personalized enrollment and follow-up support.
Each pathway requires a different level of staff involvement and operational effort.


<a id="dataset-overview"></a>
 ## :card_index_dividers: 4. Dataset Overview
 
-	12,000 patient records
+	12-week pilot period
*	Revenue per patient
-	Services utilized
+	Estimated pathway cost
*	Contribution margin
  
This dataset is a structured simulation created for strategic analysis and portfolio demonstration.


<a id="key-metrics"></a>
## :triangular_ruler: 5. Key Metrics Used

**Revenue Yield per Enrolled Patient (RYP)**

- Average revenue generated per patient within each pathway.
+ Used to measure financial intensity independent of enrollment volume.
  
**Contribution Margin per Patient**

- Service revenue minus pathway-specific operational cost.
+ Used to assess whether higher engagement justifies additional staffing cost.


<a id="key-findings"></a>
 ## :chart_with_upwards_trend: 6. Key Findings
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


<a id="strategic-interpretation"></a>
 ## :compass: 7. Strategic Interpretation
 
Digital pathways drive scale.

Higher-engagement pathways drive revenue intensity.

Sustainable program expansion requires balancing both models.


<a id="recommendations"></a>
## :white_check_mark: 8. Recommendations

-	Continue using Digital Self-Enrollment as the primary scalable pathway.
+	Deploy Care Coordinator–Guided Enrollment selectively for higher-value segments.
*	Position Physician-Initiated Enrollment as supportive rather than primary.
-	Expand data collection to include long-term retention and service-level cost details.


<a id="assumptions"></a>
## :warning: 9. Assumptions & Considerations
This analysis is based on a 12-week pilot simulation.
The following factors were not included:

-	Payer mix variation
+	Long-term patient retention
*	Clinical outcome measurement
-	Detailed service-level cost breakdown
  
Future evaluation should incorporate these elements.


<a id="technical-approach"></a>
## :computer: 10. Technical Approach

Tools used:
-	Python (Pandas, NumPy, Matplotlib)
+	Exploratory Data Analysis
*	Grouped aggregations


<a id="visualizations"></a>
## :bar_chart: Visualizations Included 

-	Enrollment by pathway
+	Revenue distribution boxplots
*	Weekly trend line charts


<a id="repo-structure"></a>
## :file_folder: Repository Structure 

/data
    annual_wellness_revenue_simulation.csv

/images

     Patients_by_Access_Pathway
     
     Spread_of_Service_Revenue_by_Access_Pathway
     
     Overall_Weekly_Revenue_Yield_per_Patient

/notebooks
    access_pathway_strategy_simulation_analysis.ipynb

/presentation
    Annual_Wellness_Screening_Revenue_Strategy.pptx

/README.md


<a id="author"></a>
## :bust_in_silhouette: Author
Deborah Akhabue

Healthcare Data Analyst

Focused on healthcare performance, operational efficiency, and revenue intelligence.


