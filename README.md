# 🌃 Illuminating Recovery: Nighttime Lights for Post-Disaster Energy Monitoring

This repository contains data processing scripts, analysis notebooks, and interactive dashboards developed for the project:

**"Illuminating Recovery: Using Nighttime Lights to Rethink Energy Restoration After Disasters"**

## 🔍 Project Overview
This project explores the use of **satellite-based Nighttime Lights (NTL)**—specifically NASA’s Black Marble product—as a scalable proxy for tracking **post-disaster electricity access**, particularly in regions with limited or delayed utility data.

While traditional grid metrics often reflect infrastructure restoration, they fail to capture whether **households have truly regained power**, especially in **remote, resettled, or underserved communities**.

## 📦 Contents

- `notebooks/` – Jupyter notebooks for cleaning, processing, and analyzing NTL and NGCP data  
- `data/` – Processed datasets (time series, rolling averages, merged NTL-grid files)  
- `html_outputs/` – Plotly-based visualizations and dashboards  
- `images/` – Figures used in reports or presentations  
- `scripts/` – GEE exports, time series builders, and automation scripts

## 🚀 Key Features

- 🔁 Rolling average and correlation analysis (Pearson R) between NTL and grid output  
- 🌐 Interactive dashboard with region toggles, disaster markers, and smoothing controls  
- 📊 Visual tracking of power restoration across major island groups in the Philippines  
- 🔎 Designed to be **adaptable for Australian use cases** under disaster contexts (e.g. cyclones, bushfires)

## 🛰️ Data Sources

- **NASA Black Marble VNP46A2** (500m, daily)  
- **NGCP Hourly Load Reports** (1AM demand)  
- [Optional: Resettlement site shapefiles, ADM boundaries from GEE]

## 📄 License

MIT License. Please cite or acknowledge if reused in research or policy work.

## ✏️ Authorship & Tools

Developed by **Rene L. Principe Jr.**  
PhD Candidate, Geospatial Sciences, RMIT University

> *ChatGPT was used to assist with grammar refinement, structural clarity, and organization of ideas.*
