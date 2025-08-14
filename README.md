
# Lake Eutrophication Prediction using Synthetic Satellite-Derived Chlorophyll-a Data

## 📌 Project Overview

This project demonstrates the prediction of **lake eutrophication levels** (oligotrophic, mesotrophic, eutrophic) using **synthetic satellite-derived water quality parameters**.
It leverages **machine learning** to model the relationship between chlorophyll-a, water temperature, Secchi depth, and total phosphorus concentration to estimate nutrient enrichment and potential harmful algal bloom risk.

---

## 📊 Features

* **Synthetic Data Generation** mimicking satellite reflectance-derived chlorophyll-a concentrations
* **Classification** of eutrophication levels based on nutrient thresholds
* **Random Forest Model** for robust prediction
* **Feature Importance Analysis** to identify key drivers of eutrophication
* **Excel Export** of synthetic dataset for further GIS or ML use

---

## 🗂 Dataset Description (Synthetic)

| Feature               | Unit  | Description                                                      |
| --------------------- | ----- | ---------------------------------------------------------------- |
| Chlorophyll\_a        | mg/m³ | Satellite-derived pigment concentration indicating algae biomass |
| Water\_Temperature    | °C    | Lake surface temperature from remote sensing                     |
| Secchi\_Depth         | m     | Water clarity measurement                                        |
| Total\_Phosphorus     | µg/L  | Nutrient concentration driving algae growth                      |
| Eutrophication\_Level | Class | 0 = Oligotrophic, 1 = Mesotrophic, 2 = Eutrophic                 |

---

## ⚙️ Installation & Requirements

Ensure you have **Python 3.8+** installed with the following dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn openpyxl
```

---

## 🚀 How to Run

1. Clone this repository or copy the script.
2. Install dependencies.
3. Run the Python script:

```bash
python lake_eutrophication_prediction.py
```

4. View:

   * Model accuracy & classification report in the terminal
   * Feature importance chart
   * Saved Excel file: `synthetic_lake_eutrophication_data.xlsx`

---

## 📈 Output Examples

* **Model Accuracy** & **Confusion Matrix**
* **Feature Importance Chart** showing chlorophyll-a as the strongest predictor
* **Excel Dataset** for GIS integration

---

## 🌍 Relevance to Sustainability

Predicting eutrophication helps in **water quality monitoring**, **aquatic biodiversity protection**, and **early warning systems** for harmful algal blooms.
This approach supports **SDG 6 – Clean Water and Sanitation**.

---

## 📜 License

MIT License – Free for academic, research, and commercial use.


