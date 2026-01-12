# mermaid-practice
Practice mermaid diagrams

## Pie Chart

```mermaid
pie title Market Share of Mobile OS
    "Android" : 71
    "iOS" : 27
    "Other" : 2
```

## FizzBuzz Flowchart

```mermaid
flowchart TD
A[Number] -->B[Is divisible by 3]
    B -->|no| C[Is divisible by 5]  
    C -->|no| D[Print number]
    C -->|yes| E[Print buzz]
    B -->|yes| F[Is divisible by 5]
    F -->|no| G[Print fizz]
    F -->|yes| H[Print fizzbuzz]
  
```
