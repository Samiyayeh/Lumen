---
description: Step by step Of writing A BiblioGraphy
---

# RSS & RRL Annotated Bibliography Generator (Chapter 2 Taxonomic Architecture)

**Description:** An Antigravity workflow to systematically source real literature, empirical studies, or software systems, and generate an ACM-formatted annotated bibliography entry designed for Chapter 2 Taxonomic / Architectural synthesis.

## Step 1: Request Analysis & Sourcing

- Ask the user for their topic and clarify if they are looking for a "Related Study", a "Related System", or "Related Literature", as well as the target chapter vault (Chapter 1 `00_anotatedbibliography/` or Chapter 2 `01_anotatedbibliography C2/`).
- **Vault Inspection Check:** Before searching for any external sources, inspect the Obsidian vault directories in both `00_anotatedbibliography/` and `01_anotatedbibliography C2/`:
  - `Related-Study international/` (and local)
  - `Related-System international/` (and local)
  - `Related-Literature international/` (and local)
- Do not recommend, select, or generate an entry for any source that already exists within these vault directories to prevent duplicate entries.
- Use search capabilities to find a **real, existing** source that matches the category and is not already in the vault.
- **CRITICAL CONSTRAINT:** Do not hallucinate sources. Verify that the study or system actually exists with a valid DOI, URL, or publication record and is freely accessible in its entirety.
- Only look for sources published between 2021–2026.

## Step 2: ACM Citation Formatting

- Format the retrieved source reference strictly using the Association for Computing Machinery (ACM) reference format in bold: `**[Author(s). Year. Title. Publication Venue. DOI/URL]**`.

## Step 3: Targeted 2-Part Annotation (Taxonomic / Architectural Framework)

Chapter 2 utilizes a **Taxonomic / Architectural Framework** to organize literature and existing systems by structural design, software layers, hardware components, or deployment topologies rather than isolated paper-by-paper summaries. Each annotation provides the raw material for taxonomic grouping, feature comparison matrices, and gap synthesis using strictly two main content sections: **Summary** and **Relevance** (with critique, limitations, and direct architectural relevance unified inside Relevance).

Draft a concise, rigorous 2-part annotation beneath the citation answering these core dimensions:

- **1. Summary (Summary of Scope & Method — 1 Sentence):**
  - **Core Questions Answered:** *What did they do, how did they do it, and what were their core findings?*
  - _For a Study:_ State the research problem addressed, the empirical methodology or algorithmic setup utilized, and the quantitative findings measured.
  - _For a System:_ State the software/hardware architecture developed (microcontroller, sensor type, transport protocol, backend), the operational mechanism, and the primary functional results achieved.
  - _For Literature / Policy:_ State the regulatory or theoretical domain covered, the administrative/survey framework applied, and the core guidelines or taxonomies established.

- **2. Relevance (Direct Relevance to the Proposed System + Critique & Limitation):**
  - **Core Questions Answered:**
    - *Direct Relevance to Your Study:* How does this directly justify the proposed system's research or inform its technical/architectural methodology across system tiers (Sensing & Edge Node, Communication & Transport, Backend & Anomaly Detection, or Presentation & Governance)?
    - *Critique & Limitation:* What are the specific weaknesses, blind spots, architectural boundaries, or technological trade-offs of their approach (e.g., invasive installation, high-latency polling, lack of class schedule context, inability to distinguish ghost consumption from baseline loads, or reliance on periodic manual audits)?
    - *The Bridge:* Conclude by stating precisely how **the proposed system** resolves these weaknesses and overcomes their operational limitations.
  - *Constraint:* Written strictly in the **third person**. Never use "you," "your," "I," or "my." Always refer to the project strictly as **"the proposed system"**.

- **3. Source Reference(s):**
  - Pinpoint exact section names (e.g., "Section 3.2 Methodology"), table numbers, page numbers, or short direct quotes verifying where data was retrieved.

## Step 4: Tone and Style Constraints

You must strictly adhere to the following academic writing rules when drafting the annotation:

