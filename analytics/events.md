# Product Events

Initial event vocabulary:

| Event | Meaning |
| --- | --- |
| service_search | User searches the service directory |
| service_view | User opens a service page |
| official_source_click | User opens an official source |
| checklist_created | User creates a checklist |
| checklist_item_completed | User completes a checklist item |
| ai_summary_requested | User requests an AI explanation |

## Event design

Events should avoid collecting unnecessary sensitive information.

Each event may eventually include:

- event name
- timestamp
- anonymous/session identifier where appropriate
- service identifier
- relevant non-sensitive metadata

The final analytics implementation will be defined alongside the application stack.
