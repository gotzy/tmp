```mermaid
flowchart LR
    A["Local Computer"] --SSH--> B
    subgraph Remote Computer
        B[("Database (MySQL)")]
    end
```
