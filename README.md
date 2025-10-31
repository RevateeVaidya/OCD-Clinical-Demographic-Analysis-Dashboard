## OCD Clinical Demographic Analysis Dashboard

## Project Overview

This data analysis project utilizes Power BI to explore a dataset detailing clinical and demographic information of patients diagnosed with Obsessive-Compulsive Disorder (OCD). The objective was to transform raw, patient-level data into actionable insights, helping to uncover patterns in disease presentation, demographic risk, and treatment efficacy.


## Key Features of the Dashboard

Demographic Segmentation: Dynamic filtering and visualizations showing symptom prevalence segmented by Age, Gender, and other relevant demographic variables.

Clinical Severity Mapping: Analysis of Y-BOCS scores mapped against duration of illness and treatment types.

Symptom Subtype Hierarchy: Visual ranking of the most common obsessions (e.g., contamination, symmetry) and compulsions (e.g., checking, washing).

Interactive Filtering: Allows clinicians and researchers to drill down into specific patient cohorts to compare outcomes.


## Tools & Technologies Used

Data Cleaning & Modeling: Excel, Power Query (M Language), DAX

Visualization & Reporting: Power BI Desktop


## Executive Summary: 

Clinical & Demographic Analysis of OCD Patients
This analysis, spanning demographic, clinical, and treatment data, reveals critical patterns regarding patient presentation, comorbidity, and potential gaps in care for the Obsessive-Compulsive Disorder patient cohort.

## I. Demographics and Severity Profile
The patient cohort analyzed is complex and presents with a high degree of illness severity and comorbidity. Over 59% of the patients fall into the Severe or Moderate-Severe Y-BOCS categories, indicating a population that requires specialized and intensive therapeutic intervention.

Comorbidity is the norm, not the exception: The data indicates that over 51% of patients have a co-occurring Depression diagnosis, and 50% have an Anxiety diagnosis. This high rate of psychiatric comorbidity emphasizes the need for integrated treatment models that address both OCD and co-occurring mood/anxiety disorders simultaneously.

In terms of underlying risk, a strong familial component is evident, with 50.67% of the patients reporting a family history of OCD. Interestingly, patients without a family history are more heavily represented in the Extreme severity category, potentially pointing toward a subset of cases driven by non-genetic or environmental factors. Finally, while OCD impacts all age groups relatively equally, analysis by ethnicity shows that Hispanic and African populations have a higher percentage in the 'High School' only education group, suggesting potential socioeconomic disparities in care access that warrant further investigation.

## II. Clinical Presentation and Trends
The dashboard clearly identifies the most prevalent clinical symptoms, which should serve as primary targets for intervention. The top obsessions are Harm-related (22.2%) and Symmetry (20.4%), highlighting the need for clinicians to skillfully manage distress related to intrusive thoughts. The resulting most frequent compulsions are Washing (21.4%) and Checking (21.07%), which represent the key behavioral targets for Exposure and Response Prevention (ERP) therapy.

Historical trend analysis showed that OCD severity peaked in 2018, followed by a gradual decline in the most severe categories since 2020. This could suggest improved diagnostic processes or increased effectiveness of treatments implemented in the post-2018 period.

## III. Treatment Gaps and Medication Usage
Analysis of treatment pathways reveals critical areas of potential under-treatment. Medication usage (SSRI, SNRI, Benzodiazepine) is appropriately concentrated in the Moderate and Moderate-Severe patient groups.

However, a significant finding is the treatment gap observed in patients with Depression: 55.70% of patients with a co-occurring Depression diagnosis were reported as having No Medication. Given that Depression can significantly hinder OCD treatment success, this high percentage of non-medicated depressed patients represents a critical area where integrated care protocols should be enforced to improve overall patient outcomes.

In contrast, patients with a known family history of OCD are slightly more likely to be on medication, suggesting greater clinical proactivity when a familial risk factor is present.



## Dashboard Preview

images/OCD- Demographics and Insights_1.jpeg

images/OCD- Clinical Severity_2.jpeg

images/OCD- Treatment_3.jpeg


## How to Use

1. Download the Power BI file from the repository.
2. Open it with Power BI Desktop.
3. Explore interactive visualizations and insights.

## Repository Structure

- `images/` — Stored screenshots and documentation images here.
- `Clinical & Demographic Analysis of OCD patients.pbix/` — Project raw file.
- `README.md` — Project overview and documentation.


