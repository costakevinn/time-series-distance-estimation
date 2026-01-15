# Time Series Distance Estimation  
**Irregular time series analytics, data pipeline and statistical regression (NASA ADS / arXiv:2311.04470)**

This repository contains the paper PDF and analysis notebooks for a project published on **NASA ADS (arXiv:2311.04470)** focused on building an end-to-end workflow for **irregular time series analysis** and **statistical modeling** using real observational data.

The paper is written in **Portuguese**, but the methodology, algorithms and results follow standard practices in **data science, time series processing and regression modeling**.

---

## 🚀 Project Overview

The goal of this project is to estimate distances using a large catalog of real observations by combining:

- **Irregular time series processing**
- **Period detection** using **Lomb–Scargle periodograms (Astropy)**
- **Phase-folding and feature extraction**
- **Regression modeling** (period–luminosity relation / Leavitt Law)
- **Quality filtering and outlier handling**
- **Validation against reference datasets (OGLE-IV)**

The dataset contains **4,700+ real samples** from the **OGLE-IV** catalog of Classical Cepheid variable stars.

Although the application is astrophysical, this workflow is directly applicable to any domain involving **noisy, irregularly sampled time series** such as finance, IoT, monitoring systems, or operations analytics.

---

## 🧠 Methods and Tools

- **Time Series Analysis (irregular sampling)**
- **Lomb–Scargle Periodogram** (Astropy)
- **Phase-folding / periodic signal transformation**
- **ETL and data cleaning**
- **Statistical regression** (SciPy `curve_fit`)
- **Model validation and benchmarking**
- **Kernel Density Estimation**
- **Python** (NumPy, Pandas, SciPy, Astropy)

---

## 📂 Repository Contents

- **`paper.pdf`**  
  Full scientific paper published on **NASA ADS (arXiv:2311.04470)** *(Portuguese)*

- **`time_series_distance_pipeline.ipynb`**  
  Core notebook implementing the data pipeline, Lomb–Scargle period detection, phase-folding and regression modeling.

- **`equation_43_derivation.ipynb`**  
  Supporting notebook with mathematical and statistical derivations used in the distance estimation method.

---

## 📊 Visual Results

Below are selected figures from the paper and notebooks illustrating the data pipeline and results:

### Lomb–Scargle Periodogram
*(Detecting periodicity in irregular time series)*  
`![Lomb–Scargle](lomb_scargle_spectrum.png)`

### Phase-Folded Time Series
*(Feature engineering from periodic signals)*  
`![Phase Folded](phase_folded_timeseries.png)`

### Regression Model (Period–Luminosity Relation)
*(Supervised regression on real data)*  
`![Regression](regression_model.png)`

### Validation vs Reference Dataset (OGLE-IV)
*(Benchmarking against external results)*  
`![Validation](model_validation.png)`

### Probability Density (Kernel Density Estimation)
*(Distribution of real-world measurements)*  
`![Density](probability_density.png)`

---

## 🔗 Publication

NASA ADS / arXiv:2311.04470  
https://ui.adsabs.harvard.edu/abs/arXiv:2311.04470

> Note: the original publication links to an older GitHub account.  
> This repository is hosted on my current GitHub profile and contains the paper PDF and the associated notebooks.

---

## 🎯 Why this is relevant for Data & Machine Learning Engineering

This project demonstrates real-world experience with:

- **Large, noisy datasets**
- **Irregular time series**
- **Data pipelines and preprocessing**
- **Statistical modeling and regression**
- **Model validation and benchmarking**
- **Reproducible notebook-based analysis**

These are core skills required for **Machine Learning Engineers, Data Scientists and Data Engineers** working with production data.

---

## 👤 Author

**Kevin Mota da Costa**  
Time Series • Statistical Modeling • Data Pipelines • Python
