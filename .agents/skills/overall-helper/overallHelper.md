---
name: overall-helper
description: >-
  Assists in writing, revising, and enriching Chapter 1 and Chapter 2 of the
  capstone research "Development and Evaluation of an IoT-Driven Sub-Metering
  and Energy Monitoring Platform for the University of Nueva Caceres."
  Chapter 1 coverage: Background of the Study, Objectives, Scope and
  Delimitation, Significance of the Study, Definition of Terms, and Conceptual
  Framework. Chapter 2 coverage: Review of Related Literature, Review of
  Related Studies, and Review of Related Systems — using only verified vault
  sources.
---

# Capstone Research Writing Skill — Overall Helper

## Purpose

This skill guides the agent in assisting the researchers in writing, completing, or improving any section of **Chapter 1** or **Chapter 2** of their capstone research paper. All work must be grounded in the project context, use only vault-indexed sources, and follow strict academic writing rules.

---

## Step 0: Load Context First

Before doing any writing, **always read the context file** at:
- `skills/overall-helper/research context.md`

This file contains:
- The authoritative Research Context (Chapter 1 & Chapter 2 draft context, conceptual framework, definition of terms)
- The complete Vault Source Index (all available citations across 6 categories)
- The status of each section

Do NOT proceed with writing until you have read and internalized the context file.

---

## Step 1: Identify What the User Needs

Ask the user (or infer from their request) which chapter and section they need help with.

### Chapter 1 Sections
1. **Background of the Study** — Narrative establishing the problem context, the gap, and the proposed system.
2. **Objectives of the Study** — Enumerated goals aligned to the system's functional and evaluation targets.
3. **Scope and Delimitation** — What the study covers and what it explicitly excludes.
4. **Significance of the Study** — Who benefits and how; written for institutional, academic, and societal stakeholders.
5. **Definition of Terms** — Single-format operational definitions of technical terms used in the study.
6. **Conceptual Framework** — IPO model narrative and visual description.

### Chapter 2 Sections
1. **Review of Related Literature (RRL)** — Synthesis of theoretical literature from the vault that contextualizes the study's domain.
2. **Review of Related Studies (RSS)** — Synthesis of empirical studies from the vault that inform the methodology and approach.
3. **Review of Related Systems (RSS)** — Synthesis of existing systems from the vault whose architectures inform or contrast with the proposed system.
4. **Synthesis** — A closing Chapter 2 section that draws connections between all reviewed works and identifies the gap the proposed system fills.

If the user asks for something specific (e.g., "write the RRL for IoT," "expand paragraph 2 of the background," "add citations to the scope"), focus only on that.

---

## Step 2: Citation Discipline

**Before inserting any citation**, check the Vault Source Index in `chapter 1 Context.md`.

- **ONLY use sources listed in the Vault Source Index.** Do not hallucinate, invent, or suggest sources not in the vault.
- Read the actual `.md` file of any vault entry before citing it to verify the Summary and Relevance align with the claim being made.
- Vault entries are stored in:
  - `00_anotatedbibliography/Related-Literature international/`
  - `00_anotatedbibliography/Related-Literature local/`
  - `00_anotatedbibliography/Related-Study international/`
  - `00_anotatedbibliography/Related-Study local/`
  - `00_anotatedbibliography/Related-System international/`
  - `00_anotatedbibliography/Related-System local/`
- In-text citations must follow APA format: `(Author et al., Year)`.

---

## Step 3: Writing Standards

Apply these rules to every sentence produced:

### Academic Tone
- Write in third person. Never use "we," "our," "I," or "you."
- Acceptable: "the proposed system," "the researchers," "the study," "this platform."
- Avoid first-person framing entirely.

### Banned AI Vocabulary
Never use these words or phrases:
- _delve, testament, paramount, seamless, robust, pivotal, fostering, game-changer, moreover, furthermore, beacon, cornerstone, revolutionizing, state-of-the-art, cutting-edge_

### Banned Rhetorical Patterns
- No rule-of-three rhythm lists (e.g., "improves workflow, enhances accuracy, and optimizes throughput").
- No X-not-Y parallel constructions. Rewrite as direct statements.
- No dramatic or melodramatic punchlines at paragraph endings.

