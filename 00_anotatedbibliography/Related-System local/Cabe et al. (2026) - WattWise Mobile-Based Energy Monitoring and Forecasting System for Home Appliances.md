# WattWise: Mobile-Based Energy Monitoring and Forecasting System for Home Appliances

**Category:** [[Related System local]]

**Euller Grifien A. Cabe, Mark Angelo Florendo, Jordan Gonzales, Vivien Agustin, and Ronald Fernandez. 2026. WattWise: Mobile-Based Energy Monitoring and Forecasting System for Home Appliances. *International Journal of Research and Scientific Innovation* 13, 6 (2026), 30–42. DOI:https://doi.org/10.51244/IJRSI.2026.1306000030**

- **Summary:** Cabe et al. develop WattWise, an IoT energy monitoring and predictive management platform integrating ESP32 microcontrollers, PZEM-004T measurement modules, a lightweight Python Flask backend API, and a centralized dashboard for real-time electrical draw tracking and time-series load forecasting.

- **Gap:** The architecture is engineered specifically for single-phase residential plug loads with consumer forecasting, lacking multi-circuit sub-panel distribution metering, institutional role-based access control, and context-aware timetable integration required for campus facility auditing.

- **Relevance:** The system architecture confirms that integrating ESP32 edge telemetry with a Python Flask REST API and cloud time-series persistence provides responsive electrical consumption monitoring, directly supporting the technical design of the proposed system's edge-to-backend data ingestion pipeline.

- **Source Reference(s):**
  - *Section 2 & Section 3 (System Architecture & IoT Hardware):* Edge data collection utilizing the ESP32 microcontroller paired with PZEM-004T power sensors transmitting voltage, current, and wattage data to a Flask backend API.
  - *Section 4 (Predictive Modeling & Dashboard Results):* Implementation of time-series predictive analytics and real-time dashboard visualization evaluated for tracking electrical consumption trends and expenditure estimation.
