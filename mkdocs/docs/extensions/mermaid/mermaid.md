Official Mermaid documentation here:
|
https://mermaid.js.org/intro/


```mermaid
classDiagram
    class Context
    Context o-- Strategy : uses
    class Strategy {
        <<abstract>>
        +execute()
    }
    Strategy <|-- ConcreteStrategy1
```

---

# Mermaid Option 2
```mermaid
---
config:
  look: handDrawn
  theme: neutral
---
flowchart LR
  A[Start] --> B{Decision}
  B -->|Yes| C[Continue]
  B -->|No| D[Stop]
```

# Hello
Isn't this cool Cole?

'''mermaid
graph TD
    A[Enter Chart Definition] --> B(Preview)
    B --> C{decide}
    C --> D[Keep]
    C --> E[Edit Definition]
    E --> B
    D --> F[Save Image and Code]
    F --> B
'''


mermaid.initialize({
  securityLevel: 'loose',
  theme: 'forest',
});

---
# FLOWCHART LR
```mermaid
---
config:
  look: handDrawn
  theme: natural
---
flowchart LR
  A[Start] --> B{Decision}
  B -->|Yes| C[Continue]
  B -->|No| D[Stop]
```
---
# "GRAPH TD"
```mermaid
graph TD
  A[Christmas] -->|Get money| B(Go shopping)
  B --> C{Let me think}
  B --> G[/Another/]
  C ==>|One| D[Laptop]
  C -->|Two| E[iPhone]
  C -->|Three| F[fa:fa-car Car]
  subgraph "Sub-Graph Flowchart"
    C
    D
    E
    F
    G
  end
```