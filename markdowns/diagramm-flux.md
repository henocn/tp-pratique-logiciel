### Graphique de flux
```mermaid
graph TD
    A[Début] --> B{Condition}
    B -->|True| C[Action 1]
    B -->|False| D[Action 2]
    C --> E[Fin]
    D --> E
```