---
id: HsOwyzZrqDMBt6FGMfqDO
title: Med_in_basket
desc: ''
sort: 2
updated: 1631368572519
created: 1631368306139
---

## System Wide Settings

```note
Here are the medication related message type and definitions as set in Epic Wide Settings
```

| MESSAGE TYPE | MESSAGE TYPE DEFINITION |
| --- | --- |
| CUH Rx Non Form [40822000] | NON-FORMULARY ALERT [408220001] |
| Medication Messages [220] | MEDICATION MESSAGES [220] |
| MR Allergies Interaction Alert [510] | INTERACTION LIST MESSAGE [3410] |
| Pharmacist Review [107000002] | CUH POA PHARMACIST REVIEW [1078502] |
| RX Patient Stored Medication [1287] | RX PATIENT STORE MEDICATION [10287] |
| SC insulin rebuild [40822002] | CUH RX INSULIN REBUILD [10287] |
| Vinorelbine Oral Chemo [115000001] | CUH ONC IP VINORELBINE [10038] |

-----

### Building a new custom In Basket

```danger
Custom message types are help in a category list - E0W 30
```
```mermaid
graph LR
  A(HCD Prescribed) -- In basket message --> B((Blueteq Check))
  A --> C(Blueteq Not Required)
  B --> D[Blueteq is Required]
```


