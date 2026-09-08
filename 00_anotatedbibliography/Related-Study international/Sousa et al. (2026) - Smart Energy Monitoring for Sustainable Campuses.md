# Smart Energy Monitoring for Sustainable Campuses: A Hybrid Anomaly Detection Approach Based on Prophet and Isolation Forest

**Category:** [[Related Study international]]

**Ângelo Sousa, Pedro J. S. Cardoso, and Jânio Monteiro. 2026. Smart Energy Monitoring for Sustainable Campuses: A Hybrid Anomaly Detection Approach Based on Prophet and Isolation Forest. *Sustainability* 18, 5 (2026), 2589. DOI:https://doi.org/10.3390/su18052589**

- **Summary:** Sousa, Cardoso, and Monteiro address campus electrical inefficiencies by deploying a telemetry platform that pairs time-series forecasting with the Isolation Forest algorithm to identify consumption irregularities across heterogeneous institutional meters.

- **Gap:** The anomaly detection pipeline relies on statistical forecast residual deviations (Prophet combined with Isolation Forest) at the whole-building level, lacking integration with institutional academic timetables and class schedules to distinguish legitimate scheduled activities from unauthorized off-hours ghost consumption at localized sub-panel circuits.

- **Relevance:** The empirical findings demonstrate that isolating residual variance between baseline load models and real-time meter telemetry enables accurate anomaly identification, directly justifying the integration of Isolation Forest algorithms within the proposed system's backend to flag unscheduled off-hours energy waste.

- **Source Reference(s):**
  - *Section 1 (Introduction) & Section 3 (Methodology):* Implementation of a campus-scale electricity monitoring system at the University of Algarve integrating IoT meter telemetry with a hybrid Prophet and Isolation Forest anomaly detection pipeline.
  - *Section 4 (Validation and Metrics):* Evaluation of model residual variance across 33 temporal cutoffs using Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and Weighted Average Percentage Error (WAPE).
