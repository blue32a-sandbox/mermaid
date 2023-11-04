## Special characters that break syntax

```mermaid
flowchart LR
    id1["This is the (text) in the box"]
```

### Entity codes to escape characters

```mermaid
    flowchart LR
        A["A double quote:#quot;"] --> B["A dec char:#9829;"]
        C["copy #0169;"]
        D["株 #12849;"]
        E["1 #9312;"]
```
