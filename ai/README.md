# AI Layer

The AI layer helps users understand curated service information.

## Principle

**AI explains. Official sources decide.**

AI should summarize or simplify structured, verified information. It should not invent missing facts.

## Initial capability

The first AI feature will be a plain-language service summary.

Input:

- verified service description
- eligibility
- requirements
- preparation steps
- official-source metadata

Output:

- concise explanation
- preparation-oriented summary
- explicit reminder to check the official source

## Guardrails

- Do not fabricate requirements.
- Do not fabricate fees or deadlines.
- Do not claim government approval.
- Do not override source information.
- Clearly separate generated explanations from source data.

See [prompts/service-summary.md](prompts/service-summary.md).
