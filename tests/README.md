# Testing Strategy

Testing will be introduced with the first application code.

## Initial test layers

### Unit tests

Test small business rules such as:

- service validation
- checklist completion
- publishing rules
- verification state transitions

### Integration tests

Test:

- service retrieval
- checklist creation
- admin publishing
- official-source relationships

### End-to-end tests

Test the core user workflow:

```text
search → service page → official source → checklist
```

### AI evaluation

AI outputs should be evaluated for:

- factual grounding
- omission of supplied requirements
- hallucination resistance
- clarity
- source-awareness
