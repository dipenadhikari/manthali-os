# Architecture

## Initial architecture

The project will use a modular full-stack architecture.

```text
Browser
   ↓
Web application
   ↓
Application / API layer
   ↓
Database
   ↓
Structured service data
   ↓
Official source metadata

                    ↘
                     AI layer
                       ↓
                 explanations

Web application
   ↓
Analytics events
```

## Core boundaries

### Web application

Responsible for:

- service discovery
- service pages
- checklists
- admin interfaces
- user-facing AI explanations

### Database

Stores structured product data such as:

- services
- departments
- requirements
- official sources
- verification metadata
- checklist state
- analytics event records where appropriate

### AI layer

Consumes curated, structured information and produces explanatory text.

It should not become the source of truth.

### Analytics

Captures product events with data minimization in mind.

## Design principles

1. Official sources are authoritative.
2. AI is an explanation layer, not an authority layer.
3. Sensitive identity documents are outside the MVP.
4. Data models should represent provenance and verification.
5. Business workflows should be testable independently from UI code.
6. The system should be easy to replace or extend in stages.
