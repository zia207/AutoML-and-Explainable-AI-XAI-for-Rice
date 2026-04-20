# Geospatial & Explainable AI Analysis of Rice Yield (Aman, Aus, Boro)

This repository contains R Markdown analyses exploring **rice yield** across three major seasons in Bangladesh (or similar regions): **Aman**, **Aus**, and **Boro**. The project combines **geospatial correlation analysis**, **Automated Machine Learning (AutoML)** for yield prediction, and **local Explainable AI (XAI)** techniques.

## 📁 Project Structure

### Geospatial Correlation Analysis
- `gw_correlation_aman_01.Rmd` / `.html` — Geographically Weighted Correlation (Aman Season - Part 1)
- `gw_correlation_aman_02.Rmd` / `.html` — Geographically Weighted Correlation (Aman Season - Part 2)

### Local Explainable AI (XAI) Analysis
- `local_XAI_uniion_aman.Rmd` / `.html` — Local XAI for Aman season (Union level)
- `local_XAI_uniion_aus.Rmd` / `.html`  — Local XAI for Aus season (Union level)
- `local_XAI_uniion_boro.Rmd` / `.html` — Local XAI for Boro season (Union level)

### AutoML Yield Prediction Models
- `yield_aman_autoML.Rmd` / `.html` — AutoML modeling and prediction for Aman rice yield
- `yield_aus_autoML.Rmd` / `.html`  — AutoML modeling and prediction for Aus rice yield
- `yield_boro_autoML.Rmd` / `.html` — AutoML modeling and prediction for Boro rice yield

### Others
- `test/` — Test scripts and temporary files

## 📊 Project Overview

This repository focuses on:

- **Geographically Weighted Correlation** to understand spatial variation in relationships affecting rice yield.
- **AutoML** approaches for accurate yield prediction in different rice seasons.
- **Local Explainable AI (XAI)** to interpret model predictions at the union level, providing insights into which factors drive yield in specific locations.

The analyses are particularly relevant for **precision agriculture**, **food security**, and **climate-smart rice farming** in regions with distinct seasonal patterns (Aman, Aus, Boro).

## 🛠 Technologies Used

- **R** & **R Markdown**
- **Geographically Weighted Models** (GW correlation)
- **AutoML** frameworks (likely h2o, AutoML, or similar)
- **Explainable AI** techniques (SHAP, LIME, or local interpretability methods)
- HTML outputs for easy viewing and sharing of results

## 📖 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
