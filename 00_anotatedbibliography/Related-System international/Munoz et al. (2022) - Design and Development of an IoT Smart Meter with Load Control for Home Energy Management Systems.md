# Design and Development of an IoT Smart Meter with Load Control for Home Energy Management Systems

**Category:** [[Related System international]]

**Oscar Munoz, Arturo Ruelas, Paul Rosales, Alejandro Acuña, Abraham Suastegui, and Francisco Lara. 2022. Design and Development of an IoT Smart Meter with Load Control for Home Energy Management Systems. *Sensors* 22, 19 (2022), 7536. DOI:https://doi.org/10.3390/s22197536**

- **Summary:** Munoz et al. develop an IoT smart sub-meter that integrates an ADE7758 polyphase energy metering IC with an ESP32 microcontroller, differential current sensing, and integrated relays to log electrical telemetry over Wi-Fi and provide real-time consumption monitoring and load switching through a web-deployed dashboard.

- **Relevance:** The embedded architecture demonstrates that interfacing dedicated energy metering ICs with ESP32 microcontrollers achieves sub-one percent measurement error in real-time telemetry acquisition, providing technical validation for deploying ESP32-driven edge sub-metering hardware within the proposed system to capture precise electrical draw across localized facilities.

- **Source Reference(s):**
  - *Section 3.1 & Section 3.2 (Architecture, Description and Development):* Implementation of a device-level smart meter combining the ADE7758 energy measurement IC, ESP32 microcontroller with Wi-Fi, and dual electromechanical relays.
  - *Section 4 & Section 5 (Testing and Results):* Empirical laboratory validation showing an absolute percentage measurement error below 1% alongside real-time monitoring through a web-deployed application.
