# Healthcare_BI_ETL
An automated ETL pipeline for processing healthcare survey data, analyzing patient satisfaction and operational metrics, and visualizing insights through PostgreSQL and interactive dashboards

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

## Dataset
Using the HCAHPS (Hospital Consumer Assessment of Healthcare Providers and Systems) dataset, the project showcases data engineering, advanced analytics, machine learning, and visualization skills to deliver insights that can drive measurable improvements in healthcare quality.
See the [dataset source](https://www.cms.gov/data-research/research/consumer-assessment-healthcare-providers-systems/hospital-cahps-hcahps) for more details.

### Data Preparation Highlights:
- **Cleaned Missing Values**: Focused on key metrics like `survey_star_rating` and `positive_response_ratio`.  
- **Validated Dates**: Ensured survey start and end dates were consistent.  
- **Geographical Enrichment**: Added state and county-level satisfaction averages.

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

## Project Workflow

### 1. **ETL Pipeline**
- Loaded raw survey data from CSV.  
- Extracted relevant columns for hospitals, survey measures, and survey responses.  
- Cleaned and exported data into structured tables for analysis.

### 2. **Exploratory Data Analysis**
- Visualized key metrics, such as satisfaction trends, response rates, and positive response ratios.  
- Identified correlations and regional performance variations.

### 3. **Feature Engineering**
- Created new variables to enhance predictive power (e.g., interaction terms, positive response ratio).  
- Aggregated geographic metrics for benchmarking (state, city, county-level satisfaction scores).

### 4. **Predictive Modeling**
- Built machine learning models to predict satisfaction scores:  
  - Initial Random Forest model achieved **R² = 0.49** and **RMSE = 0.71**.  
  - Improved XGBoost model achieved **R² = 0.53** and **RMSE = 0.68** by adding interaction terms and geographic features.

### 5. **Visualization**
- Developed interactive Tableau dashboards for executives and operational teams:  
  - Tracked satisfaction trends over time.  
  - Highlighted underperforming hospitals and regions.

## Interactive Tableau Dashboard

[Tableau Dashboard](https://public.tableau.com/views/healthcar_BI/HealthCareBI?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

Click the image above to view the interactive dashboard on Tableau Public.

Thank you:)


