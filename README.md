# A-Data-Driven-Analysis-of-Mental-Health-and-Substance-Abuse-Trends-in-the-United-States
Here’s a detailed write-up of your project based on your role as a Graduate Research Assistant at Indiana University. This version is tailored as if you’re writing it for your data portfolio, specifically aligned with clinical data analyst, healthcare data visualization, and public health research roles:

---

### Mental Health and Substance Abuse Data Analysis (Jan 2024 – May 2025)

**Graduate Research Project | Indiana University – Luddy School of Informatics, Computing and Engineering**
**Tools Used:** Python, R, SQL, Power BI, Microsoft Excel

As part of my graduate research assistantship, I led a comprehensive data analysis initiative focused on mental health and substance abuse across the United States. The project spanned multiple datasets sourced from Kaggle and HealthData.gov, aiming to identify national trends in behavioral health outcomes, socio-demographic risk factors, and treatment accessibility.

#### 1. **Data Acquisition & Integration**

* Collected large-scale datasets from:

  * [HealthData.gov](https://healthdata.gov) – Medicare and Medicaid behavioral health service usage by state.
  * [Kaggle](https://kaggle.com) – Opioid claims, global suicide rates, mental health by demographics, substance abuse mortality, and drug use by age.
* Combined structured and semi-structured data from various formats (CSV, Excel, JSON) and standardized them into analyzable formats using Python’s pandas and NumPy libraries.
* Connected datasets through SQL joins and data keys such as geography (state, country), time (year), and demographic (age, gender).

#### 2. **Data Cleaning & Preprocessing**

* Performed missing value imputation, normalization, and datatype conversions using pandas and R’s `dplyr` and `tidyverse` packages.
* Removed redundant variables and filtered low-quality entries to ensure data accuracy and reduce noise.
* Developed reproducible data pipelines using Jupyter notebooks and R scripts for future scalability.

#### 3. **Exploratory Data Analysis (EDA)**

* Uncovered patterns and correlations across various dimensions such as age, occupation, income, geography, and condition type (e.g., depression, opioid addiction).
* Used statistical methods (correlation analysis, variance analysis) to validate associations between variables like unemployment rate and suicide frequency, or age group and drug dependency trends.

#### 4. **Data Visualization & Storytelling Using Power BI**

Created six separate interactive dashboards to communicate insights effectively to both technical and non-technical stakeholders:

* **Dashboard 1 – Global Suicide Trends**
  Analyzed suicide rates in relation to GDP, employment ratios, and inflation. Highlighted how economic pressures influence mental health outcomes.

* **Dashboard 2 – U.S. Health Beneficiaries and Mental Health**
  Mapped the prevalence of mental health conditions across U.S. states. Used bubble charts and bar graphs to highlight states with the highest concentration of cases.

* **Dashboard 3 – Opioid Prescriptions and Claim Analysis**
  Evaluated opioid claim volume by provider and specialty. Identified prescribers with disproportionately high opioid claim rates for further policy review.

* **Dashboard 4 – Mood and Stress by Demographics**
  Explored occupational and gender-based disparities in mental health, including mood instability and treatment seeking behaviors.

* **Dashboard 5 – Mortality Trends in Self-Harm and Substance Abuse**
  Quantified deaths due to self-harm and substance use by gender, age group, and region. Provided context for where public health interventions are most needed.

* **Dashboard 6 – Drug and Alcohol Use by Age**
  Highlighted how drug preferences and usage frequency shift across age groups. Useful for tailoring prevention strategies by age segment.

#### 5. **Advanced Insights & Impact**

* Identified statistically significant trends such as:

  * Higher suicide rates in regions with lower GDP and employment ratios.
  * Increased opioid claims in specific medical specialties like internal medicine and pain management.
  * Younger populations reported higher hallucinogen and inhalant usage; middle-aged groups leaned toward opioids and alcohol.
* Enabled public health researchers and policymakers to pinpoint high-risk groups and regions, supporting targeted outreach and funding allocation.
* Automated weekly data refresh and reporting pipelines, making dashboards usable in real-time decision-making environments.

---

This project taught me how to manage large-scale epidemiologic datasets, design health-focused dashboards, and extract clinically relevant insights from diverse data sources. It also deepened my ability to connect social determinants of health with real-world clinical outcomes—an essential skill for any healthcare data analyst or public health informatics role.
