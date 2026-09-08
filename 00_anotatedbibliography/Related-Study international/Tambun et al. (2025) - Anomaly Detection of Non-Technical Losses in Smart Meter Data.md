# Anomaly Detection of Non-Technical Losses in Smart Meter Data Using K-Means Clustering and Isolation Forest: A Case Study From Indonesia

**Category:** [[Related Study international]]

**Rejeki Tambun, Ardyono Priyadi, and Vita Lystianingrum. 2025. Anomaly Detection of Non-Technical Losses in Smart Meter Data Using K-Means Clustering and Isolation Forest: A Case Study From Indonesia. In *2025 26th International Seminar on Intelligent Technology and Its Applications (ISITIA)*. IEEE, 1–6. DOI:https://doi.org/10.1109/ISITIA66279.2025.11137434**

- **Summary:** Tambun, Priyadi, and Lystianingrum address irregular consumption deviations and metering anomalies in smart electrical grids by deploying a hybrid pipeline combining K-Means clustering for baseline behavioral segmentation and Isolation Forest for unsupervised outlier detection.

- **Relevance:** The empirical findings indicate that coupling baseline usage clustering with the Isolation Forest algorithm achieves a 91.54% anomaly detection recall rate, providing direct algorithmic validation for utilizing Isolation Forest within the proposed system's backend to isolate unscheduled electrical deviations and ghost consumption.

- **Gap:** Although the study proves that Isolation Forest achieves high recall (91.54%) in identifying irregular electrical currents and anomalies, it operates as an offline, retrospective simulation within the KNIME desktop analytics platform on historical utility datasets. It lacks an end-to-end real-time IoT architecture (such as ESP32 edge telemetry via MQTT), automated timetable schedule cross-referencing, and an interactive web dashboard. Consequently, the framework cannot detect localized room-level energy waste or deliver instantaneous, actionable off-hours ghost consumption alerts to campus facility personnel.

- **Source Reference(s):**
  - *Section I (Introduction) & Section III (Methodology):* Framework utilizing the KNIME Analytics Platform to execute K-Means clustering and Isolation Forest anomaly scoring on utility CT smart meter telemetry.
  - *Section IV (Results and Discussion):* Empirical evaluation across 2021–2023 utility customer datasets demonstrating that tuned Isolation Forest achieves a 91.54% recall rate on unusual current flows.
  - *Section V (Conclusion):* Summary of machine learning efficacy in detecting non-technical grid losses, emphasizing that the workflow relies on offline utility simulations without live edge sub-metering deployment.
