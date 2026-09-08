# IoT enabled smart power quality analysis in three phase electrical systems with practical implementation

**Category:** [[Related System international]]

**Balasubbareddy Mallala, Rajasekhar Reddy Manyam, Jagriti Saini, Mohammad Faridun Naim Tajuddin, and Sudhakar Babu Thanikanti. 2025. IoT enabled smart power quality analysis in three phase electrical systems with practical implementation. *Scientific Reports* 15 (2025), 39665. DOI:https://doi.org/10.1038/s41598-025-23317-z**

- **Summary:** Mallala et al. implement an IoT-enabled three-phase electrical telemetry and power quality monitoring platform combining AC current and voltage sensor networks, an ESP32 edge gateway, and cloud dashboard analytics to capture continuous voltage, current, and active power draw.

- **Gap:** The system prioritizes electrical power quality parameters (harmonics, power factor, voltage sag) in industrial three-phase equipment, lacking context-aware occupancy or timetable correlation and machine learning-driven off-hours ghost load auditing.

- **Relevance:** The system verifies that combining multi-channel current and voltage sensors with an ESP32 gateway delivers continuous multi-phase telemetry logging to a centralized dashboard with minimal percentage error, providing technical validation for deploying ESP32 edge sub-metering infrastructure within the proposed system to monitor complex departmental electrical panels.

- **Source Reference(s):**
  - *Section (Materials and methods):* Implementation of sensor acquisition circuits using ACS712 current sensors and ZMPT101B voltage transformers routed through an ESP32-WROOM edge gateway to stream real-time telemetry to the cloud.
  - *Section (Results and discussions):* Practical laboratory validation across multi-phase electrical loads measuring Root Mean Squared Error (RMSE) and percentage error against industrial benchtop power quality analyzers.
