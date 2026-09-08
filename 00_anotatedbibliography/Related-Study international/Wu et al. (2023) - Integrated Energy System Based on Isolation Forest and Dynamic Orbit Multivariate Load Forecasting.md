# Integrated Energy System Based on Isolation Forest and Dynamic Orbit Multivariate Load Forecasting

**Category:** [[Related Study international]]

**Shidong Wu, Hengrui Ma, Abdullah M. Alharbi, Bo Wang, Li Xiong, Suxun Zhu, Lidong Qin, and Gangfei Wang. 2023. Integrated Energy System Based on Isolation Forest and Dynamic Orbit Multivariate Load Forecasting. *Sustainability* 15, 20 (2023), 15029. DOI:https://doi.org/10.3390/su152015029**

- **Summary:** Wu et al. address multi-energy load forecasting errors in campus infrastructure by applying an Isolation Forest outlier filtering pipeline to high-dimensional sliding window matrices, thereby isolating anomalous electrical telemetry before feeding data into baseline models.

- **Gap:** Isolation Forest is utilized solely as an offline data-scrubbing filter to clean historical training datasets for deep neural network forecasting rather than as an active surveillance tool, lacking live edge IoT telemetry, operational web alerting, and institutional schedule cross-referencing to flag real-time off-hours ghost consumption.

- **Relevance:** The empirical findings indicate that pre-filtering high-dimensional sensor telemetry with Isolation Forest isolates irregular consumption deviations from baseline load profiles, which directly supports implementing Isolation Forest algorithms in the proposed system's backend to flag unscheduled off-hours ghost consumption.

- **Source Reference(s):**
  - *Section 1 (Introduction) & Section 3 (Methodology):* Mathematical formulation of the Isolation Forest algorithm applied to multi-energy load matrices to filter outliers and repair corrupted points before neural network training.
  - *Section 4 (Case Study & Results):* Empirical validation using offline telemetry datasets from the Arizona State University Tempe campus, focusing on multi-task forecasting accuracy (TCN-MMoL) rather than live anomaly alerting.
