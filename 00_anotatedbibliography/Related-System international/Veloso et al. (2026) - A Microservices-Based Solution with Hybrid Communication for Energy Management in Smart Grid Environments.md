# A Microservices-Based Solution with Hybrid Communication for Energy Management in Smart Grid Environments

**Category:** [[Related System international]]

**Artur F. S. Veloso, José V. Reis Jr., and Ricardo A. L. Rabelo. 2026. A Microservices-Based Solution with Hybrid Communication for Energy Management in Smart Grid Environments. *Sensors* 26, 5 (2026), 1714. DOI:https://doi.org/10.3390/s26051714**

- **Summary:** Veloso, Reis, and Rabelo design a modular smart metering and energy management architecture combining ESP32 microcontrollers, SCT-013 current transformer sensors, 16-bit analog-to-digital converters, and dedicated backend microservices to execute telemetry ingestion, automated load profiling, and peak interval detection.

- **Gap:** Although utilizing SCT-013 CT sensors and ESP32 microcontrollers, the backend analytics are restricted to basic peak interval identification and demand profiling, lacking an unsupervised machine learning pipeline (such as Isolation Forest) cross-referenced with academic facility schedules to detect off-hours energy waste.

- **Relevance:** The system architecture demonstrates that pairing ESP32 edge processing with non-invasive current transformer sensors and dedicated ingestion microservices achieves reliable telemetry acquisition with high packet delivery rates, validating the hardware sensing stack and decoupled backend processing required by the proposed system to isolate building-level electrical loads.

- **Source Reference(s):**
  - *Section 3.1 & Section 3.2 (System Architecture and Smart Meter Design):* Implementation of physical smart meter prototypes integrating ESP32-WROOM-32 microcontrollers, SCT-013 current sensors, ZMPT101B voltage modules, and ADS1115 analog-to-digital converters.
  - *Section 3.3 (Microservices Architecture for Data Analysis):* Implementation of independent microservices for telemetry ingestion, load profile generation, and critical peak interval identification.
