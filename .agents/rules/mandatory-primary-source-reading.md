---
trigger: always_on
---

# Mandatory Primary Source Reading Rule

**AI Directive:** When drafting, updating, or rewriting any annotated bibliography entry for Chapter 1 or Chapter 2 (in `00_anotatedbibliography/` or `01_anotatedbibliography C2/`), the AI must **NEVER** merely rehash or summarize existing vault notes or abstracts.

## Mandatory Retrieval & Reading Protocol

Before presenting any draft entry for user review:

1. **Retrieve the Actual Primary Source:**
   - Use `read_url_content`, web search, DOI resolvers, open-access university repositories, or IEEE/ACM/ScienceDirect records to access the actual full text, proceedings, or published paper.
2. **Extract Concrete Technical Details from the Primary Text:**
   - *Hardware & Setup:* Exact microcontrollers used (e.g., ESP32, ESP8266, Arduino), sensor models (e.g., split-core CT clamps, ACS712, PZEM-004T), calibration methods, pin interfaces, and physical testbeds.
   - *Software & Networking:* Protocols (MQTT, HTTP, WebSockets), databases, cloud backend (PostgreSQL, Firebase, ThingSpeak), dashboard UI frameworks (React, MATLAB, Blynk).
   - *Measured Data & Empirical Findings:* Specific numbers, error percentages (e.g., ±1.5%), load measurements (kWh, watts), latency, or survey scores.
   - *Actual Stated Boundaries & Future Work:* Read the paper's actual Discussion, Conclusion, and Limitations sections to pinpoint what the authors explicitly acknowledged their system lacked.
3. **Grounding in 3-Question Framework:**
   - **Summary of Scope & Method:** Exactly what they did, how they built/tested it, and what empirical results they achieved.
   - **Relevance (Tier Justification + Critique & Limitation):** How it directly justifies the proposed system's tier, contrasted against its specific blind spots (lack of schedule context, reliance on manual audits/switching, closed cloud, invasive installation) and how the proposed system resolves them.
   - **Source Reference(s):** Direct section headings, table numbers, or page numbers from the primary publication.
