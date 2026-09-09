# Research Context

This document is the authoritative context file for the `overall-helper` skill. It contains the current state of the research draft (Chapter 1 and Chapter 2) and a complete index of all annotated bibliography entries available in the vault.

---

## Current Chapter 1 Draft

### Title

**Development and Evaluation of an IoT-Driven Sub-Metering and Energy Monitoring Platform for the University of Nueva Caceres: Tracking Off-Hours Usage to Minimize Campus Energy Waste**

A Capstone Project Study
Presented to the Faculty of the School of Computer and Information Sciences
University of Nueva Caceres

In Partial Fulfillment of the Requirements for the Degree of
BACHELOR OF SCIENCE IN INFORMATION TECHNOLOGY

**By:**
Asido, Christian Louise O.
Calubad, John Kenneth P.
Ortega, Rizalina A.

**AUGUST 2026**

---

### Background of the Study

Managing energy consumption in educational institutions requires tracking to eliminate wasted electricity and meet the sustainable development goals. Integrating IoT sensor nodes with the energy monitoring dashboards will provide the real-time tracking of energy consumption (Polin et al., 2023). Large institutional buildings lack automation in detecting real time energy consumption, relying on manual audits that failed to minimize energy usage.

The educational facilities in the Philippines are supervised by Administrative Order No. 15 adopting the automated energy audits and real-time consumption monitoring that will reduce monthly electricity usage (Office of the President of the Philippines, 2024). Complying with this mandate, the University of Nueva Caceres established an institutional goal to minimize campus energy consumption and promote sustainability. However, the university cannot monitor the real-time energy consumption of each office and department of the campus. The University of Nueva Caceres facilities management department receives only one electronic bill for everything, making it difficult to track unmonitored off-hours consumption across campus facilities.

The main bottleneck of this workflow is leaving office equipment and cooling units running continuously through lunch breaks and off-hours, the technical limitation is caused by the institution's reliance on manual room checks and physical audit procedures. When the rooms are left powered on outside scheduled hours the detection relies on manual discovery rather than automated tracking, leaving the facilities wasting energy while doing nothing. Right now, there is no software that connects with the campus electrical setup that will monitor the running time of metrics in real-time. Therefore the technical gaps in this study is the absence of the real-time power monitoring mechanism that is capable of capturing energy metrics and preventing unmonitored energy consumption during vacant hours.

To address these operational and technical gaps, this study proposes the Development and Evaluation of an IoT-Driven Sub-Metering and Energy Monitoring Platform for the University of Nueva Caceres: Tracking Off-Hours Usage to Minimize Campus Energy Waste. This system involves installing the non-invasive ESP32 microcontrollers to track the real-time electricity usage of the specific campus areas. To handle the data, we will integrate the Isolation Forest algorithm to cross-check the power consumption and detect the off-hours ghost consumption. To validate the data, the accuracy of the ESP32 sub-metering nodes will be evaluated against the standard commercial clamp meters, while the overall operational quality and usability will be evaluated by the UNC facilities personnel using the systems and software quality requirements and evaluation.

---

### Objectives of the Study

The objective of this study is to design, develop and evaluate an IoT-Driven Sub-Metering and Energy Monitoring Platform for the University of Nueva Caceres: Tracking Off-Hours Usage to Minimize Campus Energy Waste using the Software Quality Standard.

To achieve this objective, the study will follow this:

1. Develop non-invasive ESP32 CT clamp hardware inside sub-panels to track real-time power consumption to a specific campus zones
2. Create a lightweight Python backend running an Isolation Forest algorithm to cross-check power usage against class schedules and detect off-hours ghost consumption.
3. Deploy a centralized web dashboard to provide facility administrators with actionable, department-level energy insights.
4. Evaluate the proposed platform based on the Software Quality Standards in terms of:
   - Performance efficiency
   - Usability

---

### Scope and Delimitation

The study will focus on the development and evaluation of an IoT sub-metering and energy monitoring platform for the University of Nueva Caceres. This study covers the real-time tracking of electricity usage and detecting off-hours ghost consumption by cross-checking energy usage against actual class schedule.

With the deployment of this, the installation of the hardware is restricted within the JH Building (such as a computer laboratory, lecture classroom and faculty office) using the non-invasive ESP32 microcontrollers and CT clamp sensors. The project will exclude any feature that automatically shuts off the power or trips the breakers when an empty room is detected, in order to comply with the campus safety regulation. Additionally, it does not include financial billing computation, as the system is designed for tracking energy consumption and sending operational alerts.

---

### Definition of Terms

For the purpose of clarity, the following key terms used throughout the study are defined within the context of this research:

1. **Centralized Web Dashboard** — A web-based graphical user interface developed with React and Tailwind CSS that aggregates sub-panel telemetry and presents real-time energy consumption metrics and off-hours alert notifications to University of Nueva Caceres facilities managers.

