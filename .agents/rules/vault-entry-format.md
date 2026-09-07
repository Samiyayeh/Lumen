# Vault Entry Formatting Rule

**AI Directive:** Every time an annotated bibliography entry is saved or updated in the Obsidian vault (under `00_anotatedbibliography/`), it MUST strictly adhere to the following Markdown format with exact spacing and structure:

## Required Entry Template

```markdown
# [Paper / System / Literature Full Title]

**Category:** [[<Category Hub Name>]]

**[Full ACM Citation with bold author, year, title, publication venue, and DOI/URL link]**

- **Summary:** [1-sentence summary]

- **Relevance:** [Third-person relevance explanation]

- **Source Reference(s):**
  - *[Section / Page 1]:* [Details or direct quote]
  - *[Section / Page 2]:* [Details or direct quote]
```

## Structure & Spacing Constraints

1. **Title Header:** Start with a level-1 header (`#`) containing the exact full title of the study, system, or literature.
2. **Category Wikilink:** Follow with a blank line and `**Category:** [[<Category Hub Name>]]` matching the target directory (e.g., `[[Related Study international]]`, `[[Related Study local]]`, `[[Related System international]]`, `[[Related System local]]`, `[[Related Literature international]]`, `[[Related Literature local]]`).
3. **ACM Citation in Bold:** Follow with a blank line and the entire ACM citation formatted inside double asterisks (`**[Citation]**`).
4. **Vertical Spacing:** Include a blank line separating the title, category, citation, summary, relevance, and source reference sections.
5. **Google Docs Compatibility:** Do NOT insert extra `## Heading` wrappers around Summary or Relevance. Use clean bullet format (`- **Summary:**`, `- **Relevance:**`, `- **Source Reference(s):**`) with indented sub-bullets for references so entries can be copied directly into Google Docs.
