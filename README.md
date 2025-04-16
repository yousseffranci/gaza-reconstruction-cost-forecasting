# 🏗️ Gaza Reconstruction Cost Forecasting (2025–2026)

**Forecasting Construction Costs and Carbon Emissions by Building Typology in the Gaza Strip – A Post-Conflict Data-Driven Framework**

![Gaza Construction Forecast](https://img.shields.io/badge/Status-Research--Backed-blueviolet) ![Python](https://img.shields.io/badge/Built%20With-Python-blue) ![License](https://img.shields.io/badge/License-MIT-green)  

---

## 📘 Overview

This project provides a **localized, typology-based forecasting model** to estimate **construction costs and embodied carbon emissions** in Gaza for the 2025–2026 rebuilding phase. It integrates:

- 📊 Historical cost indices (2014–2024)
- 🧱 Typology-specific material intensity datasets
- 📈 Time series forecasting (Holt’s Linear, Holt-Winters methods)
- 🌍 Carbon footprint simulation by structure

> Developed as part of an MSc Research Project at King’s College London  
> **Author:** Youssef A. Francia — *Supervised by Dr. Mohit Arora*

---

## 🧩 Key Features

✨ **Typology-Aware Simulation**  
Simulates cost & carbon for structures like single-family homes, multi-family low-rise, vertical apartments, and emergency prefab shelters.

📈 **Time-Series Forecasting**  
Predicts construction material/labor/equipment costs using exponential smoothing models.

🧮 **Carbon Emissions Analysis**  
Estimates embodied CO₂ per square meter using standard emission factors and uplift scenarios.

🛠️ **Scenario Modeling**  
Supports multiple recovery scenarios (e.g., high inflation, donor-backed rebuilding).

---

## 📂 Repository Structure

📁 gaza-reconstruction-cost-forecasting/ │ ├── 📊 cost_estimation.ipynb # Forecasting time-series indices (2014–2024) ├── 📐 bill_of_materials.ipynb # Typology-based cost and CO2 simulations │ ├── 📄 forecasted_costs_2025.csv # Predicted 2025 costs across categories ├── 📄 Cleaned_Monthly_Skeleton_2014_2024.csv # Historical PCBS index data ├── 📄 mena_building_typology_dataset_2025.csv # Typology + material intensities │ └── 📘 README.md # You’re here!

---

## 🔍 Example Outputs

### 💵 Material Costs per m² (USD)
| Typology                    | Cost (USD/m²) | Total (USD)   |
|----------------------------|---------------|---------------|
| SFH – Concrete (1 floor)   | 325.48        | $32,548       |
| MFH – Low-Rise (3 floors)  | 308.22        | $147,946      |
| MFH – Vertical (10 floors) | 295.60        | $354,720      |
| Pre-Fab Emergency Shelter  | 188.40        | $9,420        |

### ♻️ Embodied CO₂ Emissions (kg/m²)
| Typology                    | CO₂ (kg/m²)   | Total CO₂ (kg) |
|----------------------------|---------------|----------------|
| SFH – Concrete             | 435.3         | 43,530         |
| MFH – Low-Rise             | 422.1         | 202,608        |
| MFH – Vertical             | 410.4         | 492,480        |
| Pre-Fab Emergency Shelter  | 162.9         | 8,145          |

---

## 🧠 Methodologies

- 📉 **Holt’s Linear Trend & Holt-Winters Models** for cost forecasting
- 🏗️ **Material intensity modeling** per typology
- 🧾 **Dynamic scenario multipliers** for inflation & conflict-adjusted volatility
- 🌐 **Embodied carbon calculation** using lifecycle emission factors

---

## 🌍 Use Cases

- 📌 Local authorities & urban planners
- 🤝 Humanitarian NGOs & donors
- 🧪 Academic researchers in reconstruction economics & sustainability
- 💡 Civil/Structural engineers in post-conflict regions

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

This work was supported by the **Institution of Structural Engineers (IStructE)** under the MSc Research Grant program.

---

## 📬 Contact

**Youssef A. Francia**  
📧 youssef.a.franci@kcl.ac.uk  
🎓 MSc Engineering with Management| King’s College London  

---
