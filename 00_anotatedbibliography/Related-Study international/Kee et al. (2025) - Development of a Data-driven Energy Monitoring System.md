# Development of a Data-driven Energy Monitoring System for Power Consumption and Power Quality Monitoring

**Category:** [[Related Study international]]

**Owen Kwong-Hong Kee, Keh-Kim Kee, Ching Yee Yong, Ramli Rashidi, and Tsu Hsiung Lo. 2025. Development of a Data-driven Energy Monitoring System for Power Consumption and Power Quality Monitoring. *Journal of Renewable Energy and Smart Grid Technology* 20, 2 (2025), 163–175. DOI: https://doi.org/10.69650/rast.2025.263660**

- **Summary:** Kee et al. address the lack of real-time granularity and analytical capability in conventional energy meters by engineering an IoT monitoring platform using ESP32 microcontrollers and current transformer sensors to capture telemetry across multi-tiered edge and cloud environments.

- **Gap:** Event classification is governed by static rule-based threshold engines focused on electrical power quality disturbances (voltage fluctuations and harmonics), lacking unsupervised machine learning and institutional timetable cross-referencing to isolate behavioral energy waste and unscheduled off-hours ghost consumption.

- **Relevance:** The experimental evaluation confirms that pairing ESP32 microcontrollers with non-invasive current sensors delivers accurate telemetry with minimal measurement error compared to commercial meters, directly supporting the hardware data-acquisition tier implemented in the proposed system.

- **Source Reference(s):**
  - *Section 1 (Introduction) & Section 2 (System Architecture):* Design of a multi-tiered Data-Driven Energy Monitoring System (DDEMS) coupling ESP32 edge processing with SCT-013 current sensors and cloud analytics.
  - *Section 2.3 & Section 3 (Rule Engine & Results, pp. 166–174):* Implementation of a cloud-based rule engine based on IEEE 1159/IEC 61000-4-30 power quality standards, validated against Lovato DMG800 and Fluke 437-II analyzers with 1.24% MAPE.
