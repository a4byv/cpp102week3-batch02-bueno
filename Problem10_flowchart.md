```mermaid
flowchart TD

A --> ([START])--> B [/INPUT raffle ticket/]
B -->{PROCESS IF number is divisible by 2 Then}-->C
B --{PROCESS ELSE amount if not divisible 2 Then}--> C
C --> [/DISPLAY Even/] --> D
D --> [/DISPLAY ODD/]

D --> E ([END])
```
