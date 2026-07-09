```mermaid
flowchart TD
A --> ([START])--> B [/INPUT daily allowance/]
B --> C [/INPUT number of days/]
C --> D [/INPUT chore bonus /]
D --> E (PROCESS sum = daily allowance + number of days + chore bonus)
E --> F [/DISPLAY result/]
([END])
```