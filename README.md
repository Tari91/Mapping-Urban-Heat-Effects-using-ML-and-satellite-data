# 🌆 Urban Heat Mapping using Machine Learning and Synthetic Satellite Data

This project simulates the mapping of Urban Heat Island (UHI) effects using machine learning and synthetic satellite data features like NDVI, NDBI, albedo, and land cover. A regression model is trained to predict Land Surface Temperature (LST), a proxy for urban heat impact.

---

## 📁 Files

- `urban_heat_synthetic_data.xlsx` – Contains the synthetic dataset with satellite features and target (LST).
- `urban_heat_model.py` – Python script to generate data, train the model, and visualize results.
- `README.md` – Project overview and usage instructions.

---

## 📊 Features Included

- **NDVI** – Normalized Difference Vegetation Index
- **NDBI** – Normalized Difference Built-up Index
- **Albedo** – Surface reflectance
- **Land Cover** – Categorical encoded class (e.g., vegetation, urban, water)
- **LST** – Land Surface Temperature (target for prediction)

---

## 🧠 ML Model

- Algorithm: `RandomForestRegressor` (from scikit-learn)
- Task: Regression to predict LST based on synthetic features
- Evaluation: R² score, RMSE, feature importance

---

## 🚀 How to Run

1. **Install dependencies:**

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
Run the model script:

bash


python urban_heat_model.py
Output:

Trained ML model

Scatter plot: Actual vs Predicted LST

Feature importance bar chart

Excel file with synthetic data

📦 Output
The generated Excel file contains:

NDVI	NDBI	Albedo	Land_Cover	LST (K)
0.67	0.21	0.31	1	301.2
...	...	...	...	...

📌 Notes
Data is synthetic and does not reflect real-world conditions.

For real applications, integrate with Earth observation sources (e.g., Sentinel-2, MODIS, or Google Earth Engine).

📧 Author
Tarinabo williamtarinabo@gmail.com
