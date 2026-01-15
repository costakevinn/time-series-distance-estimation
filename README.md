# Time Series Distance Estimation  
**Irregular time series analytics, data pipeline and statistical regression (NASA ADS / arXiv:2311.04470)**

This repository contains the PDF and notebooks for a project published on **NASA ADS (arXiv:2311.04470)** focused on building an end-to-end workflow for **irregular time series analysis** and **statistical modeling** using real observational data.

The paper is written in **Portuguese**, but the methodology, figures and results follow standard practices in **data analytics, time series processing and regression modeling**.

---

## 🚀 Project Overview

Goal: estimate distances using a large catalog of observations by combining:

- **Irregular time series processing**
- **Period detection** using **Lomb–Scargle periodogram (Astropy)**
- Feature extraction from periodic signals (phase-folding)
- **Regression modeling** (period–luminosity / Leavitt Law) using **SciPy (curve_fit)**
- Quality filtering and outlier handling to improve model reliability
- Validation by comparing results with the **OGLE-IV** reference catalog

Dataset scale: **4709** Classical Cepheid variable stars from the **OGLE-IV** catalog.

While the application is astrophysical, the workflow is directly transferable to any domain involving **noisy and irregularly sampled time series** (e.g., sensors/IoT, finance, operations, monitoring).

---

## 🧠 Techniques & Tools

- **Time Series Analysis (irregular sampling)**
- **Lomb–Scargle Periodogram** (Astropy)
- **Phase-folding / periodic signal transformation**
- **ETL / data preprocessing**
- **Regression and curve fitting** (SciPy `curve_fit`)
- **Model validation and benchmarking** (comparison vs OGLE-IV)
- **Python** (NumPy, Pandas, SciPy, Astropy)

---

## 📂 Repository Contents

- **`paper.pdf`**  
  Full paper published on **NASA ADS / arXiv:2311.04470** *(Portuguese)*

- **`time_series_distance_pipeline.ipynb`**  
  Notebook covering the core workflow: data processing, Lomb–Scargle period estimation, phase-folding and regression modeling.

- **`equation_43_derivation.ipynb`**  
  Notebook with supporting mathematical and statistical derivations used in the distance estimation method.

---

## 🔗 Publication

- NASA ADS / arXiv:2311.04470  
  https://ui.adsabs.harvard.edu/abs/arXiv:2311.04470

> Note: the original publication links to an older GitHub account.  
> This repository is hosted on my current GitHub profile and includes the paper PDF and the accompanying notebooks.

---

## 🎯 Why this is relevant for Data / ML Engineering

This project demonstrates practical experience with:

- Building data workflows for **large real-world datasets**
- Working with **irregular and noisy time series**
- Applying **statistical modeling and regression** to extract reliable parameters
- Performing **validation against reference datasets**
- Delivering results through **reproducible notebooks and documented outputs**

---

## 👤 Author

**Kevin Mota da Costa**  
Time Series • Statistical Modeling • Data Pipelines • Python
