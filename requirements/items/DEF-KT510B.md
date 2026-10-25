---
id: DEF-KT510B
type: defect
title: "Defect: heat pump driver does not display schedule entries"
status: Draft
owner: J. Müller
parent: INFO-ZBHTYF
order: 90
links:
  - type: relates-to
    target: TC-KG8Z7C
  - type: relates-to
    target: SYS-HPD0VD
---
Found during regression testing of build 2.1.35.

**Observed:** the heat pump driver did not notify the connection state.
**Expected:** The heat pump driver shall report humidity values without user interaction.

```
ERR 0x0761 at heat_pump_driver.c:839
```
