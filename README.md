# UIDAI Hackathon 2026 – Aadhaar Enrolment & Update Trends Analysis

This project is developed as part of the **UIDAI Data Hackathon 2026**.  
The objective of this analysis is to understand Aadhaar enrolment and update
patterns across India using official UIDAI datasets, and to derive insights
that can support better service delivery and administrative decision-making.

---

## Problem Statement

Aadhaar enrolment and update activities vary significantly across states,
districts, and age groups. Understanding these variations is essential for:

- Identifying high-demand regions
- Improving enrolment and update infrastructure
- Planning targeted awareness and outreach programs

This project focuses on analysing enrolment, demographic updates, and biometric
updates to uncover meaningful trends and patterns.

---

## Datasets Used

The analysis uses official datasets provided by UIDAI as part of the hackathon,
including:

- Aadhaar Enrolment Data  
- Demographic Update Data  
- Biometric Update Data  

Each dataset contains records at state, district, and pincode level with age-wise
breakdowns.

> **Note:** Due to dataset size and usage constraints, raw UIDAI datasets are not
uploaded to this repository.

---

## Methodology

1. Combined multiple UIDAI CSV files into consolidated datasets
2. Cleaned and standardised column names and data formats
3. Created derived metrics such as:
   - Total enrolments
   - Total demographic updates
   - Total biometric updates
4. Performed:
   - State-level analysis
   - District-level analysis
   - Age group-wise analysis
5. Visualised key findings using charts and plots

---

## Key Insights

- States like **Uttar Pradesh, Maharashtra, and Bihar** show the highest Aadhaar
  activity due to large population and frequent update requirements
- Biometric updates are significantly higher than enrolments, indicating strong
  demand for post-enrolment services
- The **0–5 age group** contributes the highest number of enrolments, highlighting
  the importance of early Aadhaar registration
- Certain districts show unusually high update activity, indicating potential
  service load concentration

---

## Visualisations

The project includes multiple visualisations such as:

- Top 10 states by enrolment
- Top 10 states by demographic updates
- Top 10 states by biometric updates
- District-level comparison charts
- Age group-wise Aadhaar activity

These visualisations are included in the final presentation PDF.

---

## Project Structure

├── notebook/
│ └── Aadhaar_Enrollment_Update_Analysis.ipynb
│
├── presentation/
│ └── Aadhaar_Enrollment_Update_Trends_Analysis.pdf


---

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab

---

## Impact & Applicability

The insights from this analysis can help UIDAI and related authorities to:

- Allocate enrolment and update resources more efficiently
- Identify regions requiring additional centres or manpower
- Improve planning for demographic and biometric update campaigns

---

## Author

**Ankur Pal**  
UIDAI Data Hackathon 2026 Participant
