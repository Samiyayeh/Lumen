# A Review of Edge Computing Technology and Its Applications in Power Systems

**Category:** [[Related Literature international]]

**Shiyang Liang, Shuangshuang Jin, and Yousu Chen. 2024. A Review of Edge Computing Technology and Its Applications in Power Systems. *Energies* 17, 13 (2024), 3230. https://doi.org/10.3390/en17133230**

- **Summary:** Liang, Jin, and Chen examine edge computing paradigms across smart power systems, reviewing edge-to-cloud communication architectures, low-latency telemetry protocols, and localized anomaly detection models deployed on microcontroller hardware.

- **Relevance:** The literature validates the edge-processing tier of the proposed system, demonstrating that pre-processing sub-meter signals directly on ESP32 microcontrollers prior to cloud ingestion reduces telemetry latency and eliminates server network bottlenecks.

- **Gap:** While the review confirms that edge computing reduces telemetry latency and cloud bandwidth bottlenecks, the literature highlights resource constraints on low-power microcontrollers when executing analytical models. Specifically, existing power system architectures lack lightweight partitioning that combines non-invasive edge sensor telemetry with backend anomaly detection. Without this separation, monitoring setups struggle to balance low latency with computational feasibility, hindering the continuous tracking of localized off-hours electrical waste.

- **Source Reference(s):**
  - _Section 2 (Edge Computing Architecture in Power Systems, pp. 3–6):_ Surveys hierarchical topologies connecting low-power IoT microcontrollers with centralized backend database infrastructures.
  - _Section 4 (Data Processing and Anomaly Detection, pp. 9–13):_ Analyzes the performance trade-offs between local microcontroller preprocessing and server-side machine learning execution.
  - _Section 6 (Future Opportunities and Challenges, pp. 16–18):_ Emphasizes the need for lightweight edge-to-cloud partitioning in low-cost institutional electrical monitoring deployments.
