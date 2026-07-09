```Mermaid
flowchart TD
    A([START]) --> B[/INPUT total purchase/]
    B --|amount > 100| --> C[/DISPLAY Eligible for discount/]
    B --|amount ≤ 100|--> B[/DISPLAY Not for discount/]
    C --> D([END])
```