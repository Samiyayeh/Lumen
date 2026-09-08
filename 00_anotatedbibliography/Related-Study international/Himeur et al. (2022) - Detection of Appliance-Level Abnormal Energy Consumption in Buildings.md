# Detection of Appliance-Level Abnormal Energy Consumption in Buildings Using Autoencoders and Micro-moments

**Category:** [[Related Study international]]

**Yassine Himeur, Abdullah Alsalemi, Faycal Bensaali, and Abbes Amira. 2022. Detection of Appliance-Level Abnormal Energy Consumption in Buildings Using Autoencoders and Micro-moments. In *Proceedings of the 5th International Conference on Big Data and Internet of Things (BDIoT 2021)* (Lecture Notes in Networks and Systems, Vol. 488). Springer, 185–197. DOI:https://doi.org/10.1007/978-3-031-07969-6_14**

- **Summary:** Himeur et al. address the challenge of identifying unmonitored idle power and equipment misuse in buildings by developing an unsupervised anomaly detection framework that extracts micro-moment consumption features, including standby power and operating durations, using autoencoder neural networks.

- **Relevance:** The study confirms that evaluating device standby power consumption (DSPC) and inactive duration metrics enables precise identification of idle energy waste, providing theoretical and methodological justification for the anomaly detection logic employed in the proposed system to isolate off-hours ghost consumption across campus sub-circuits.

- **Gap:** Although the study proves that autoencoders and micro-moment metrics effectively detect appliance-level idle power and equipment faults, it relies on granular plug-level monitoring and computationally intensive neural network architectures. It lacks branch-circuit sub-panel metering using non-invasive CT sensors, lightweight unsupervised algorithms (such as Isolation Forest), and integration with institutional classroom timetables. Consequently, the approach is cost-prohibitive for campus-wide scaling and cannot cross-reference aggregated room-level electrical draw against academic schedules to detect unauthorized off-hours ghost consumption.

- **Source Reference(s):**
  - *Section 1 (Introduction) & Section 2 (Micro-moment Extraction Framework, pp. 185–190):* Mathematical extraction of Device Standby Power Consumption (DSPC) and operational duration metrics to characterize idle versus active load states.
  - *Section 3 (Evaluation and Discussion, pp. 191–196):* Experimental testing of unsupervised reconstruction models on real-world building energy data, demonstrating high anomaly detection sensitivity on idle and abnormal equipment draws.
  - *Section 4 (Conclusion, pp. 196–197):* Summary of autoencoder anomaly detection performance on appliance-level loads and discussion of computational constraints when scaling micro-moment frameworks across broader facility infrastructures.
