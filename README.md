# Zinātnieku nakts 2026

Šajā repozitorijā ir kods un tā lietošanas apraksts, ko lietoju savā Zinātnieku nakts aktivitātē "Dzīvā attelu analīze".

## Shemātiskais zīmejums

Aktivitātē tika lietoti divi portatīvie datori (abos Linux 26.04 operētājsistēma), kamera Logitech, parasta klaviatūra, un trīs ekrāni rezultātu rādīšanai.

```mermaid
---
config:
  layout: fixed
---
flowchart TB
    n1["Dators1"] --> n2["Dators2"] & n5["Ekrāns1"]
    n2 --> n4["Ekrāns2"] & n7["Ekrāns3"]
    n6["Klaviatūra"] --> n1
    n3["Kamera"] --> n1

    n1@{ shape: text}
    n2@{ shape: text}
    n5@{ shape: text}
    n4@{ shape: text}
    n7@{ shape: text}
    n6@{ shape: text}
    n3@{ shape: text}
     n1:::Ash
     n2:::Ash
     n5:::Ash
     n4:::Ash
     n7:::Ash
     n6:::Ash
     n3:::Ash
    classDef Ash stroke-width:1px, stroke-dasharray:none, stroke:#999999, fill:#EEEEEE, color:#000000
    style n5 fill:#BBDEFB,stroke:#2962FF
    style n4 fill:#BBDEFB,stroke:#2962FF
    style n7 fill:#BBDEFB,stroke:#2962FF
    style n6 fill:#C8E6C9,stroke:#00C853
    style n3 fill:#C8E6C9,stroke:#00C853
```
