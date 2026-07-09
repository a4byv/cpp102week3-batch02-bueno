```mermaid
flowchart TD
A --> ([START])-->B [/INPUT score 1/]
B --> C [/INPUT score 2/]
C --> D [/INPUT score 3/]
E --> F (PROCESS average = score 1 + score 2 + score 3)/3
F --> G [/DISPLAY result/]
([END])
```