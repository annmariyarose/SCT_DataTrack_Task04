# SCT_DataTrack_Task04
📊 US Accident Analysis – SkillCraft Task 4 


This project is part of my internship at **SkillCraft Technology**, where I analyzed a large-scale U.S. accident dataset to uncover meaningful insights about accident patterns based on **road conditions**, **weather**, **time of day**, and **location hotspots**.

---

## 🗂️ Dataset

- **Source**: [US Accidents (Kaggle)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **Size**: ~4 million records (2016–2023)
- **File used**: `US_Accidents_March23.csv`
- Contains 47 columns with data such as:
  - Location: Latitude, Longitude, City, State
  - Time: `Start_Time`, `End_Time`
  - Road Conditions: `Bump`, `Junction`, `Traffic_Signal`, etc.
  - Weather Metrics: Temperature, Wind, Visibility, Precipitation
  - Accident Severity (1 to 4)

---

## 🎯 Objective

- Analyze accident frequency across different **hours of the day**
- Investigate the role of **weather** and **road features** in accident occurrence
- Create an interactive **heatmap of accident hotspots**
- Understand key contributing factors to high-severity incidents

---

## 🛠️ Tools Used

- **Python**
- **Pandas** – data handling
- **Seaborn & Matplotlib** – charts and visualizations
- **Folium** – interactive maps

---

## 📈 Visual Outputs

- 🕒 **Accidents by Hour of Day**  
- 🌧️ **Top 10 Weather Conditions During Accidents**  
- 🚦 **Road Feature Impact** – e.g., Bumps, Signals, Junctions  
- 🗺️ **Heatmap of Accident Hotspots** (saved as `accident_hotspots_map.html`)
