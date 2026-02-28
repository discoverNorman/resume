# Copilot Instructions — Resume Repository

## Project Overview

This is a single-file professional CV for Joel T. Norman, rendered as `README.md` on GitHub. The document serves as a formal Curriculum Vitae for executive and professional audiences.

## Voice & Style

- **Third-person implied** — no first-person pronouns ("I", "my"). Open bullets with action verbs.
- **Present tense** for the current role at Microsoft; **past tense** for all prior roles.
- **Declarative and factual** — state what was done and what it produced. No editorial commentary, rhetorical questions, or persuasive framing.
- **No superlatives or subjective claims** — let credentials, metrics, and outcomes speak for themselves.
- Avoid casual language, sentence fragments, and conversational tone.

## Document Structure

Maintain the following section order. Do not add, remove, or reorder sections without explicit instruction.

1. **Header** — Name, tagline, contact info
2. **Summary** — Three concise paragraphs: current focus, key achievement (Z2A), career trajectory
3. **Awards & Recognition** — Bulleted list
4. **Core Capabilities** — Three-column table
5. **Career History** — Reverse chronological roles, each with a brief description and verb-led bullet points
6. **Speaking & Thought Leadership** — Conference speaking and community subsections
7. **Education** — Single entry

## Formatting Rules

- Use `###` for role headings in Career History; format as `### Company — Title`
- Bold key achievements at the start of each bullet: `- **Created Z2A** — description…`
- Use em dashes (—) not hyphens for separators in bullet points
- Horizontal rules (`---`) between major sections only
- No dates or durations on roles — structure emphasizes outcomes, not tenure
- Keep bullet points concise; one to two sentences maximum

## Content Rules

- All metrics and numbers must be factual. Do not fabricate or inflate figures.
- The blog [agentdrivendevelopment.com](https://agentdrivendevelopment.com) should only appear in the "Agent Driven Development" experience section, not in the header or summary.
- Canton Coders is always described as "1,000+ member" community.
- Z2A scale: "hundreds of thousands of customer engineers" and "hundreds of Microsoft employees."

## Editing Guidelines

- When adding a new role, follow the existing pattern: `### Company — Title`, brief description, then verb-led bullets.
- When adding new achievements to an existing role, append to that role's bullet list.
- Do not restructure the entire document for a single content addition.
- After any edit, commit and push to origin/main.

## Git Workflow

- Repository: `discoverNorman/resume` (public)
- Branch: `main`
- Commit messages: brief, descriptive (e.g., "Add speaking engagement at Build 2026")
- Push after every committed change
