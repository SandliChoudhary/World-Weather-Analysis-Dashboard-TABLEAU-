# 🌍 World Weather Dashboard — Tableau Project

## 🧩 Introduction  
This project focuses on the analysis and visualization of global weather data collected from May 2024 to March 2025 using Tableau. Weather and air quality indicators are key in understanding the ongoing changes in our climate and their impacts on different regions of the world.

The main objective of this project is to examine how temperature, precipitation, and major air pollutants such as Carbon Monoxide (CO), Sulphur Dioxide (SO₂), and Nitrogen Dioxide (NO₂) vary across countries and months. These insights help reveal trends in environmental conditions and support awareness of climate patterns globally.

To represent this data effectively, several individual Tableau sheets were designed, including Map, Temperature, Precipitation, Correlation, and Monthly Analysis. Each sheet highlights a unique aspect of the data—such as spatial distribution, temporal trends, or relationships between weather and pollutants.

All these sheets were combined into a single interactive dashboard, allowing users to explore and compare global weather parameters intuitively.
Overall, the World Weather Dashboard serves as a comprehensive and visually engaging tool that enables users to observe key climate trends, identify extreme conditions, and analyze the connection between temperature and air quality across different countries.
---

## ❓ Problem Statement  
> Climate data collected from multiple countries is often vast, complex, and highly variable, making it challenging to identify clear patterns or relationships among key environmental factors. The challenge lies in analyzing global weather data (May 2024 – March 2025) to uncover meaningful insights about temperature, precipitation, and air pollution. This project aims to visualize and interpret how these factors vary across regions and over time, highlighting the hottest and coldest areas, monthly climate fluctuations, and the impact of pollutants such as CO, SO₂, and NO₂ on weather conditions.
> **Goal:** To analyze and visualize global weather data (May 2024 – March 2025) and identify temperature trends, rainfall distribution, and pollutant patterns such as CO, SO₂, and NO₂ using Tableau.

---

## 🔬 Research Questions & Key Findings  

🔍 Research Questions and Findings

1. **How do average temperature levels vary across countries and months, and which regions experience the most extreme climatic conditions?**
Countries such as Saudi Arabia, Morocco, and India showed the highest average temperatures, while European and North American regions experienced lower temperature ranges. Seasonal patterns showed warmer months from June to August and cooler months from December to February.

2. **What are the global trends in precipitation, and how do rainfall patterns differ between tropical, temperate, and arid regions?**
Tropical regions recorded the heaviest rainfall, while arid regions had minimal precipitation. Seasonal shifts indicated higher rainfall in mid-year months and drier periods towards the end of the year.

3. **How do air pollutants such as Carbon Monoxide (CO), Sulphur Dioxide (SO₂), and Nitrogen Dioxide (NO₂) differ in concentration across countries and seasons?**
Pollution levels were highest in industrial and densely populated regions, particularly for NO₂ and SO₂. Cleaner air was found in less industrialized regions. Colder months showed slightly higher pollution levels due to heating and industrial activity.

4. **Is there a measurable relationship between air pollution levels and temperature variations across different regions?**
A negative correlation was found between temperature and nitrogen dioxide (NO₂) levels — higher temperatures often coincided with lower pollution. This suggests that warmer climates may promote pollutant dispersion, reducing atmospheric concentration.

5. **How can an interactive Tableau dashboard be used to effectively visualize, compare, and interpret global weather and pollution data?**
By using calculated fields, parameters, and filters, the dashboard allowed users to interactively explore data. It helped users identify monthly, regional, and pollutant-based patterns in an engaging and analytical manner.

---

## 🧾 Dataset Description  
- **Source:** [Global Weather Repository — Kaggle](https://www.kaggle.com/datasets/salhirahma/global-weather-repository)  
- **Period:** May 2024 – March 2025  
- **Variables Included:**  
  - Average Temperature (°C)  
  - Precipitation (mm)  
  - Carbon Monoxide (CO)  
  - Sulphur Dioxide (SO₂)  
  - Nitrogen Dioxide (NO₂)  
  - Wind Direction, Weather Condition, etc.  

---

## ⚙️ Data Preprocessing  
- The dataset was **clean and complete** — no missing or duplicate entries.  
- Added **calculated fields** and **interactive parameters** to enhance Tableau analysis.  
- Focused on **data enrichment** and **interactivity**, not cleaning.

---

## 📈 Steps Performed in Tableau  
1. **Map Sheet:**  
   - Displayed global data using country coordinates.  
   - Filters: *wind direction, weather condition, month*.  

2. **Temperature & Precipitation Sheets:**  
   - Visualized variations by month and region.  
   - Used dynamic filters for comparison.  

3. **Air Quality Sheets (CO, SO₂, NO₂):**  
   - Individual pollutant visualizations.  
   - Compared changes by season and geography.  

4. **Monthly & Correlation Analysis:**  
   - Combined measures to show monthly variation.  
   - Used parameters for *dynamic comparison*.  

---

## 💡 Insights & Findings  
- **Hottest Regions:** Saudi Arabia, Morocco, India  
- **Coolest Regions:** North America, Europe  
- **Rainfall:** Heavy in tropical, low in desert zones  
- **Pollution:** High NO₂ & SO₂ in industrial regions  
- **Key Trend:** Temperature and NO₂ show *negative correlation*  

---

## 🧠 Conclusion  
The **World Weather Dashboard** combines **data visualization** and **environmental analytics** to present a clear view of climate and air quality.  
By integrating **calculated fields, parameters, and filters**, users can interactively explore global patterns and relationships between temperature, precipitation, and pollutants.

---

## 🧮 Tools Used  
- **Tableau Public** — for visualization  
- **Kaggle** — data source  
- **Excel / CSV** — for dataset inspection  

---

## 🧰 Future Enhancements  
- Include **real-time weather data** using APIs  
- Add **humidity**, **wind speed**, and **pressure** indicators  
- Improve dashboard UI with more **animated visualizations**

---


