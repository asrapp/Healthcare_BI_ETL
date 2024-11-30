# Healthcare Analytics and Operational Intelligence 
A data-driven project designed to improve patient satisfaction, operational efficiency, and decision-making in the healthcare industry. 

This independent project highlights my ability to design, implement, and deliver impactful data solutions that align with real-world healthcare challenges. The project emphasizes ETL pipeline development, statistical analysis, predictive modeling, and dashboarding—all critical skills for a data analyst role in the healthcare industry.

## Project Goals
1. **Analyze Patient Satisfaction Trends**  
   - Explore factors impacting patient satisfaction, such as survey response rates and cleanliness metrics.  
   - Identify key drivers of satisfaction to guide operational improvements.

2. **Build Predictive Models**  
   - Use machine learning to predict hospital satisfaction scores and survey response rates.  
   - Provide hospitals with tools for proactive decision-making.

3. **Develop Interactive Dashboards**  
   - Present actionable insights through Tableau dashboards for executives and operational teams.  
   - Enable geographic performance comparisons across states, cities, and counties.

4. **Optimize Operational Metrics**  
   - Analyze response rates, completion rates, and engagement metrics to improve survey reliability.

---

## Dataset
Using the HCAHPS (Hospital Consumer Assessment of Healthcare Providers and Systems) dataset, the project showcases data engineering, advanced analytics, machine learning, and visualization skills to deliver insights that can drive measurable improvements in healthcare quality.
See the [dataset source](https://www.cms.gov/data-research/research/consumer-assessment-healthcare-providers-systems/hospital-cahps-hcahps) for more details.



### Data Preparation Highlights:
- **Cleaned Missing Values**: Focused on key metrics like `survey_star_rating` and `positive_response_ratio`.  
- **Validated Dates**: Ensured survey start and end dates were consistent.  
- **Geographical Enrichment**: Added state and county-level satisfaction averages.

---

## Key Features
### 1. **ETL Process**
- Automated the extraction, transformation, and loading (ETL) of patient survey data using Python.  
- Processed raw data into three structured tables:  
  - **Hospitals Table**: Hospital details (e.g., name, address, location).  
  - **Survey Measures Table**: Survey questions and answer descriptions.  
  - **Survey Responses Table**: Star ratings, response rates, and completion metrics.  
- Ensured data quality by handling missing values, standardizing date formats, and validating key fields.  

### 2. **Feature Engineering**
- **Positive Response Ratio**: Calculated the percentage of patients answering “Always” for key satisfaction measures.  
- **Geographical Metrics**: Aggregated satisfaction scores at the state, city, and county levels.  
- **Interaction Terms**: Added combined metrics (e.g., positive responses × response rates) to enhance predictive modeling.

### 3. **Exploratory Data Analysis (EDA)**
- **Satisfaction Trends**: Visualized distributions of star ratings and positive response ratios.  
- **Correlation Analysis**: Identified relationships between response rates, positive feedback, and satisfaction scores.  
- **Geographic Insights**: Mapped satisfaction trends across states and counties.

### 4. **Machine Learning Models**
- Built and evaluated predictive models to forecast patient satisfaction scores:  
  - **Random Forest Regressor**: Predicted satisfaction with an **R² of 0.53** and **RMSE of 0.68**.  
  - **XGBoost Regressor**: Incorporated advanced features, improving model accuracy.  
- Key insights from feature importance:  
  - **Positive Response Ratio**: Most significant predictor of satisfaction (44% importance).  
  - **Response Rate**: Secondary predictor, highlighting engagement’s role in satisfaction.

### 5. **Interactive Dashboards**
- Designed **Tableau Dashboards** tailored for stakeholder needs:  
  - **Executive Dashboard**: High-level KPIs, including satisfaction trends and state-level performance.  
  - **Operational Dashboard**: Drill-down views of response rates, positive response ratios, and star ratings.  
  - **Geographic Dashboard**: Heatmaps of satisfaction scores by state, city, and county.



## Tools and Technologies
- **Python**: pandas, NumPy, matplotlib, seaborn, scikit-learn, XGBoost.  
- **Tableau**: Designed role-specific, interactive dashboards for data visualization.  
- **SQL**: Used for relational data structuring and querying.  
- **HCAHPS Dataset**: Publicly available data from CMS.  

---

## Key Insights
1. **Cleanliness as a Key Driver**  
   - Positive cleanliness ratings are strongly correlated with higher satisfaction scores.  
   - Hospitals with higher positive response ratios ("Always" answers) tend to achieve better overall ratings.

2. **Response Rates and Reliability**  
   - Higher survey response rates contribute to more reliable satisfaction scores.  
   - Hospitals with low response rates may need interventions to improve survey engagement.

3. **Geographic Trends**  
   - Satisfaction scores vary significantly by state and county.  
   - High-performing regions can serve as benchmarks for underperforming areas.


## Interactive Tableau Dashboard

[Tableau Dashboard](https://public.tableau.com/views/healthcar_BI/HealthCareBI?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

Click the image above to view the interactive dashboard on Tableau Public.

Thank you:)


