# A Review of Non-Intrusive Load Monitoring Applications in Industrial and Residential Contexts

**Category:** [[Related Literature international]]

**Simone Mari, Giovanni Bucci, Fabrizio Ciancetta, Edoardo Fiorucci, and Andrea Fioravanti. 2022. A Review of Non-Intrusive Load Monitoring Applications in Industrial and Residential Contexts. *Energies* 15, 23 (2022), 9011. https://doi.org/10.3390/en15239011**

- **Summary:** Mari et al. review non-intrusive load monitoring techniques and sub-metering methodologies across residential and industrial environments, categorizing current sensor disaggregation algorithms, telemetry architectures, and load profile extraction for energy management systems.

- **Relevance:** The literature demonstrates that non-invasive current measurement at aggregate electrical distribution panels provides sufficient resolution to detect operational load variations without installing individual socket meters, establishing foundational technical justification for the clamp-based sub-metering topology implemented in the proposed system.

- **Gap:** Although the review confirms that non-intrusive current sensing at aggregate electrical panels can capture operational load profiles without per-socket metering, it demonstrates that conventional NILM algorithms suffer from high algorithmic complexity, susceptibility to electrical noise, and poor disaggregation accuracy when distinguishing multiple concurrent or identical loads. Crucially, existing NILM research focuses predominantly on residential appliances or heavy industrial machinery, lacking practical, lightweight sub-panel architectures that combine non-invasive split-core CT telemetry with external schedule awareness to audit multi-room institutional facilities.

- **Source Reference(s):**
  - _Section 2 (NILM Systems Architecture and Measurement Techniques):_ Analyzes current and voltage sensing topologies deployed at localized electrical sub-panels to capture real-time power draw metrics.
  - _Section 4 (Applications in Energy Management and Audit):_ Reviews load profile disaggregation for identifying operational anomalies, equipment idle states, and unneeded power consumption.
