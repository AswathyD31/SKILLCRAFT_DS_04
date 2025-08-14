# **Data Science Internship at Prodigy Infotech**

## **Task 4 Submission:**
-----

This project is part of Task 4 of my Data Science Internship at SkillCraft Technology.
The objective was to perform data cleaning, preprocessing, and exploratory data analysis (EDA) on a global road accident dataset to uncover trends, identify major contributing factors, and generate actionable recommendations for improving road safety.

## Dataset Description
____________

The dataset contains detailed records of road accidents with the following key columns:

* **Accident_Severity** – Categorized as Minor, Moderate, or Severe.

* **Weather_Condition** – Conditions during the accident (Clear, Rain, Fog, Snow, etc.).

* **Road_Condition** – Dry, Wet, Icy, or Other.

* **Light_Condition** – Daylight, Night with lighting, Night without lighting.

* **Alcohol_Level** – Driver alcohol concentration category.

* **Fatigue_Involvement** – Whether driver fatigue was involved.

* **Traffic_Volume** – Number of vehicles on the road during the incident.

* **Cause** – Primary cause (e.g., Drunk Driving, Speeding, Distracted Driving).

* **Location** – Region and country where the accident occurred.

* **Vehicles_Involved** – Number of vehicles in the accident.

* **Injuries / Fatalities** – Casualties in the accident.

* **Economic_Loss** – Estimated financial damage.

* **Response_Time** – Emergency service arrival time.

## Tools and Libraries Used
__________________

* **Pandas** – Data cleaning & manipulation

* **NumPy** – Numerical computations

* **Matplotlib** – Visualization

* **Seaborn** – Statistical plots

* **Plotly** – Interactive visualizations

* **Jupyter Notebook** – Interactive analysis

## **Data Cleaning Process**
-------

* **Handled Missing Values** – Checked and addressed missing entries.

* **Removed Duplicates** – Eliminated repeated accident records.

* **Outlier Treatment** – Applied IQR method for capping extreme values in numerical columns.

### **Encoding** –

* **Binary encoding** for Yes/No features (Fatigue_Involvement)

* **One-hot encoding** for categorical variables (Weather_Condition, Accident_Severity, etc.)

* **Feature Formatting** – Ensured correct data types for numerical columns like Economic_Loss, Traffic_Volume, and Response_Time.

## Exploratory Data Analysis
____________

The following analyses were conducted:

* Accident severity distribution across different weather and road conditions.

* Impact of alcohol level on accident severity.

* Role of driver fatigue in accident frequency.

* Traffic volume influence on accident occurrence.

* Leading causes of accidents by count.

* Geographical analysis – accident hotspots by region and country.

* Injuries vs. economic loss patterns by accident severity.

* Emergency response time trends by accident severity.

## Hotspot Map

An interactive hotspot map was created using Folium to visualize accident density across the United States.

👉 Preview:![Hotspot Map](https://github.com/AswathyD31/SKILLCRAFT_DS_04/blob/da2bdbc81acd6f1ee7b188bb1966004dad09767b/Accident%20Hotspots%20by%20Country.JPG)

## Visualizations
 __________

* Bar charts for accident causes.

* Count plots for weather and road condition comparisons.

* Heatmaps for feature correlations.

* Scatter plots for injuries vs. economic loss.

* Geographic charts for top accident hotspots.

* Boxplots for response time distribution by severity.

## Key Insights
___________

* Alcohol Level – Even moderate alcohol levels are linked to both minor and severe accidents.

* Fatigue – A major contributor, with accident counts reaching up to 60,000 in fatigue-related cases.

* Traffic Volume – Higher traffic volumes strongly correlate with increased accident frequency.

* Cause Analysis – Drunk and distracted driving lead accident causes, exceeding weather or mechanical failures.

* Geography – Accident rates are evenly distributed globally at a continental level, but country-level hotspots exist.

* Economic Impact – Severe accidents cause disproportionately higher economic losses.

* Response Time – Not always correlated with accident severity, indicating possible inefficiencies in emergency services.

## **Conclusion**

This analysis highlights human behavior factors (alcohol, fatigue, distraction) as the dominant causes of accidents over environmental conditions.
Findings can help policymakers, traffic authorities, and emergency services prioritize prevention strategies and optimize resource allocation for better road safety outcomes.

🙏 **Acknowledgement**

Thank you for reviewing my submission for Task 4 of the SkillCraft Technology Data Science Internship.