### Evidence-Based Qualifiers
Use hedged academic language:
- GOOD: "suggests," "indicates," "demonstrates a reduction of," "has been shown to"
- BAD: "completely solves," "guarantees," "eliminates," "proves"

### Direct Transitions
Use functional academic connectors:
- GOOD: "However," "Specifically," "In contrast," "Conversely," "Building on this,"
- BAD: "In today's world," "In the modern era," "It is undeniable that"

### Technical Specificity
Replace vague descriptors with concrete technical references:
- BAD: "a modern platform"
- GOOD: "an ESP32-based CT clamp metering node transmitting data over MQTT"

---

## Step 4: Chapter 1 — Section-Specific Instructions

### Background of the Study

Structure the background in three logical movements:

1. **Macro Context** — Global/national context of energy waste in educational institutions. Cite literature reviews and legal frameworks (e.g., AO No. 15, SDG 7/13).
2. **Institutional Problem** — UNC-specific gap: single-bill utility structure, no department-level visibility, off-hours ghost consumption.
3. **Technical Gap & Proposed Solution** — Absence of real-time automated monitoring; introduce the proposed system (ESP32 + Isolation Forest + web dashboard).

Each paragraph must contain at least one vault citation. Do not make unsupported claims.

### Objectives of the Study

- Must follow the four numbered objectives already established in the draft.
- Objectives must be action-verb driven (Develop, Create, Deploy, Evaluate).
- The evaluation objective must name the ISO/IEC 25010 quality dimensions being tested: **Performance Efficiency** and **Usability**.
- Do not add objectives not grounded in the system's actual scope.

### Scope and Delimitation

Structure in two parts:
1. **Scope** — What the system does, where it is deployed (JH Building), what it measures (real-time electrical draw cross-checked against class schedules).
2. **Delimitations** — What is explicitly excluded and why:
   - No automatic power shutoff / breaker tripping (campus safety regulation).
   - No billing computation (system is for monitoring and alerting only).
   - Hardware restricted to JH Building only.

### Significance of the Study

Identify and write benefit statements for each of these stakeholders. Each stakeholder gets one concise paragraph:

1. **University of Nueva Caceres Administration** — Decision-making via department-level energy data.
2. **UNC Facilities Management Department** — Automated ghost consumption alerts replacing manual audits.
3. **Department Heads / Faculty** — Visibility into usage patterns within their areas.
4. **Future Researchers** — Replicable IoT + ML anomaly detection framework for campus energy auditing.
5. **Philippine Government / Policy** — Demonstrates institutional compliance with AO No. 15 and SDG 7/13.

### Definition of Terms

- Use a **single-definition format** (not split into conceptual and operational sub-bullets).
- Each definition must state what the term means AND how it applies specifically to this study.
- Only define terms that appear in the Chapter 1 draft. Do not add terms from outside the chapter.
- Currently drafted terms (12): Centralized Web Dashboard, CT Clamp Sensor, ESP32 Microcontroller, Ghost Consumption, IoT, Isolation Forest Algorithm, Off-Hours Usage, Performance Efficiency, Schedule Cross-Referencing, Software Quality Standards (ISO/IEC 25010), Sub-Metering, Usability.

### Conceptual Framework

- Frame using the Input-Process-Output (IPO) model.
- **Input:** ESP32 + CT clamps, class schedules, 24/7 authorized baselines (server rooms, IT infrastructure), MQTT, ISO/IEC 25010, AO No. 15.
- **Process:** Edge telemetry ingestion, PostgreSQL time-series logging, Isolation Forest anomaly detection (distinguishing ghost loads from authorized 24/7 critical loads), React & Tailwind dashboard engineering, and software quality evaluation.
- **Output:** Operational IoT sub-metering platform, real-time ghost consumption alerts, UNC facilities dashboard, ISO/IEC 25010 evaluation report.
- **Feedback Loop:** Telemetry calibration and 24/7 baseline model tuning.

---

## Step 5: Chapter 2 — Section-Specific Instructions

