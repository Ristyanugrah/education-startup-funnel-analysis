# Education Startup Funnel Analysis: Conversion & Drop-off Insights

## Project Overview

This project analyzes the customer acquisition funnel of an education startup using Python and Pandas. The analysis focuses on understanding how customers progress through each stage of the funnel, identifying the largest drop-off point, and comparing conversion performance across customer groups.

The goal is to identify opportunities to improve customer conversion and provide data-driven recommendations for business optimization.

## Business Problem

An education startup needs to understand how effectively it converts potential customers into registered users. By analyzing conversion rates and customer drop-offs, the business can identify stages that may require further investigation and improvement.

## Objectives

- Analyze the customer funnel from lead generation to user registration.
- Calculate conversion rates and drop-off rates at each stage.
- Identify the stage with the largest customer drop-off.
- Compare conversion performance across customer groups.
- Identify customer groups with the highest and lowest overall conversion rates.
- Develop data-driven recommendations to improve funnel performance.

## Funnel Stages

The analysis uses the following funnel:

1. **Leads** — Potential customers entering the funnel.
2. **Bookings** — Leads progressing to the booking stage.
3. **Free Trials** — Customers proceeding to try the service.
4. **Register New User** — Customers registering as new users.

## Tools & Technologies

- Python
- Pandas
- Google Colab
- Matplotlib (for visualizations, if used in the notebook)

## Analysis Process

1. **Data Loading and Inspection**  
   Load the Excel dataset and inspect its structure, dimensions, data types, and missing values.

2. **Funnel Analysis**  
   Aggregate customer counts at each stage and arrange the stages in the correct order.

3. **Conversion Rate Analysis**  
   Calculate the percentage of customers progressing from one stage to the next.

4. **Drop-off Analysis**  
   Measure the percentage of customers who do not progress to the next stage and identify the largest drop-off.

5. **Customer Group Analysis**  
   Compare stage-level and overall conversion rates across customer groups.

6. **Business Recommendations**  
   Identify opportunities for further investigation and potential conversion improvements.

## Key Findings

- The largest reported drop-off occurs between **Bookings and Free Trials**, with a drop-off rate of **37.32%**.
- The number of bookings is **417,400**, while the number of free trials is **261,630**.
- Customer group performance is evaluated using stage-level conversion rates and overall conversion rates.
- The dataset identifies where the largest drop-off occurs, but it does not establish the specific reasons customers fail to progress.

## Business Recommendations

Based on the observed funnel drop-off, the following actions could be investigated:

- Review the booking-to-free-trial activation process to identify potential friction.
- Evaluate follow-up communication with customers after booking.
- Compare customer expectations with the actual free-trial experience.
- Investigate conversion differences across customer groups.
- Monitor funnel conversion rates over time to evaluate the impact of future improvements.

These recommendations are hypotheses for further investigation, not confirmed causes of customer drop-off.

## Project Limitations

- The dataset does not directly explain why customers drop out of the funnel.
- Potential causes of drop-off require additional customer feedback, behavioral data, or operational information.
- The reported conversion rates depend on the accuracy and consistency of the stage counts in the dataset.

## Conclusion

This project demonstrates how funnel analysis can help an education startup evaluate customer progression, identify conversion bottlenecks, and prioritize areas for further investigation.

The reported 37.32% drop-off between Bookings and Free Trials highlights an important stage for potential improvement. Further investigation is needed to determine the underlying causes and validate the effectiveness of proposed actions.

## Author

**Risty Anugrah Dwi Septiana**

Informatics Engineering Graduate | Data Analyst Enthusiast

- GitHub: [Ristyanugrah](https://github.com/Ristyanugrah)
- Portfolio: [Data Analytics Portfolio](https://github.com/Ristyanugrah/data-analytics-portfolio)

---

*This project was developed as part of a data analytics learning journey, applying Python and Pandas to business funnel analysis.*
