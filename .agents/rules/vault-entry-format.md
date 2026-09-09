---
trigger: always_on
---

# Vault Entry Formatting Rule

**AI Directive:** Every time an annotated bibliography entry is saved or updated in the Obsidian vault (under `00_anotatedbibliography/` or `01_anotatedbibliography C2/`), it MUST strictly adhere to the following Markdown format with exact spacing and structure:

## Required Entry Template

```markdown
# [Paper / System / Literature Full Title]

**Category:** [[<Category Hub Name>]]

**[Full ACM Citation with author, year, title, publication venue, and DOI/URL link]**

- **Summary:** [1-sentence summary of scope & method: what they did, how they did it, and core findings]

- **Relevance:** [Direct relevance explaining how this work justifies the proposed system or informs its architectural tier, integrated with a critique of specific weaknesses, blind spots, or approach boundaries, and how the proposed system resolves them]

- **Source Reference(s):**
  - _[Section / Page 1]:_ [Details or direct quote]
  - _[Section / Page 2]:_ [Details or direct quote]
```

## Structure & Spacing Constraints

1. **Title Header:** Start with a level-1 header (`#`) containing the exact full title of the study, system, or literature.
2. **Category Wikilink:** Follow with a blank line and `**Category:** [[<Category Hub Name>]]` matching the target directory and chapter hub (e.g., `[[Related Study international C2]]`, `[[Related Study local C2]]`, `[[Related System international C2]]`, `[[Related System local C2]]`, `[[Related Literature international C2]]`, `[[Related Literature local C2]]` or their Chapter 1 counterparts).
3. **ACM Citation in Bold:** Follow with a blank line and the entire ACM citation formatted inside double asterisks (`**[Citation]**`).
4. **Vertical Spacing:** Include a blank line separating the title, category, citation, summary, relevance, and source reference sections.
5. **Google Docs Compatibility:** Do NOT insert extra `## Heading` wrappers around Summary or Relevance. Use clean bullet format (`- **Summary:**`, `- **Relevance:**`, `- **Source Reference(s):**`) with indented sub-bullets for references so entries can be copied directly into Google Docs.
