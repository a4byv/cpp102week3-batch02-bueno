```mermaid
flowchart TD
A --> ([START])--> B [/INPUT price/]
B --> C [/INPUT quantity 1/]
C --> D [/INPUT quantity 2 /]
D --> E [/INPUT quantity 3 /]
E --> F (PROCESS sum = price + quantity 1 + quantity 2 + quantity 3)/3
F --> G [/DISPLAY result/]
([END])
```
