# Electricity Misuse With Pzem Anomaly Detection and Notification

**Category:** [[Related System local]]

**Ian Glenn B. Adana, Lovennia Khaye P. Zorilla, Yzyl S. Domingo, and Lloyd O. Arenas. 2026. Electricity Misuse With Pzem Anomaly Detection and Notification. *American Journal of Smart Technology and Solutions* 5, 1 (2026), 1–11. DOI:https://doi.org/10.54536/ajsts.v5i1.7719**

- **Summary:** Adana et al. develop an IoT energy monitoring and anomaly notification platform that integrates PZEM-004T power measurement sensors with ESP32 microcontrollers and a web-based dashboard to perform per-room electrical telemetry acquisition, detect irregular load misuse, and issue automated alerts.

- **Gap:** Anomaly detection is constrained to basic per-room threshold exceedance and current spikes, lacking multi-dimensional time-series machine learning algorithms and timetable cross-referencing to determine whether detected power draw occurs during authorized room reservations or unauthorized off-hours periods.

- **Relevance:** The system confirms that deploying ESP32 microcontrollers and PZEM-004T telemetry hardware for localized load tracking successfully isolates abnormal electrical draw and informs facility managers through web dashboards, providing practical engineering validation for the edge sensing and room-level anomaly alerting mechanisms designed within the proposed system.

- **Source Reference(s):**
  - *Section 2 & Section 3 (System Architecture & Hardware Assembly):* Hardware implementation integrating PZEM-004T current and power sensors with ESP32 microcontrollers to collect and transmit live telemetry to a centralized web dashboard.
  - *Section 4 (Results and Field Evaluation):* Real-world field deployment at the Mar-Lee Apartment in General Santos City evaluating per-room consumption tracking, anomaly detection notification accuracy, and user acceptability across usability and reliability metrics.
