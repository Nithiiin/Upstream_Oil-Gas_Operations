# Upstream Oil & Gas Operations: Data Processing and Machine Learning

This repository focuses on data analysis and machine learning applications in the upstream oil and gas sector. It provides resources and examples for processing industry-specific data formats, exploratory analysis, and predictive modeling to optimize drilling operations.

---

## Repository Contents

### 1. **Data Files**
- **`16_81_PT1_PR.SGY`**: Seismic survey data in SEG-Y format for geophysical analysis.
- **`DDR.xml`**: Daily Drilling Report in XML format, providing hierarchical operational data.
- **`ROP_data.csv`**: Data on Rate of Penetration (ROP) and associated drilling parameters.
- **`Well_log.LAS`**: Well log data in LAS format for subsurface property analysis.
- **`drilling_bit_data.csv`**: Drilling bit specifications and performance metrics.

### 2. **Jupyter Notebooks**
#### a. **`different_data_type_working.ipynb`**
   - Demonstrates handling and preprocessing of various data formats used in the oil and gas industry:
     - SEG-Y: Seismic survey data processing with `segyio`.
     - LAS: Well log data parsing using `lasio`.
     - XML: Daily drilling reports parsed with `xml.etree.ElementTree`.
   - Techniques applied:
     - Data cleaning (missing value imputation, outlier removal).
     - Exploratory Data Analysis (EDA) to uncover patterns and anomalies.

#### b. **`machine_learning.ipynb`**
   - Implements supervised machine learning to optimize drilling performance:
     - **Target**: Predict **Rate of Penetration (ROP)**.
     - **Features**: Weight on Bit (WOB), Flow Rate, Wellhead Pressure, and others.
   - Key methodologies:
     - Data preprocessing with domain-aware thresholds (e.g., ROP limited to 0-300 ft/hr).
     - Anomaly detection using **Elliptic Envelope**.
     - Supervised regression models to improve ROP prediction accuracy.

---

## Features
- **Industry-Specific Data Handling**: Provides workflows for SEG-Y, LAS, XML, and CSV data formats.
- **Exploratory Data Analysis**: Offers visualizations and insights to guide operational decisions.
- **Predictive Modeling**: Enhances drilling efficiency through data-driven approaches.

---
