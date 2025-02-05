# **Social Determinants of Health (SDOH) Dashboard**

## **Project Overview**
This project analyzes the **impact of social determinants of health (SDOH) on healthcare access and health outcomes** across California. By visualizing key metrics such as **poor health rates, healthcare professional shortage areas (HPSA scores), air quality, obesity, and food access**, this dashboard provides **data-driven insights to inform policy decisions and healthcare interventions**.

The **SDOH Dashboard** uses **data analysis and visualization** to examine how **demographics, healthcare access, and environmental factors** impact health outcomes, highlighting disparities in **high-Hispanic, low-access areas**.

![SDOH Overview](https://github.com/rubythedev/social-determinants-of-health/blob/main/SDOH_Overview.png)

## **Dataset**
The dataset integrates multiple **public health and environmental data sources**, covering **2,585 ZIP codes across California**.

### **Key Data Sources**
- **Social Determinants of Health (SDOH) Dataset** → Demographic indicators, uninsured rates.
- **HPSA (Healthcare Professional Shortage Area) Scores** → Measures healthcare access.
- **Air Quality Index (AQI) Data** → Environmental impact on public health.
- **County Health Rankings (CHR)** → Health outcomes (obesity, physical inactivity, food environment index).

## **Project Link**
🔗 [SDOH Analytics Dashboard](https://public.tableau.com/app/profile/ruby.nunez/viz/SocialDeterminantsofHealth_17387310659210/HRSummary?publish=yes)

## **Project Objectives**
- Identify **health disparities across ZIP codes and counties**.
- Analyze the **relationship between social determinants and health outcomes**.
- Examine **the impact of healthcare access (HPSA) on preventable hospitalizations**.
- Assess **the role of environmental factors (air quality, food access) on health risks**.
- Provide **data-driven recommendations for healthcare policies and interventions**.

---

## **Methodology**
### **1. Data Preparation**
- **Cleaned and integrated multiple datasets** to ensure consistency.
- **Merged ZIP code and county-level data** for geographic harmonization.
- **Handled missing values** to maintain dataset integrity.

### **2. Exploratory Data Analysis (EDA)**
- **Analyzed county-level poor health rates and healthcare shortages**.
- **Mapped environmental health risks (AQI, food access) to obesity rates**.
- **Examined demographic factors (ethnicity, language barriers) in relation to uninsured rates and poor health**.

### **3. Data Visualization & Insights**
- **Developed interactive Tableau dashboards** to explore relationships between health outcomes and SDOH.
- **Color-coded insights**:
  - 🔴 **Red** = **Poor Health Outcomes** (High % Fair/Poor Health, High Obesity, High Physical Inactivity, High Preventable Hospitalizations).
  - 🔵 **Blue** = **Limited Healthcare Access** (High HPSA Score, High % Uninsured, Low Access to Exercise).

---

## **Key Visual Representations**
### **1️⃣ Overview: Health Outcomes & Healthcare Access**
- **📊 % Fair or Poor Health by County**
  - `PCT_FAIR_POOR_HEALTH` (🔴 Red)
- **📈 % Fair or Poor Health vs. HPSA Score**
  - `MEDIAN_HPSA_SCORE` (🔵 Blue) vs. `PCT_FAIR_POOR_HEALTH` (🔴 Red)

### **2️⃣ Demographics: Who is Most Affected?**
- **📊 Ethnicity Breakdown & Poor Health**
  - `ACS_PCT_HISPANIC_ZC` vs. `PCT_FAIR_POOR_HEALTH` (🔴 Red)
- **📈 Language Barriers vs. HPSA Score**
  - `ACS_PCT_ENGL_NOT_ALL_ZC` vs. `MEDIAN_HPSA_SCORE` (🔵 Blue)
- **📈 Median Age vs. % Adults with Obesity**
  - `ACS_MEDIAN_AGE_ZC` vs. `PCT_ADULTS_OBESE` (🔴 Red)

### **3️⃣ Healthcare Analytics: Identifying Gaps**
- **📊 Air Quality vs. HPSA Score**
  - `MEDIAN_AQI` vs `MEDIAN_AQI` (🔵 Blue)
- **📈 % Adults with Obesity vs. Food Environment Index**
  - `FOOD_ENV_INDEX` vs. `PCT_ADULTS_OBESE` and `PCT_FAIR_POOR_HEALTH` (🔴 Red)
---

## **Key Findings**
### **1️⃣ Demographic & Language Barriers**
- **Higher Hispanic population and English proficiency barriers** correlate with **higher rates of poor health**.
- Areas with **more non-English speakers have higher HPSA scores**, indicating limited healthcare access.

### **2️⃣ Environmental & Food Access Impact**
- **Counties with worse air quality (higher AQI) tend to have higher HPSA scores**, indicating that **environmental risks align with healthcare shortages**.
- **Areas with limited access to healthy food (lower food environment index) have higher obesity rates**.

### **3️⃣ Age & Obesity Trends**
- **Median age is negatively associated with obesity rates**, meaning **younger populations experience higher obesity levels**.

### **4️⃣ Healthcare Shortages & Poor Health**
- **Counties with poor health outcomes have high HPSA scores**, indicating that **limited healthcare access is a significant factor in worsening health conditions**.

---

## **Recommendations**
### **1️⃣ Address Healthcare Access Disparities**
✅ **Expand healthcare facilities in high-HPSA score areas** to reduce preventable hospitalizations.  
✅ **Improve language accessibility** in healthcare services for **non-English-speaking communities**.  

### **2️⃣ Environmental & Preventive Health Interventions**
✅ **Enhance air quality monitoring** in high-HPSA score areas to reduce health risks.  
✅ **Expand access to fresh and affordable food options** in low food environment index regions.  
✅ **Increase funding for public exercise facilities** to address physical inactivity.  

### **3️⃣ Policy & Public Health Initiatives**
✅ **Allocate healthcare funding to ZIP codes with high uninsured rates and poor health outcomes**.  
✅ **Implement targeted obesity prevention programs** in younger populations.  
✅ **Leverage community partnerships** to improve food access, healthcare outreach, and preventive care.  

---

## **Conclusion**
This analysis highlights **critical health disparities** linked to **demographics, healthcare access, environmental risks, and food accessibility**. By addressing these **social determinants of health**, policymakers and healthcare providers can develop **targeted interventions** to improve **health equity and accessibility**.

**This dashboard serves as a data-driven tool for healthcare professionals and policymakers, reinforcing the need for proactive healthcare strategies.**

---

## **Future Directions**
📌 **Integrate additional datasets** to track health trends over time.  
📌 **Apply machine learning models** to predict future healthcare needs based on SDOH factors.  
📌 **Expand the analysis to other states** to assess nationwide health disparities.  
