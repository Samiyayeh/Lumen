# Toward an Intelligent Campus: IoT Platform for Remote Monitoring and Control of Smart Buildings

**Category:** [[Related System international]]

**Mohamed A. Ahmed, Sebastian A. Chavez, Ali M. Eltamaly, Hugo O. Garces, Alejandro J. Rojas, and Young-Chon Kim. 2022. Toward an Intelligent Campus: IoT Platform for Remote Monitoring and Control of Smart Buildings. *Sensors* 22, 23 (2022), 9045. DOI:https://doi.org/10.3390/s22239045**

- **Summary:** Ahmed et al. present a multi-tier IoT campus energy management platform that combines electrical panel sub-metering via ESP32 microcontrollers and current transformer sensors, MQTT telemetry ingestion to a Mosquitto broker, MySQL time-series storage, and a responsive Node-RED dashboard for real-time electrical monitoring and appliance control across university spaces.

- **Gap:** Although deployed across campus spaces, the platform depends on manual supervisory dashboard intervention and static threshold rules, lacking automated machine learning algorithms (such as Isolation Forest) to autonomously cross-reference live electrical draw against dynamic class schedules for ghost load detection.

- **Relevance:** The architectural design demonstrates that coupling ESP32 microcontrollers with current transformer sensors at electrical panels enables lightweight telemetry transmission via MQTT to a centralized web dashboard, validating the multi-tier IoT hardware and communication topology required by the proposed system to isolate building-level electrical loads in educational facilities.

- **Source Reference(s):**
  - *Section 3.1 & Section 3.2 (IoT-Based Architecture for Smart Buildings):* Specification of the four-tier architectural hierarchy spanning the power layer, data acquisition layer, network layer, and application layer across campus facilities.
  - *Section 4.2.2 & Section 4.4.1 (Power Layer and Network Layer):* Integration of PZEM-004T modules and current transformer sensors with ESP32 microcontrollers transmitting telemetry via MQTT to a cloud-hosted Mosquitto broker.
  - *Section 4.5 (Application Layer):* Deployment of a virtual server hosting MySQL database storage and a responsive Node-RED dashboard interface for real-time electrical telemetry visualization across university offices, classrooms, and laboratories.
