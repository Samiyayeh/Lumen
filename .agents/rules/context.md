---
trigger: always_on
---

# TARGET PROJECT DATA (CONTEXT CONSTRAINTS)

**AI Directive:** Use this document as the absolute truth for the user's current project[cite: 1]. When sourcing, evaluating, or writing annotations for Related Literature (RRL), Related Studies (RS), or Related Systems (RSS), the AI must ensure the source aligns with the objectives, architecture, and evaluation metrics defined below[cite: 1].

## 1. Project Identity

- **System Title:** Development and Evaluation of an IoT-Driven Sub-Metering and Energy Monitoring Platform for the University of Nueva Caceres: Tracking Off-Hours Usage to Minimize Campus Energy Waste[cite: 1]
- **Proponents:** Rizalina A. Ortega, John Kenneth P. Calubad, Christian Louise O. Asido[cite: 1]
- **Target Organization/Agency:** University of Nueva Caceres (UNC) Facilities Management Department, UNC Administration and Finance Office, and Department Heads[cite: 1]
- **Domain:** Internet of Things (IoT), Institutional Energy Informatics, Smart Sub-Metering, Context-Aware Anomaly Detection[cite: 1]
- **Primary Goal:** Align with UN Sustainable Development Goal 7 (Affordable and Clean Energy) and SDG 13 (Climate Action) by mitigating campus electricity waste and tracking localized off-hours "ghost" consumption[cite: 1].

## 2. Problem Space

The agent should look for literature addressing these specific operational bottlenecks:

- Reliance on macro-utility billing that hides localized, department-level electrical consumption patterns[cite: 1].
- Ineffective manual physical room audits leading to "compliance theater" during scheduled energy inspections[cite: 1].
- Inability to detect off-hours "ghost" energy consumption and idle power draw in empty classrooms, laboratories, and offices[cite: 1].

## 3. Core Functional Requirements

Sources must demonstrate solutions or prototypes related to:

- **IoT Sub-Metering & Telemetry:** Non-invasive current sensor hardware deployed inside sub-panels to track and transmit real-time electrical draw over lightweight IoT protocols[cite: 1].
- **Context-Aware Auditing & Ghost Load Detection:** Machine learning algorithms that cross-reference live power draw against academic/class schedules to identify and flag unscheduled off-hours energy waste[cite: 1].
- **Centralized Facility Dashboard:** Web-based monitoring interface providing facility managers with department-level energy metrics, irregular consumption alerts, and actionable insights[cite: 1].

## 4. Technical Architecture Targets

When evaluating "Related Systems," the agent must prioritize architectures that reflect or inform the 3-tier IoT web ecosystem:

- **IoT Edge / Hardware Layer:** ESP32 microcontrollers paired with non-invasive current transformer (CT) clamp sensors; MQTT ingestion protocols/APIs[cite: 1].
- **Application & Data Tier (Backend):** Lightweight Python backend running anomaly detection logic; PostgreSQL database for time-series energy logs and schedule data[cite: 1].
- **Machine Learning / Anomaly Detection:** Isolation Forest algorithm for context-aware usage auditing and ghost consumption identification[cite: 1].
- **Presentation Tier (Frontend):** Component-based web dashboard built with React and Tailwind CSS[cite: 1].
- **Security & Ethics:** Data encryption, role-based access control (RBAC), and strict adherence to the Data Privacy Act of 2012 (RA 10173) for administrative energy logs[cite: 1].

## 5. Development & Evaluation Standards

When evaluating "Related Studies," the agent must prioritize methodologies using:

- **Lifecycle Model:** Input-Process-Output (IPO) framework combined with the Agile Development Model (iterative sprint cycles)[cite: 1].
- **Theoretical Basis:** Quality Metrics (QUAMET) theoretical foundation[cite: 1].
- **Testing Standards:** Standardized evaluation grounded in the ISO/IEC 25010 Software Quality Standards[cite: 1].
- **Specific Performance Metrics:**
  - _Data Latency:_ Transmission time (in milliseconds/seconds) from ESP32 CT clamps via MQTT to the web dashboard[cite: 1].
  - _Algorithmic Accuracy:_ Confusion Matrix analysis (Precision and Recall) of the Python backend in detecting unscheduled off-hours ghost consumption[cite: 1].
  - _Software Quality:_ Weighted mean calculation using 5-point Likert scale surveys assessing Functional Suitability, Performance Efficiency, Usability, Security, and Reliability among facility personnel[cite: 1].
