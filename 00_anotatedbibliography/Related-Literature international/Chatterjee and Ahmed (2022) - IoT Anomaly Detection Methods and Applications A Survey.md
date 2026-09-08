# IoT Anomaly Detection Methods and Applications: A Survey

**Category:** [[Related Literature international]]

**Ayan Chatterjee and Bestoun S. Ahmed. 2022. IoT Anomaly Detection Methods and Applications: A Survey. *Internet of Things* 19 (2022), 100568. https://doi.org/10.1016/j.iot.2022.100568**

- **Summary:** Chatterjee and Ahmed survey state-of-the-art anomaly detection methodologies across IoT sensor ecosystems, categorizing machine learning algorithms, unsupervised models, and telemetry drift challenges in smart facility environments.

- **Relevance:** The comparative analysis demonstrates that unsupervised anomaly detection models effectively evaluate multi-dimensional time-series sensor streams without extensive manual data labeling, directly supporting the Isolation Forest backend architecture chosen for the proposed system.

- **Gap:** While the survey benchmarks machine learning anomaly detection techniques across IoT domains, the literature highlights critical operational constraints: complex deep learning models cause processing bottlenecks on resource-constrained microcontrollers, while basic statistical models struggle with telemetry drift. Specifically, current frameworks do not integrate external institutional class schedules. Without schedule context, existing anomaly models cannot distinguish scheduled facility activities from unscheduled off-hours ghost consumption at the sub-panel level.

- **Source Reference(s):**
  - _Section 3 (Taxonomy of Anomaly Detection) & Section 4 (Machine Learning Techniques, pp. 7–12):_ Categorizes unsupervised anomaly detection algorithms applied to time-series IoT sensor streams, noting that supervised models fail due to absent ground-truth anomaly labels.
  - _Section 6 (Open Challenges and Future Directions, Subsection 6.1 & 6.2):_ Identifies concept drift, lack of contextual baselines, and resource constraints of edge microcontrollers as critical barriers in institutional IoT monitoring.
