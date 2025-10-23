# Adverse Event Reporting in the Food and Cosmetics Industry- The CAERS database
## Objective-
The primary objective of analyzing the CFSAN Adverse Event Reporting System (CAERS) dataset is to gain a comprehensive understanding of adverse events associated with foods, dietary supplements, and cosmetics as reported to the FDA. This analysis aims to identify patterns and trends in these events, including the distribution across different product categories, the demographic characteristics of those affected, and the types and severities of reported symptoms and outcomes. By exploring these aspects, the analysis seeks to contribute valuable insights for enhancing product safety surveillance, informing regulatory policies, and ultimately improving public health outcomes by identifying potential risks and areas for intervention in the industries of food, dietary supplements, and cosmetics.

## Data Source-

The dataset from the CFSAN Adverse Event Reporting System (CAERS) is a comprehensive collection of reports submitted to the FDA regarding adverse events and product complaints associated with foods, dietary supplements, and cosmetics. It spans from 2004 to the second quarter of 2017 and includes several key fields:
1. RA_Report #: A unique identifier for each adverse event report.
2. RA_CAERS Created Date: The date when the report was entered into the CAERS database.
3. AEC_Event Start Date: The date when the adverse event started.
4. PRI_Product Role: Indicates whether the product was a suspect or concomitant (present during the event but not necessarily the cause).
5. PRI_Reported Brand/Product Name: The name of the product reported to be associated with the adverse event.
6. PRI_FDA Industry Code & Name: Categorization of the product based on FDA industry codes and names, such as 'Bakery Prod/Dough/Mix/Icing', 'Ice Cream Prod', etc.
7. CI_Age at Adverse Event: Age of the individual experiencing the adverse event.
8. CI_Age Unit: Unit of measurement for age (e.g., years, months).
9. CI_Gender: Gender of the individual.
10. AEC_One Row Outcomes: Describes the outcomes of the event, such as hospitalization, ER visit, or non-serious injuries/illness.
11. SYM_One Row Coded Symptoms: Lists the symptoms reported in association with the adverse event.

## Conclusion-
1. Comprehensive Data Understanding:
The CAERS dataset provided deep insights into adverse event patterns related to food, cosmetics, and dietary supplements reported to the FDA from 2004 to 2017.
2. Effective Data Transformation:
Using Power BI’s Power Query, raw data was cleaned, standardized, and enriched by creating new columns such as Created Date, Event Start Date, and Age in Years — enabling accurate analysis and visualization.
3. Structured Data Modeling:
A proper data model following a star schema was implemented, ensuring efficient relationships between key tables and enabling smooth DAX calculations.
4. Insightful Visual Dashboards:
Multiple interactive dashboards were created — covering product and industry trends, demographic distribution, symptom frequency, and adverse outcome patterns — helping identify key public health insights.
5. Identification of Risk Patterns:
Analysis revealed which product categories and brands were most associated with adverse events, as well as demographic trends like higher reporting among certain age groups and genders.
6. Real-World Relevance:
The project demonstrated how Power BI can support regulatory monitoring, consumer safety, and data-driven decision-making in public health sectors.
7. Learning and Skill Development:
The project enhanced our understanding of data cleaning, DAX formulas, modeling, and visualization, showcasing the power of analytics tools in transforming raw data into meaningful insights.
