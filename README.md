## Fast Food Marketing A/B Test Analysis

This project analyzes the effectiveness of three marketing campaigns using A/B testing methods. The dataset used comes from the `wa_marketing_campaign` table in the `turing_data_analytics` BigQuery project. The goal is to determine which promotion performed best across locations, based on weekly sales data.

### Project Objectives

* Evaluate the impact of different marketing promotions on sales
* Perform **pairwise statistical comparisons** between the three campaigns
* Control for **multiple testing error** by using a stricter significance threshold (99% confidence level)
* Provide a structured A/B testing analysis similar to the previous hands-on task

### Data Summary

* **Source**: `turing_data_analytics.wa_marketing_campaign`
* **Granularity**: Aggregated by `LocationID`, `PromotionID`, and week
* **Preprocessing**: Data further aggregated by `LocationID` and `PromotionID` for analysis

### Deliverables

* `AB_Test_Analysis.xlsx` – Statistical test results, comparisons, and visualizations
* - `Statistical Inference & A/B Testing.pdf` – Full report detailing the analysis methodology, statistical tests, and conclusions regarding the marketing campaigns.


### Tools Used

* **BigQuery SQL** – Data extraction and preprocessing
* **Excel/Google Sheets** – Statistical testing and result visualization

