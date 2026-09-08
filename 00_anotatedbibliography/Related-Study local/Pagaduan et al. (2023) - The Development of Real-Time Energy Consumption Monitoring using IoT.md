# The Development of Real-Time Energy Consumption Monitoring using IoT

**Category:** [[Related Study local]]

**Lyndel Jean L. Pagaduan, Jhobert G. Portolazo, Jounariz Xavier D. Delfin, John Pablo O. Dela Cruz, and Micah Bambie O. Estanda. 2023. The Development of Real-Time Energy Consumption Monitoring using IoT. *Advanced Computational Intelligence: An International Journal* 10, 3 (2023), 13–24. DOI:https://doi.org/10.5121/acii.2023.10302**

- **Summary:** Pagaduan et al. design and evaluate an IoT telemetry architecture using current sensors and cloud databases to track real-time electrical draw, employing the Input-Process-Output developmental framework to mitigate excessive power consumption in Philippine facilities.

- **Gap:** The implementation relies on multi-board hardware chaining to upload raw current readings to a third-party IoT service (ThingSpeak), functioning solely as a passive numeric logger that lacks institutional database integration, machine learning anomaly detection, and academic timetable cross-referencing to isolate unscheduled off-hours ghost consumption.

- **Relevance:** The study confirms that structuring hardware telemetry and cloud ingestion under the Input-Process-Output framework delivers responsive, real-time power tracking, directly validating the architectural development lifecycle employed by the proposed system to capture and visualize institutional load data.

- **Source Reference(s):**
  - *Section 1 (Introduction) & Section 3 (Methodology & IPO Framework, pp. 21–24):* Application of the Input-Process-Output (IPO) lifecycle model integrating non-invasive current sensing inputs, microcontroller processing, and cloud database outputs.
  - *Section 4 & Section 5 (Project Development and Results, pp. 24–27):* Hardware configuration using an SCT-013 sensor, Arduino Uno, and Raspberry Pi 3 sending telemetry to ThingSpeak, evaluated across 50 respondents for real-time monitoring and reporting functionality.
