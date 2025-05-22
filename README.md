# ChennaiFloodMappingML

A research project that combines **machine learning** and **spatial data** to predict and visualize flood-prone zones in Chennai, India. This work was carried out as part of my postgraduate research (In Second Semester) and is especially designed to help citizens and real estate decision-makers understand flood risks in various wards of Chennai.

---

## 📌 About the Project

- 🧪 **Type**: Academic Research Project (MCA, VIT Chennai)
- 🏙️ **Focus Area**: Chennai Metropolitan Area
- 💻 **Tech Stack**: Python, Scikit-learn, TensorFlow, Pandas, Folium
- 📊 **Models Used**:
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - Deep Neural Network (DNN)

---

## 📌 Custom Dataset

Unlike existing studies that rely on precompiled datasets, this project used a **self-created dataset** combining:

- Chennai ward-level spatial data
- Historical rainfall and cyclone data
- Elevation and proximity to rivers (Adyar, Cooum, Kosasthalaiyar)
- Water level data from past flood events

This custom dataset is key to localized and accurate flood risk prediction.

---

## 🌍 Output: Flood Risk Map

Flood zones were visualized using **Folium** in interactive maps. You can view:

- 🔴 `FloodMapRedZone.html`: Wards with **high flood risk**
- 🟠 `FloodMapOrangeZone.html`: Wards with **moderate flood risk**

These maps help inform safer real estate planning and disaster preparedness.

Below is a sample output showing high flood risk zones in Chennai:


![Flood Map Screenshot](Output_Screenshots/RedZones.png)
![Flood Map Screenshot](Output_Screenshots/OrangeZones.png)


(Interactive maps are available in the repo as `.html` files.)

---

## 📈 Model Performance

| Model              | MAE   | MSE    |
|-------------------|-------|--------|
| Decision Tree      | 3.331 | 18.365 |
| Random Forest      | 2.896 | 11.270 |
| Gradient Boosting  | 2.976 | 11.715 |
| Neural Network     | 3.231 | 13.956 |

---

## 🚀 Future Work

- Integrating **real-time weather APIs**
- Adding **GIS layers** (roads, drainage)
- Using LSTM for time-series flood forecasting

---

