# A Survey on IoT-Enabled Smart Grids: Emerging, Applications, Challenges, and Outlook

**Category:** [[Related Literature international]]

**Arman Goudarzi, Farzad Ghayoor, Muhammad Waseem, Shah Fahad, and Issa Traore. 2022. A Survey on IoT-Enabled Smart Grids: Emerging, Applications, Challenges, and Outlook. *Energies* 15, 19 (2022), 6984. https://doi.org/10.3390/en15196984**

- **Summary:** Goudarzi et al. provide a comprehensive survey on IoT-enabled energy management systems, reviewing telemetry network architectures, lightweight messaging protocols, and data security mechanisms across distributed smart metering environments.

- **Relevance:** The literature analyzes the low latency and bandwidth efficiency of MQTT messaging pipelines in multi-point sub-metering, providing architectural justification for the communication protocols and telemetry encryption used in the proposed system.

- **Gap:** While the survey highlights the low-latency and bandwidth efficiency of lightweight IoT communication protocols like MQTT across smart grids, it emphasizes that existing IoT telemetry frameworks are largely engineered for macro-utility distribution rather than localized institutional sub-metering. Furthermore, the literature identifies persistent vulnerabilities in telemetry payload encryption, device authentication, and data pipeline scalability on resource-constrained microcontrollers, lacking integrated models that combine secure edge-to-cloud transport with automated, context-aware anomaly detection at the sub-panel level.

- **Source Reference(s):**
  - _Section 2 (IoT Architecture for Energy Systems) & Section 3 (Communication Protocols):_ Compares IoT messaging protocols, confirming MQTT as the optimal standard for high-frequency, low-bandwidth electrical telemetry streams.
  - _Section 5 (Data Security and Integrity):_ Examines role-based access control and payload encryption standards needed to safeguard institutional energy logs against unauthorized manipulation.
