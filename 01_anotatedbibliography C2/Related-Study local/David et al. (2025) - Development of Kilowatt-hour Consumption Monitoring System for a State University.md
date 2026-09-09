# Development of Kilowatt-hour Consumption Monitoring System for a State University: Real-time Tracking with Sub-meter

**Category:** [[Related Study local C2]]

**J. D. David, A. T. Aga, J. C. Basa, T. M. Cailing Jr., A. E. Rimando VII, C. M. D. Canonero, and A. M. Viscayno. 2025. Development of Kilowatt-hour Consumption Monitoring System for a State University: Real-time Tracking with Sub-meter. *Asian Journal of Applied Science and Technology* 9, 3 (2025), 54–60. DOI:https://doi.org/10.38177/ajast.2025.9306**

- **Summary:** David et al. evaluated departmental electrical demand at Don Honorio Ventura State University by installing a wireless smart sub-meter on a 3rd-floor distribution panel board connected to a cross-platform mobile dashboard, measuring departmental loads across engineering faculties (10.61–38.96 kWh/day) and proving that sub-metering uncovers localized consumption peaks that single campus utility meters conceal.

- **Relevance:** This study directly justifies the Sensing and Presentation Tiers of the proposed system by demonstrating in a Philippine state university that panel-level sub-metering isolates departmental inefficiencies and validates daily load profiles. However, the architectural boundary of their system is restricted to passive telemetry display with manual graph interpretation, lacking offline edge memory buffers, automated anomaly detection, and academic schedule awareness. The proposed system directly overcomes these blind spots by integrating edge-buffered ESP32 telemetry with backend Isolation Forest anomaly detection and automated class schedule cross-referencing, autonomously detecting and alerting administrators to unscheduled off-hours ghost consumption.

- **Source Reference(s):**
  - _Section 2.2 & 2.3 (System Flow & Architecture, pp. 55–56):_ Deployment of a wireless smart sub-meter on the 3rd-floor panel board and pre-deployment calibration testing against a residential utility meter yielding deviations between -0.03 kWh and -0.09 kWh.
  - _Section 3.1 & 3.2 (Results and Discussion, p. 57):_ Empirical tracking of departmental loads (Table 1) where Architecture consumed 38.96 kWh and EE consumed 10.61 kWh, alongside actual 4-day consumption logs ranging between 50.54 kWh and 71.98 kWh (Table 2).
  - _Section 4 & 5 (Conclusion & Future Suggestions, p. 58):_ Explicit acknowledgment that the platform relies on manual observation, lacks machine learning analytics, and requires offline memory storage to prevent data loss.