2. **Current Transformer (CT) Clamp Sensor** — A non-invasive electrical sensor placed around electrical cables inside the JH Building distribution sub-panels to measure live current draw without cutting or interrupting existing campus electrical lines.

3. **ESP32 Microcontroller** — A low-power hardware computing node deployed within the campus sub-panels that reads analog signals from CT clamp sensors, calculates electrical draw metrics, and transmits real-time telemetry to the system backend.

4. **Ghost Consumption** — Electrical energy consumed by lighting, desktop computers, and air conditioning units during unscheduled periods, vacant classroom hours, lunch breaks, or overnight in unoccupied campus rooms.

5. **Internet of Things (IoT)** — The networked system architecture comprising edge ESP32 microcontroller nodes, non-invasive current sensors, and a backend server that continuously collect and transmit electrical metrics over the campus network.

6. **Isolation Forest Algorithm** — An unsupervised machine learning algorithm that detects anomalies by isolating rare data points through randomized decision tree partitions, where outliers require fewer splits to separate than normal data. In this study, it runs within the Python backend to evaluate live power draw against academic class schedules, automatically isolating and flagging unscheduled electrical usage as off-hours ghost consumption.

7. **Off-Hours Usage** — Electrical consumption that occurs outside authorized operating hours or designated class and laboratory schedules within the JH Building.

8. **Performance Efficiency** — An evaluation metric based on ISO/IEC 25010 that assesses the response time, data transmission latency, and processing speed of the ESP32 hardware and web dashboard during live operation.

9. **Schedule Cross-Referencing** — The backend process of comparing live electrical load in a specific campus zone against the official University of Nueva Caceres class schedule to differentiate between legitimate classroom use and unmonitored energy waste.

10. **Software Quality Standards (ISO/IEC 25010)** — The international software evaluation framework utilized to assess the operational quality of the proposed platform, specifically measuring Performance Efficiency and Usability through structured evaluations by UNC facilities personnel.

11. **Sub-Metering** — The deployment of dedicated edge sensors downstream from the main university electric meter to monitor localized, room- and circuit-level power draw within the JH Building.

12. **Usability** — An evaluation metric based on ISO/IEC 25010 that measures how easily UNC facilities administrators can navigate the dashboard, interpret energy graphs, and respond to off-hours ghost consumption alerts.

---

## Vault Source Index

All annotated bibliography entries currently available in the Obsidian vault. The skill must only cite sources from this list and must never hallucinate or invent sources.

### Related Literature — International

| File | Citation Key |
|---|---|
| Al-Obaidi et al. (2022) - A Review of Using IoT for Energy Efficient Buildings and Cities A Built Environment Perspective.md | Al-Obaidi et al., 2022 |
| Chatterjee and Ahmed (2022) - IoT Anomaly Detection Methods and Applications A Survey.md | Chatterjee & Ahmed, 2022 |
| El Husseini et al. (2025) - Machine Learning in Smart Buildings A Review of Methods Challenges and Future Trends.md | El Husseini et al., 2025 |
| Goudarzi et al. (2022) - A Survey on IoT-Enabled Smart Grids.md | Goudarzi et al., 2022 |
| Liang et al. (2024) - A Review of Edge Computing Technology and Its Applications in Power Systems.md | Liang et al., 2024 |
| Lopez-Goyez et al. (2026) - Smart Campus in Higher Education A Systematic Review.md | Lopez-Goyez et al., 2026 |
| Mari et al. (2022) - A Review of Non-Intrusive Load Monitoring Applications in Industrial and Residential Contexts.md | Mari et al., 2022 |
| Oliveira and Proenca (2025) - Sustainable Campus Operations in Higher Education Institutions A Systematic Literature Review.md | Oliveira & Proenca, 2025 |
| Polin et al. (2023) - The Making of Smart Campus A Review and Conceptual Framework.md | Polin et al., 2023 |
| Poyyamozhi et al. (2024) - IoT A Promising Solution to Energy Management in Smart Buildings.md | Poyyamozhi et al., 2024 |
| Raza et al. (2023) - Smart Meters for Smart Energy A Review of Business Intelligence Applications.md | Raza et al., 2023 |
| Rojas et al. (2025) - Mapping the Evolution and Future Directions of ISO-IEC 25010 A Bibliometric and Thematic Analysis.md | Rojas et al., 2025 |
| Shahid et al. (2025) - Advances in Building Energy Management A Comprehensive Review.md | Shahid et al., 2025 |
| Tian et al. (2026) - A Systematic Review of Building Energy Management and Optimization Using the Artificial Intelligence of Things.md | Tian et al., 2026 |

### Related Literature — Local

| File | Citation Key |
|---|---|
| Office of the President (2024) - Administrative Order No. 15 Government Energy Management Program.md | Office of the President, 2024 |

### Related Study — International

