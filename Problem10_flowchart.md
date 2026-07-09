```mermaid
flowchart TD
A([Start]) --> B[/Input raffle ticket/]
B --> C{Is number divisible by 2?}
C -- Yes --> D[/Display Positive/]
C -- No --> E[/Display Negative/]
D --> F([End])
E --> F
```
