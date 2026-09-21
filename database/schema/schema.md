# Initial Data Model

## Entities

### Department

Represents the organization or office responsible for a service.

Suggested fields:

- id
- name
- description
- contact information
- created_at
- updated_at

### Service

Represents a public service.

Suggested fields:

- id
- department_id
- name
- slug
- summary
- eligibility
- preparation_steps
- status
- published_at
- created_at
- updated_at

### Requirement

Represents something a user may need for a service.

Suggested fields:

- id
- service_id
- name
- description
- required
- notes
- sort_order

### OfficialSource

Represents the source used to support service information.

Suggested fields:

- id
- service_id
- title
- url
- source_type
- verified_at
- verified_by
- active

### Checklist

Represents a user's preparation list for a service.

Suggested fields:

- id
- user_id
- service_id
- created_at
- updated_at

### ChecklistItem

Represents completion state for a requirement or preparation step.

Suggested fields:

- id
- checklist_id
- requirement_id
- completed
- completed_at

## Relationships

```text
Department 1 ──── * Service
Service    1 ──── * Requirement
Service    1 ──── * OfficialSource
Service    1 ──── * Checklist
Checklist  1 ──── * ChecklistItem
Requirement 1 ──── * ChecklistItem
```

The exact database technology and constraints will be selected during implementation.