### General Chapter 2 Rules

- Chapter 2 draws **exclusively** from the vault source index. Do not cite external sources not in the vault.
- Each reviewed work must have a paragraph of its own that includes: what the source did, how it was done, and what its gap or limitation was relative to the proposed system.
- The final sentence of each paragraph must connect the reviewed work's findings or limitations to the proposed system's contribution.
- Do not summarize the abstract. Extract specific methodological or technical details from the vault entry's **Summary**, **Relevance**, and **Source Reference(s)** fields.

### Review of Related Literature (RRL)

- Draw only from `Related-Literature international/` and `Related-Literature local/` vault entries.
- Organize RRL thematically, not entry by entry. Suggested thematic clusters:
  1. **IoT in Energy Management and Smart Buildings** — (e.g., Al-Obaidi et al., 2022; Goudarzi et al., 2022; Poyyamozhi et al., 2024; Shahid et al., 2025)
  2. **Smart Campus Frameworks** — (e.g., Polin et al., 2023; López-Goyez et al., 2026; Oliveira & Proença, 2025)
  3. **Anomaly Detection & Machine Learning in Buildings** — (e.g., Chatterjee & Ahmed, 2022; El Husseini et al., 2025; Tian et al., 2026)
  4. **Non-Intrusive Load Monitoring** — (e.g., Mari et al., 2022; Raza et al., 2023; Liang et al., 2024)
  5. **Policy & Quality Standards** — (e.g., Office of the President, 2024; Rojas et al., 2025)

### Review of Related Studies (RSS)

- Draw only from `Related-Study international/` and `Related-Study local/` vault entries.
- Organize by thematic relevance to the proposed system:
  1. **IoT Energy Monitoring in University/Campus Settings** — (e.g., Mendoza et al., 2024; Park & Kim, 2025; Sousa et al., 2026; Kee et al., 2025)
  2. **Anomaly Detection Studies** — (e.g., Himeur et al., 2022; Wang et al., 2022; Tambun et al., 2025; Wu et al., 2023)
  3. **ESP32 & Protocol Studies** — (e.g., Adriansyah et al., 2026)
  4. **Local Philippine Studies** — (e.g., David et al., 2025; Pagaduan et al., 2023; Merencilla et al., 2023; Cubacub et al., 2025; Sanglay et al., 2025; Mababa, 2023)

### Review of Related Systems (RSS)

- Draw only from `Related-System international/` and `Related-System local/` vault entries.
- For each system, describe: hardware used, key features, functional scope, and how it differs from or informs the proposed system.
- Organize by architectural similarity:
  1. **International Systems** — (e.g., Ahmed et al., 2022; Khan et al., 2024; Munoz et al., 2022; Mallala et al., 2025; Supriyono et al., 2025; Joha et al., 2024; Ramachandra & Natarajan, 2024; Sousa et al., 2023; Veloso et al., 2026; Wang et al., 2025)
  2. **Local Systems** — (e.g., Adana et al., 2026; Cabe et al., 2026; Lorenzo & Recto, 2024; Magnaye et al., 2025; Monteagudo et al., 2025)

### Synthesis

- Write as a single closing section for Chapter 2.
- Identify the common themes across all reviewed literature, studies, and systems.
- Explicitly name the gap that all reviewed works share that the proposed system addresses (e.g., lack of schedule-aware IoT anomaly detection with a centralized institutional dashboard).
- Do not introduce new citations in the synthesis; only reference sources already discussed in Chapter 2.

---

## Step 6: Output and Approval Workflow

1. Output only the requested section or paragraph at a time.
2. After outputting, briefly note which vault sources were cited and why.
3. Ask the user for approval or if they want any revision before proceeding to the next section.
4. **Do not save or write to any file unless the user explicitly approves the output.**

---

## Step 7: File Saving (Upon Approval)

If the user approves a section and asks to save it:
- Save the content to a Markdown file in the workspace.
- Suggested paths:
  - Chapter 1: `Chapter 1 Draft/[Section Name].md`
  - Chapter 2: `Chapter 2 Draft/[Section Name].md`
- Do not overwrite existing draft content without confirmation.
