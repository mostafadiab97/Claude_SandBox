---
id: DEF-AYM03Y
type: defect
title: "Defect: Zigbee radio does not authenticate the set point"
status: Approved
priority: High
owner: K. Tanaka
parent: INFO-Y69DRS
order: 110
links:
  - type: relates-to
    target: TC-3SSBJ3
  - type: relates-to
    target: SYS-PBKX7W
---
Found during regression testing of build 2.3.2.

**Observed:** the Zigbee radio did not notify energy consumption.
**Expected:** The Zigbee radio shall authenticate humidity values within 200 ms.

```
ERR 0x4390 at Zigbee_radio.c:502
```
