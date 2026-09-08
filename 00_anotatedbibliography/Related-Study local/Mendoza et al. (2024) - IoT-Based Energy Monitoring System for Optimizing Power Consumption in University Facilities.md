# IoT-Based Energy Monitoring System for Optimizing Power Consumption in University Facilities

**Category:** [[Related Study local]]

**Ronieto N. Mendoza, Joss Elmar B. Monton, and Jeffrey T. Dellosa. 2024. IoT-Based Energy Monitoring System for Optimizing Power Consumption in University Facilities. In *2024 8th International Artificial Intelligence and Data Processing Symposium (IDAP)*. IEEE, 1–6. DOI:https://doi.org/10.1109/IDAP64064.2024.10710764**

- **Summary:** Mendoza, Monton, and Dellosa address localized power waste in Philippine academic facilities by deploying an IoT hardware telemetry pipeline using ACS712 current sensors and ESP8266 microcontrollers to transmit real-time electrical draw to a cloud repository for facility-level energy evaluation.

- **Gap:** The architecture relies on human-in-the-loop manual remote switching through a web GUI rather than automated anomaly detection, and it lacks institutional class schedule cross-referencing to autonomously distinguish between authorized instructional usage and unscheduled off-hours ghost consumption.

- **Relevance:** The empirical results indicate that deploying room-level sub-circuit current telemetry achieves measurement accuracy within ±1.5%, providing engineering justification for the localized edge sensing layer of the proposed system while demonstrating the necessity of upgrading to non-invasive CT clamps and automated schedule-aware analytics.

- **Source Reference(s):**
  - *Section I (Introduction) & Section III (System Architecture):* Design and deployment of an IoT-based sub-metering infrastructure for Caraga State University facilities using ACS712 sensors, ESP8266 microcontrollers, Firebase cloud storage, and manual GUI power relays.
  - *Section IV (Performance Evaluation & Results):* Experimental validation of hardware sensor accuracy yielding a ±1.5% measurement error margin across active loads, alongside an explicit note regarding the omission of voltage sensors.
