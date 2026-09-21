# ManthaliOS

ManthaliOS is a digital service and opportunity platform concept for Manthali, Nepal.

The first version focuses on one practical workflow:

> Find a public service → understand it → see what to prepare → build a checklist → verify against the official source.

## Why this project exists

People often need government services without having a clear, simple explanation of:

- what the service is
- who is eligible
- which documents are required
- what steps to prepare
- where the official information comes from

ManthaliOS aims to make that information easier to understand while keeping official sources as the authority.

## MVP

1. Service directory
2. Service detail pages
3. Personal preparation checklists
4. Admin publishing and verification workflow
5. AI-assisted plain-language explanations
6. Basic product analytics

## Product principle

**AI explains. Official sources decide.**

ManthaliOS will not treat an AI-generated answer as an official government decision.

## Planned stack

The exact implementation stack will be chosen after the product and data model are documented. The project is intentionally being built in stages instead of generating a large application all at once.

## Repository structure

```text
apps/          Web application
database/      Data model and seed documentation
ai/            AI prompts and AI-specific documentation
analytics/     Product event definitions
docs/          Product and architecture documentation
tests/         Testing strategy
.github/       CI and repository automation
```

## Development sequence

```text
Product problem
    ↓
Workflow
    ↓
Database
    ↓
Service directory
    ↓
Service pages
    ↓
Checklist
    ↓
Admin workflow
    ↓
Analytics
    ↓
AI layer
    ↓
Tests + CI
```

## Status

**Stage 0 — Product foundation**

The repository is being developed incrementally as a portfolio-quality engineering project.

## License

License will be selected when the project reaches its first usable release.
