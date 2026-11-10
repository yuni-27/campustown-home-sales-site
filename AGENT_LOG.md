# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```
## 2026-11-10: Adding city median sale prices

- **Asked:** "Read AGENT.md and docs/data_description_sheet.md first. Then replace the placeholder index.html with a page that shows the median sale price for each city, computed from data/college_town_sales.csv. Leave out sales under $10,000 and state that rule on the page."
- **Agent produced:** Replaced the placeholder with a plain HTML page that loads `data/college_town_home_sales.csv`, excludes sales under $10,000, computes each city's median in the browser, and displays the results in an accessible table.
- **Checked or changed:** The agent initially looked for the requested `AGENT.md` and `college_town_sales.csv` names and got no matching files; the repository listing caught that mismatch, so `AGENTS.md` and the documented `college_town_home_sales.csv` were used instead. Computed the city medians independently from the CSV to verify the page's source and filtering rule.
