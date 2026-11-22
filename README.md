# British Airways Customer Reviews & Service Analytics Dashboard

![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Focus-Data%20Analytics-blue?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Focus-Data%20Visualization-2E8B57?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

## 1. Project Overview

The **British Airways Customer Reviews & Service Analytics Dashboard** is an interactive Tableau data visualization project designed to explore customer experiences and evaluate airline service performance.

Customer feedback provides valuable insights into service quality, operational performance and customer satisfaction. However, extracting meaningful patterns from large volumes of reviews requires effective data visualization and analytical techniques.

The objective of this project is to transform British Airways customer review data into an interactive dashboard that enables users to explore service ratings across different aircraft, geographical locations, travel periods and passenger segments.

The dashboard provides an overview of customer experience indicators, allowing stakeholders to identify performance patterns and potential areas for service improvement.

**Business Objectives:**
- Evaluate customer satisfaction across different airline service dimensions.
- Compare service performance across aircraft types.
- Explore geographical variations in customer ratings.
- Analyse changes in customer ratings over time.
- Identify potential service improvement opportunities through interactive data exploration.

**Target Audience:** Business analysts, data analysts, airline management, customer experience teams and operational decision-makers.

## 2. Dashboard Preview

https://github.com/MasekoNP/British_airways_project_tableau/blob/152c5409cb4006a62e8d2bcb91fd83e2ae0e8352/British%20Airways%20Dashboard%20Screenshot.PNG

### Explore the Interactive Dashboard

https://github.com/MasekoNP/British_airways_project_tableau/blob/9786cfbd9dd7e6b3cbce96fb990e790438e39ce4/British%20Airways%20dashboard.twbx
## 3. Data Source & Preparation

### Data Sources

The Tableau workbook references the following datasets:

| Dataset | Description |
|---|---|
| `ba_reviews.csv` | British Airways customer review and service-rating data |
| `Countries.csv` | Geographical reference data used for country-level visualization |

The customer review dataset contains fields relating to:
- Customer review dates and flight dates.
- Aircraft and travel routes.
- Traveller types and seat classes.
- Overall customer ratings.
- Individual service quality ratings.
- Customer recommendations and trip verification.

### Data Preparation

The workbook uses Tableau's data connection and visualization capabilities to organize and analyse the customer review information.

The analytical fields include:
- Overall Rating
- Seat Comfort
- Cabin Staff Service
- Food & Beverages
- Ground Service
- Entertainment
- Value for Money

A calculated field, **Metric Selected**, dynamically selects the appropriate rating measure based on the user's chosen parameter.

The workbook also includes an aircraft grouping field and geographical dimensions such as country and continent to support comparative analysis.

**Note:** Detailed upstream data-cleaning procedures, including missing-value treatment, duplicate removal and date standardization, should be documented once verified against the original datasets and preparation workflow.

## 4. Key Metrics & Dashboard Features

### Key Performance Indicators (KPIs)

The dashboard supports analysis of the following customer experience indicators:

| Metric | Analytical Purpose |
|---|---|
| Overall Rating | Evaluates customers' overall airline experience. |
| Cabin Staff Service | Assesses customer perceptions of cabin crew service. |
| Seat Comfort | Evaluates passenger comfort during flights. |
| Food & Beverages | Examines customer satisfaction with onboard catering. |
| Ground Service | Evaluates the quality of airport and ground services. |
| Entertainment | Assesses the onboard entertainment experience. |
| Value for Money | Evaluates perceived value relative to the cost of travel. |

### Interactive Dashboard Features

**1. Dynamic Metric Selection**

Users can select a customer experience metric from the dashboard's parameter control. The selected metric dynamically updates the visualizations, allowing comparisons across multiple service dimensions without switching between separate dashboards.

Available selections include:
- Overall Rating
- Cabin Staff Service
- Entertainment
- Food
- Ground Service
- Seat Comfort
- Value

**2. Geographical Analysis**

The interactive geographical visualization presents average customer ratings by country, enabling users to explore geographical differences in customer experience.

**3. Monthly Performance Analysis**

The monthly visualization enables users to examine changes in average customer ratings over time and identify potential temporal patterns.

**4. Aircraft Performance Analysis**

The aircraft visualization compares average customer ratings across aircraft categories, supporting the identification of potential differences in passenger experience between aircraft.

**5. Interactive Filters**

Users can refine their analysis through the following dashboard filters:

| Filter | Function |
|---|---|
| Date | Narrows the analysis to a selected review period. |
| Traveller Type | Compares customer experiences across traveller segments. |
| Seat Type | Explores ratings across different cabin classes. |
| Aircraft Group | Filters performance by aircraft category. |
| Continent | Enables geographical comparisons at continent level. |

These interactive features allow users to investigate specific customer segments and service dimensions.

## 5. Key Insights & Findings

The dashboard is designed to uncover patterns in customer satisfaction across different dimensions of the British Airways passenger experience.

The following analytical areas can be investigated:

- **Service Quality:** Compare cabin staff service, ground service, food and beverage quality, entertainment and seat comfort to identify differences in customer perceptions.
- **Aircraft Performance:** Investigate whether customer ratings vary across aircraft categories.
- **Geographical Performance:** Examine differences in customer ratings across countries and continents.
- **Customer Experience Trends:** Analyse monthly rating patterns to identify periods of improving or declining customer satisfaction.

**Important:** Numerical findings and ranked performance claims should be added after validating the underlying dataset and dashboard results. No specific rating averages or trends are assumed in this documentation.

## 6. Actionable Business Recommendations

The dashboard provides a foundation for evidence-based recommendations that British Airways could consider when evaluating customer experience and service delivery.

**1. Prioritize Service Improvement Areas**

Use comparisons between service dimensions to identify areas with relatively lower customer ratings. Prioritize improvements where customer dissatisfaction is most evident.

**2. Evaluate Aircraft-Specific Experiences**

Investigate aircraft categories associated with weaker customer ratings. Consider targeted cabin maintenance, seating improvements and onboard service reviews where the evidence supports intervention.

**3. Strengthen Geographical Service Monitoring**

Use geographical comparisons to identify markets or destinations where customer experiences differ. Further investigate operational factors that could explain these differences.

**4. Monitor Customer Experience Over Time**

Track monthly service ratings to identify emerging patterns and evaluate whether operational improvements are associated with better customer feedback.

**5. Improve Data-Driven Decision-Making**

Integrate customer feedback analysis into regular operational performance reviews, enabling management to prioritize interventions using measurable customer experience indicators.

## 7. Technical Skills Demonstrated

This project demonstrates practical experience in:

- **Data Visualization:** Developing interactive dashboards using Tableau.
- **Exploratory Data Analysis:** Investigating customer satisfaction patterns across multiple dimensions.
- **Calculated Fields:** Creating dynamic analytical measures using Tableau calculations.
- **Parameter Controls:** Implementing dynamic metric selection.
- **Geographical Analysis:** Visualizing customer ratings across countries and continents.
- **Time-Based Analysis:** Exploring monthly customer rating patterns.
- **Interactive Reporting:** Building dashboards with multiple filters for stakeholder-driven analysis.
- **Business Intelligence:** Translating customer review data into actionable business insights.

## 8. How to Use / View Locally

### Option 1: View the Published Dashboard

1. Open the Tableau Public dashboard link provided above.
2. Explore the visualizations.
3. Use the available filters to refine the analysis.
4. Change the selected metric to investigate different customer experience dimensions.

### Option 2: Open the Tableau Workbook Locally

1. Clone or download this GitHub repository.
2. Ensure the required datasets, `ba_reviews.csv` and `Countries.csv`, are available.
3. Open `British Airways dashboard.twb` using Tableau Desktop.
4. If Tableau reports missing data connections, reconnect the workbook to the corresponding CSV files.
5. Refresh the data connections if necessary.
6. Explore the dashboard and its interactive functionality.

**Note:** The uploaded workbook is a `.twb` file, which stores Tableau workbook definitions rather than packaging the underlying data. A `.twbx` packaged workbook can be used to distribute the workbook together with its supporting data and resources, subject to applicable data-sharing permissions.

## 9. Repository Structure

```text
British-Airways-Customer-Analytics/
│
├── British Airways dashboard.twb
│
├── Dataset/
│   ├── ba_reviews.csv
│   └── Countries.csv
│
├── Images/
│   └── dashboard-preview.png
│
└── README.md
```

*The repository structure above is a recommended organization. Include the dataset files only if you have permission to redistribute them.*

## 10. Project Conclusion

This project demonstrates how customer review data can be transformed into an interactive business intelligence solution.

By combining dynamic metric selection, geographical visualization, monthly analysis and aircraft-level comparisons, the dashboard provides a structured approach to exploring airline customer satisfaction.

Beyond visualization, the project highlights the role of data analytics in identifying service performance patterns, supporting operational decisions and improving customer experience.

---

**Author:** [Your Name]

**Tools:** Tableau | Data Analytics | Data Visualization

**Project Category:** Business Intelligence & Customer Experience Analytics

**GitHub:** [Your GitHub Profile](INSERT-GITHUB-PROFILE-LINK)

**Tableau Public:** [View My Tableau Portfolio](INSERT-TABLEAU-PUBLIC-PROFILE-LINK)