| File | Citation Key |
|---|---|
| Adriansyah et al. (2026) - Performance Analysis of MQTT and HTTP Protocols on Low-Power ESP32 Devices.md | Adriansyah et al., 2026 |
| Himeur et al. (2022) - Detection of Appliance-Level Abnormal Energy Consumption in Buildings.md | Himeur et al., 2022 |
| Kee et al. (2025) - Development of a Data-driven Energy Monitoring System.md | Kee et al., 2025 |
| Park and Kim (2025) - A Low-Carbon Smart Campus Created by the Strategic Usage of Space.md | Park & Kim, 2025 |
| Sousa et al. (2026) - Smart Energy Monitoring for Sustainable Campuses.md | Sousa et al., 2026 |
| Tambun et al. (2025) - Anomaly Detection of Non-Technical Losses in Smart Meter Data.md | Tambun et al., 2025 |
| Wang et al. (2022) - Toward Delicate Anomaly Detection of Energy Consumption for Buildings.md | Wang et al., 2022 |
| Wu et al. (2023) - Integrated Energy System Based on Isolation Forest and Dynamic Orbit Multivariate Load Forecasting.md | Wu et al., 2023 |

### Related Study — Local

| File | Citation Key |
|---|---|
| Cubacub et al. (2025) - B30 Blynk-interfaced Three-Phase Smart Energy Monitoring System.md | Cubacub et al., 2025 |
| David et al. (2025) - Development of Kilowatt-hour Consumption Monitoring System for a State University.md | David et al., 2025 |
| Mababa (2023) - Development of a Real-Time Electricity Meter Monitoring with Theft Detection Alert System.md | Mababa, 2023 |
| Mendoza et al. (2024) - IoT-Based Energy Monitoring System for Optimizing Power Consumption in University Facilities.md | Mendoza et al., 2024 |
| Merencilla et al. (2023) - IoT-Based Energy Management and Power Outage Detection System for Commercial Buildings.md | Merencilla et al., 2023 |
| Pagaduan et al. (2023) - The Development of Real-Time Energy Consumption Monitoring using IoT.md | Pagaduan et al., 2023 |
| Sanglay et al. (2025) - Illuminating Sustainability.md | Sanglay et al., 2025 |

### Related System — International

| File | Citation Key |
|---|---|
| Ahmed et al. (2022) - Toward an Intelligent Campus.md | Ahmed et al., 2022 |
| Joha et al. (2024) - A Secure IIoT Environment That Integrates AI-Driven Real-Time Short-Term Active and Reactive Load Forecasting with Anomaly Detection.md | Joha et al., 2024 |
| Khan et al. (2024) - A Low-Cost Energy Monitoring System with Universal Compatibility.md | Khan et al., 2024 |
| Mallala et al. (2025) - IoT enabled smart power quality analysis in three phase electrical systems.md | Mallala et al., 2025 |
| Munoz et al. (2022) - Design and Development of an IoT Smart Meter with Load Control for Home Energy Management Systems.md | Munoz et al., 2022 |
| Ramachandra and Natarajan (2024) - IoT-Based Home Energy Management System.md | Ramachandra & Natarajan, 2024 |
| Sousa E. et al. (2023) - Development a Low-Cost Wireless Smart Meter with Power Quality Measurement.md | Sousa et al., 2023 |
| Supriyono et al. (2025) - Electrical power submeter for quality and energy monitoring.md | Supriyono et al., 2025 |
| Veloso et al. (2026) - A Microservices-Based Solution with Hybrid Communication for Energy Management in Smart Grid Environments.md | Veloso et al., 2026 |
| Wang et al. (2025) - Research on the Development of a Building Model Management System Integrating MQTT Sensing.md | Wang et al., 2025 |

### Related System — Local

| File | Citation Key |
|---|---|
| Adana et al. (2026) - Electricity Misuse With Pzem Anomaly Detection and Notification.md | Adana et al., 2026 |
| Cabe et al. (2026) - WattWise Mobile-Based Energy Monitoring and Forecasting System for Home Appliances.md | Cabe et al., 2026 |
| Lorenzo and Recto (2024) - Transforming Energy Management with Advanced Web-Driven Community Dashboards.md | Lorenzo & Recto, 2024 |
| Magnaye et al. (2025) - eVolta A Cloud-Based and Real-Time Electricity Usage Monitoring System.md | Magnaye et al., 2025 |
| Monteagudo et al. (2025) - Design and Development of a Smart Motion Detection System Geared Towards Energy Conservation.md | Monteagudo et al., 2025 |

---

## Chapter 1 Sections Status

| Section | Status |
|---|---|
| Background of the Study | Draft exists — needs citation enrichment and polish |
| Objectives of the Study | Draft exists — needs review |
| Scope and Delimitation | Partial draft exists (Kenneth's section) — needs completion |
| Significance of the Study | Not yet written |
| Definition of Terms | Drafted (12 terms, single operational format) |
