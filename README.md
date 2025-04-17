# 🏗️ Gaza Reconstruction Cost Forecasting (2025–2026)

**Forecasting Construction Costs and Embodied Carbon Emissions by Building Typology in the Gaza Strip**  
_A Post-Conflict Data-Driven Framework_

![Status](https://img.shields.io/badge/Status-Active-blueviolet)
![Built with](https://img.shields.io/badge/Built%20With-Python-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Google%20Cloud%20%26%20Colab-yellow)

---

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/thumb/4/40/King%27s_College_London_seal.svg/1024px-King%27s_College_London_seal.svg.png" alt="King's College London" width="140"/>
</p>

> 🔎 **This repository is in addendum to**  
> 📝 **_Forecasting Construction Costs and Carbon Emissions by Building Typology in the Gaza Strip – A Post-Conflict Data-Driven Framework_**  
> 📚 This project is **ancillary to a Master’s Thesis** currently in development at **King’s College London**  
> 🧑‍🎓 MSc Individual Research | Department of Engineering | Supervised by **Dr. Mohit Arora**

---

## ☁️ Cloud & Notebook Compatibility

This repository is built for reproducibility, scalability, and interactivity:

- **Google Cloud Platform** for compute and dataset scalability
- **Google Colab** notebooks for quick, browser-based execution

<p align="left">
  <a href="https://colab.research.google.com/github/YOUR-REPO-PATH/blob/main/notebooks/cost_estimation.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>
  </a>
</p>

---

## 📘 Summary

This project develops a modular and localized simulation model to estimate 2025–2026 construction costs and CO₂ emissions for rebuilding efforts in the Gaza Strip.

It includes:

- 🏗️ Typology-specific cost simulations
- 📈 Time-series forecasting (2014–2024)
- ♻️ Carbon emissions modeling per material per typology
- 🔁 Scenario testing under conflict volatility

---

## 📂 Repository Structure

```
📁 gaza-reconstruction-cost-forecasting/
│
├── notebooks/
│   ├── cost_estimation.ipynb              # Time series modeling (Holt & Holt-Winters)
│   └── bill_of_materials.ipynb            # Typology simulation: cost & CO₂
│
├── data/
│   ├── Cleaned_Monthly_Skeleton_2014_2024.csv
│   ├── forecasted_costs_2025.csv
│   └── mena_building_typology_dataset_2025.csv
│
├── visuals/
│   └── trends_comparative.png             # Graphical outputs for material cost evolution
│
└── README.md
```

---

## 🧠 Methodology Summary

- 🕒 **Holt’s Linear & Holt-Winters Forecasting**: Trends + seasonality captured from PCBS indices
- 🧱 **Material Intensity Modeling**: Based on RASMI & MENA references
- ⚙️ **Conflict Adjustment Factors**: Reflect volatility in Gaza supply chain
- 🌿 **Embodied Carbon Estimation**: Lifecycle-based calculations by typology
- 📊 **Scenario Planning**: Multi-pathway modeling (baseline, moderate recovery, donor-boosted, etc.)

---

## 💵 Forecasted Outputs (2025)

| Typology                    | Cost (USD/m²) | Total Cost (USD) | CO₂ (kg/m²) | Total CO₂ (kg) |
|----------------------------|---------------|------------------|-------------|----------------|
| SFH – Concrete             | $325.48       | $32,548          | 435.3       | 43,530         |
| MFH – Low-Rise             | $308.22       | $147,946         | 422.1       | 202,608        |
| MFH – Vertical             | $295.60       | $354,720         | 410.4       | 492,480        |
| Pre-Fab Emergency Shelter  | $188.40       | $9,420           | 162.9       | 8,145          |

---

## 🔍 Use Cases

- 🧱 **Engineers**: Building-level planning, BoQ estimation
- 🧑‍💼 **NGOs**: Cost-effective allocation, post-war procurement
- 📊 **Policymakers**: Emissions tradeoffs & typology strategies
- 🎓 **Researchers**: Carbon intensity & conflict-zone modeling
- 🏗️ **Developers/Planners**: Scenario-aware reconstruction blueprints

---

## 📜 License

This repository is distributed under the **MIT License**.  
See [`LICENSE`](./LICENSE) for more information.

---

## 🙏 Acknowledgements

Developed at **King’s College London** as part of the MSc Individual Research Project.  
This research was partially supported by the **Institution of Structural Engineers (IStructE)** MSc Research Grant.  
All conclusions are those of the author and do not necessarily reflect the views of IStructE or King’s College.

---

## 📬 Contact

**Youssef A. Francia**  
✉️ [youssef.a.franci@kcl.ac.uk](mailto:youssef.a.franci@kcl.ac.uk)  
🎓 MSc Candidate, Department of Engineering, King’s College London

> _“Rebuilding Gaza demands tools that are not only technical — but ethical, empirical, and empowering.”_
