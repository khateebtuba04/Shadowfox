#  In-Depth Air Quality Index (AQI) Analysis of Delhi

##  Project Overview

Air pollution remains one of the most critical environmental and public health challenges in Delhi. Rapid urbanization, increasing vehicular emissions, industrial activities, seasonal weather conditions, and geographical factors contribute significantly to deteriorating air quality.

This project presents an **in-depth analysis of Delhi’s Air Quality Index (AQI)** using pollutant concentration data. The study explores major pollutants, seasonal and temporal trends, pollutant relationships, and environmental insights to better understand Delhi’s air pollution dynamics.

This project was completed as part of the **ShadowFox Data Science Internship – Intermediate Level Task**.

---

##  Project Objectives

The primary objectives of this project are to:

- Analyze pollutant concentration patterns in Delhi
- Identify major pollutants contributing to poor air quality
- Study seasonal and monthly air quality variations
- Explore pollutant relationships through statistical analysis
- Understand temporal pollution trends
- Generate insights to support environmental and public health initiatives

---

##  Research Questions

This project investigates the following research questions:

1. Which pollutants contribute most significantly to poor air quality in Delhi?

2. How does air quality vary across different seasons in Delhi?

3. Which months experience the highest and lowest pollution levels?

4. How do PM2.5 and PM10 concentrations change over time?

5. Are certain pollutants strongly correlated with each other?

6. What temporal trends can be observed in Delhi’s air pollution levels?

7. Which season presents the greatest public health risk due to poor air quality?

8. How can data-driven analysis support environmental policymaking in Delhi?

9. What environmental and geographical factors contribute to AQI deterioration in Delhi?

10. Can pollutant trends help predict periods of severe pollution?

---

## Dataset Information

The dataset contains pollutant concentration measurements recorded in Delhi.

### Dataset Features

| Feature | Description |
|----------|-------------|
| date | Date and time of observation |
| co | Carbon Monoxide concentration |
| no | Nitric Oxide concentration |
| no2 | Nitrogen Dioxide concentration |
| o3 | Ozone concentration |
| so2 | Sulfur Dioxide concentration |
| pm2_5 | Fine particulate matter (PM2.5) |
| pm10 | Coarse particulate matter (PM10) |
| nh3 | Ammonia concentration |

Since the dataset did not contain a direct AQI column, an **AQI Proxy** was created using key pollutant indicators such as PM2.5, PM10, NO₂, and SO₂.

---

##  Technologies Used

The project was developed using the following technologies:

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Jupyter Notebook**

---

##  Project Workflow

The project was completed through the following stages:

### 1. Data Understanding
- Dataset exploration
- Shape and structure analysis
- Missing value inspection
- Duplicate value checking

### 2. Data Cleaning
- Duplicate removal
- Date formatting
- Data preprocessing

### 3. Feature Engineering
- Month extraction
- Seasonal categorization
- AQI proxy generation

### 4. Exploratory Data Analysis (EDA)
The following analyses were performed:

- Average pollutant distribution
- AQI trend over time
- Monthly pollution analysis
- Seasonal AQI variation
- Correlation heatmap
- PM2.5 vs PM10 trend analysis
- AQI distribution analysis
- Statistical summaries

---

##  Visualizations Included

The project contains multiple professional visualizations, including:

- Pollutant Distribution Analysis
- Air Quality Trend Analysis
- Monthly AQI Variation
- Seasonal Pollution Analysis
- Correlation Heatmap
- PM2.5 vs PM10 Trend Comparison
- AQI Distribution Plot

---

##  Key Findings

The study revealed several important findings:

### 1. PM2.5 and PM10 emerged as dominant pollutants
These pollutants exhibited higher concentration levels and stronger influence on Delhi’s air quality patterns.

### 2. Seasonal variation strongly influences air quality
Winter and post-monsoon periods demonstrated comparatively poorer air quality conditions.

### 3. Air quality fluctuates significantly over time
Temporal analysis revealed substantial variation in pollution levels throughout the observation period.

### 4. Pollutants exhibit strong interrelationships
Correlation analysis indicated strong positive relationships among several pollutants.

### 5. High pollution periods may increase public health risks
Poor air quality may contribute to respiratory and cardiovascular health issues.

---

##  Health Impact Analysis

Air pollution can significantly impact public health.

### PM2.5 Risks
- Respiratory diseases
- Lung damage
- Asthma aggravation

### PM10 Risks
- Breathing difficulties
- Reduced lung function

### NO₂ Risks
- Respiratory irritation
- Airway inflammation

### SO₂ Risks
- Breathing discomfort
- Respiratory stress

---

##  Recommendations

### Environmental Recommendations
- Increase urban green cover
- Strengthen industrial emission regulations
- Encourage sustainable transportation

### Public Health Recommendations
- Increase AQI awareness
- Promote preventive healthcare practices
- Encourage safety measures during high pollution periods

### Government Recommendations
- Improve real-time air monitoring
- Implement stricter emission policies
- Promote electric and public transportation

---

##  Limitations of Study

This study includes a few limitations:

- The dataset did not contain an official AQI column.
- AQI was estimated using an AQI proxy.
- Weather and traffic variables were unavailable.
- Geographical station-level information was not included.

Despite these limitations, the study provides meaningful environmental insights.

---

##  Future Scope

Future improvements may include:

- Machine Learning-based AQI prediction
- Real-time AQI monitoring systems
- Weather-integrated pollution analysis
- Geographical hotspot mapping
- Predictive pollution forecasting

---

##  Project Structure

```txt
ShadowFox_Task2_AQI_Delhi
│── data
│   └── delhiaqi.csv
│
│── notebook
│   └── Delhi_AQI_Analysis.ipynb
│
│── images
│   ├── pollutant_distribution.png
│   ├── aqi_trend.png
│   ├── monthly_aqi.png
│   ├── seasonal_analysis.png
│   ├── correlation_heatmap.png
│   ├── pm25_pm10_trend.png
│   └── aqi_distribution.png
│
│── README.md
│── requirements.txt
```

---

##  Conclusion

This project provided an in-depth understanding of Delhi’s air pollution dynamics through statistical analysis and data visualization.

The findings suggest that particulate pollutants such as **PM2.5 and PM10** are major contributors to deteriorating air quality. Seasonal patterns and environmental factors significantly influence pollution levels.

The insights generated from this analysis can support policymakers, environmental agencies, and public health organizations in developing targeted strategies for air quality improvement.

---

##  Author

**Tuba Mariyam Khateeb**  
ShadowFox Data Science Intern