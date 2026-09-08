# Performance Analysis of MQTT and HTTP Protocols on Low-Power ESP32 Devices for IoT Applications

**Category:** [[Related Study international]]

**Syahrul Adriansyah, Sumarno, Ulya Mutiara Nurfuha, Abidzar Giffari, Tsulsi Khoirunisa, and Winky Gunsan Subarkah. 2026. Performance Analysis of MQTT and HTTP Protocols on Low-Power ESP32 Devices for IoT Applications. *CoreID Journal* 4, 1 (2026), 38–45. DOI:https://doi.org/10.60005/coreid.v4i1.160**

- **Summary:** Adriansyah et al. evaluate transport protocol efficiency on ESP32 microcontrollers by measuring latency, packet overhead, and power draw between MQTT publish-subscribe streams and HTTP client-server architectures across IoT networks.

- **Relevance:** The empirical findings indicate that MQTT achieves 4.76× to 12.1× lower transmission latency and consumes 6% to 8% less power than HTTP on ESP32 hardware, providing empirical validation for selecting MQTT ingestion protocols to minimize data latency in the proposed system.

- **Gap:** Although the study provides comprehensive empirical validation that MQTT achieves substantially lower data latency (4.76× to 12.1× faster) and higher power efficiency than HTTP on ESP32 microcontrollers, it is strictly confined to a transport-layer protocol evaluation and Systematic Literature Review. It lacks physical current transformer (CT) sub-metering hardware deployment, a persistent time-series database pipeline (such as PostgreSQL), automated machine learning anomaly detection (such as Isolation Forest), and integration with institutional room-scheduling data. Consequently, the study cannot measure actual electrical parameters, detect off-hours ghost consumption, or provide campus facility administrators with an operational, sub-panel monitoring web dashboard.

- **Source Reference(s):**
  - *Section 2 (Method, pp. 39–41):* Systematic Literature Review protocol based on PRISMA 2020 guidelines evaluating empirical studies of ESP32 microcontrollers under MQTT and HTTP communication architectures.
  - *Section 3 (Results and Discussion, Subsection 3.3.1 & 3.3.2, pp. 41–44):* Comparative analysis demonstrating HTTP response times 4.76× to 12.1× higher than MQTT under fog and cloud server deployments, alongside 6% to 8% energy savings for MQTT.
  - *Section 4 (Conclusion, pp. 44–45):* Concluding synthesis confirming MQTT's superiority for low-latency, resource-constrained ESP32 IoT implementations while noting the necessity for practical implementations across large-scale physical deployments.