1. **Zero-Hallucination Rule:** Do not add external knowledge to the summary. If the source does not mention a specific framework, metric, or finding, do not include it.
2. **Banned AI Vocabulary:** NEVER use overused AI buzzwords (e.g., _delve, testament, paramount, seamless, robust, pivotal, fostering, game-changer, moreover, furthermore, beacon, cornerstone, revolutionizing, state-of-the-art, cutting-edge_).
3. **Ban Manufactured Rhetoric:**
   - Avoid forced rule-of-three rhythm lists (e.g., "improves workflow, enhances accuracy, and optimizes throughput").
   - Avoid X-not-Y parallel constructions (e.g., "the challenge is not X, but Y"). Rewrite as direct statements.
   - Do not use dramatic, melodramatic summaries, or punchlines at paragraph endings.
4. **Academic Hedging:** Use evidence-based qualifiers (_"suggests", "indicates", "demonstrates a reduction of"_) rather than absolute claims (_"completely solves", "guarantees", "eliminates"_).
5. **Direct Transitions:** Use functional research connectors (_"However," "Specifically," "In contrast," "Conversely"_) instead of conversational filler or dramatic transitions.
6. **Technical Grounding over Vague Praise:** Replace abstract descriptive hype with concrete engineering metrics (e.g., transmission latency in milliseconds, RAM/CPU overhead, F1-score/precision/recall, or specific communication topologies).

## Step 5: Single Entry Output & Approval

- Output exactly **one** complete bibliography entry at a time matching the structure:

  # [Paper / System / Literature Full Title]

  **Category:** [[<Category Hub Name>]]

  **[Full ACM Citation with author, year, title, publication venue, and DOI/URL link]**

  - **Summary:** [1-sentence summary of scope & method: what was done, how it was done, and core findings]

  - **Relevance:** [Direct relevance informing/justifying the proposed system's architectural tier, integrated with an explicit critique of specific weaknesses, blind spots, or boundaries of their approach and how the proposed system resolves them]

  - **Source Reference(s):**
    - _[Section / Page 1]:_ [Details or direct quote]
    - _[Section / Page 2]:_ [Details or direct quote]

- Ask the user for approval or feedback on the entry. **Stop execution.** Do not generate the next entry or execute any file transfers until the user explicitly approves the current one.

## Step 6: Obsidian Vault Integration & Routing

- Upon receiving explicit user approval, automatically transfer and save the approved entry as a Markdown (`.md`) file into the local Obsidian vault.
- Determine the target chapter and geographic origin to route the file to the correct directory:
  - **Chapter 2 Vault (`01_anotatedbibliography C2/`):**
    - Study international: `01_anotatedbibliography C2/Related-Study international/` (Category: `[[Related Study international C2]]`)
    - Study local: `01_anotatedbibliography C2/Related-Study local/` (Category: `[[Related Study local C2]]`)
    - System international: `01_anotatedbibliography C2/Related-System international/` (Category: `[[Related System international C2]]`)
    - System local: `01_anotatedbibliography C2/Related-System local/` (Category: `[[Related System local C2]]`)
    - Literature international: `01_anotatedbibliography C2/Related-Literature international/` (Category: `[[Related Literature international C2]]`)
    - Literature local: `01_anotatedbibliography C2/Related-Literature local/` (Category: `[[Related Literature local C2]]`)
  - **Chapter 1 Vault (`00_anotatedbibliography/`):**
    - Routes to corresponding `00_anotatedbibliography/` subdirectories with base hub links (e.g., `[[Related Literature local]]`).
- **Category Hub Linking:** Append the new note's wikilink `[[<Note Name>]]` with a checkbox (`- [ ] [[<Note Name>]]`) to the corresponding category hub note (e.g., `Related Study international C2.md`), which connects to its parent `[[Bibliography C2]]` or `[[Bibliography]]`.
- **Graph Hierarchy Maintained:**
  `[[Bibliography C2]]` ➔ `[[<Category Hub C2>]]` ➔ `[[<Individual Entry>]]`

