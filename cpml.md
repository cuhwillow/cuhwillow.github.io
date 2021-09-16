---
id: 
title: CLIN.PHARM.MON.LISTS
desc: ''
sort: 4
updated: 
created: 
---

<center> ## CLINICAL PHARMACY MONITORING LISTS </center>

```note
PARENT LIST: Clinical Pharmacy Monitoring Lists 2021 - 408130421
```

```mermaid
stateDiagram-v2
[*] --> Clinical Administration
Clinical Administration --> Mangement Options
Management Options --> Utilities
Utilities --> Clinical Utilities
Clinical Utilities --> Patient List/Subset Utilities
Patient List/Subset Utilities --> Assign a My List Template
Assign a My List Template --> Enter List ID
Enter List ID --> Enter Users EMP
Enter Users EMP --> Commit & Leave
Commit & Leave --> [*]
```

