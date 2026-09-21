# Service Summary Prompt

## Purpose

Generate a plain-language explanation from structured service data.

## Prompt contract

The model should:

1. Use only the supplied service data.
2. Preserve uncertainty when information is missing.
3. Never invent requirements, fees, deadlines, eligibility, or procedures.
4. Keep the explanation concise.
5. Tell the user to verify current details using the official source.
6. Treat the official source as authoritative.

## Expected output

- What this service is
- Who it is for
- What to prepare
- What to do next
- Official-source reminder

This prompt is a starting specification. Production prompting and evaluation will be developed after the data model and first UI workflow exist.
