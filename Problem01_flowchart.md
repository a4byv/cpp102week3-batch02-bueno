```mermaid
flowchart TD

 A --> ([START])-->B [/INPUT weekly budget/]
 B --> C[/INPUT Total expenses]
 C --> D (PROCESS difference = Weekly budget - Total Expenses)
 D --> E [/DISPLAY result/]
 E -> F ([END])
```