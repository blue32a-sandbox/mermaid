## Links between nodes

### A link with arrow head
```mermaid
flowchart LR
    A --> B
```

### An open link
```mermaid
flowchart LR
    A --- B
```

### Text on links
```mermaid
flowchart LR
    A -- This is the text! --- B
    C ---|This is the text!| D
```

### A link with arrow head and text
```mermaid
flowchart LR
    A -- text --> B
    C -->|text| D
```

### Dotted link
```mermaid
flowchart LR
    A -.-> B
    C -.- D
```

### Dotted link with text
```mermaid
flowchart LR
    A -. text .-> B
    C -.->|text| D
```

### Thick link
```mermaid
flowchart LR
    A ==> B
```

### Thick link with text
```mermaid
flowchart LR
    A == text ==> B
    C ==>|test| D
```

### An invisible link
```mermaid
flowchart LR
    A ~~~ B
```

### Chaining of links
```mermaid
flowchart LR
    A -- text --> B -- text2 --> C
```

```mermaid
flowchart LR
    A --> B & C --> D
```

```mermaid
flowchart TB
    A & B --> C & D
```

```mermaid
flowchart TB
    A --> C
    A --> D
    B --> C
    B --> D
```

### New arrow types
```mermaid
flowchart LR
    A --o B
    B --x C
```

### Multi directional arrows
```mermaid
flowchart LR
    A o--o B
    B <--> C
    C x--x D
```

### Minimum length of a link
```mermaid
flowchart TD
    A[Start] --> B{Is it?}
    B -->|Yes| C[OK]
    C --> D[Rethink]
    D --> B
    B ---->|No| E[End]
```

```mermaid
flowchart TD
    A[Start] --> B{Is it?}
    B -- Yes --> C[OK]
    C --> D[Rethink]
    D --> B
    B -- No ----> E[End]
```
