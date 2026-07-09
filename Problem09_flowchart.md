```mermaid
flowchart TD
 A --> ([START])--> B [/INPUT account balance/]
 B -->{PROCESS IF Greater than 0 Then}-->C [/DISPLAY Positive Balance/]
 B --{PROCESS IF Less than 0 Then}--> C[/DISPLAY Negative Balance/]
 C --> {PROCESS IF exactly 0} --> D [/DISPLAY Zero Balance/]
 D --> E ([END])
```





