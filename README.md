# Shifting Tides: Finnish Public Opinion on NATO (2020–2025)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-%23150458.svg)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-%233776AB.svg)](https://seaborn.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An end-to-end data analytics project exploring how public opinion and societal resilience in Finland evolved during the critical geopolitical transition into NATO (2020–2025).

---

## 📌 Project Overview
This portfolio project analyzes multi-year institutional microdata to track the historic shift in Finnish national security sentiment. Moving from pre-war skepticism to post-accession consensus, the project processes official survey data to uncover underlying trends across demographics, defense confidence, and international cooperation.

* **Data Source:** Official annual surveys from the **Finnish Social Science Data Archive (FSD)** (Series: FSD349, FSD3606, FSD3676, FSD3752, FSD3856, FSD3955, FSD4066).
* **Timeframe:** 2020–2025.

---

## 🛠️ Tech Stack & Methodology
* **Data Processing & Cleaning:** Python (`Pandas`, `NumPy`)
* **Data Visualization:** `Matplotlib`, `Seaborn`
* **Methodological Rigor:** 
  * Applied official respondent weights (`PAINO`) to accurately reflect Finland's national population structure.
  * Filtered out missing values and ambiguous responses (`"Can't say"`) to ensure transparent and reliable percentage calculations and average scores.

---

## 📊 Key Findings & Insights
1. **The Great Flip (2021–2022):** In 2021, skepticism and opposition heavily outweighed support for NATO. Following the geopolitical shifts in 2022, public opinion rapidly inverted, establishing a stable majority above 50% through 2025.
2. **Generational Shift:** While younger demographics initially showed higher uncertainty, by 2025 solid majorities across all age groups—particularly seniors (56+)—aligned in strong support of the alliance.
3. **Resilience & Defense:** By 2025, public confidence in national defense reached a high score of **4.24 out of 5**, reflecting strong societal resilience and trust in national security measures.

---

## 📂 Repository Structure
```text
├── Evolution of Finnish Defense Sentiment (2020–2025).pptx     # Final slide deck (.pptx)
├── README.md                                                   # Project documentation
└── finland_security_opinion_analysis.ipynb                     # Jupyter Notebook with full data pipeline and analysis
