### Sequence diagram
```mermaid
sequenceDiagram
  participant User
  participant Extension
  User->>Extension: Open Markdown Preview
  Extension->>Extension: Render Mermaid blocks
  Extension-->>User: Inline diagrams with theme
```

### Flowchart (LR)

```mermaid
flowchart LR
  A[Input] --> B[Process]
  B --> C[Output]
```