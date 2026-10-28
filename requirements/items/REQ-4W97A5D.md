---
id: REQ-4W97A5D
type: defect
title: "Defect: heat pump driver does not display schedule entries"
status: Draft
owner: J. Müller
former-id: DEF-KT510B
parent: REQ-XJDN42Y
order: a8
links:
  - type: relates-to
    target: REQ-E45BGY8
    confirmed: d1b22deb6986
  - type: relates-to
    target: REQ-6MCMEW9
    confirmed: 5718299a4e75
---
Found during regression testing of build 2.1.35.

**Observed:** the heat pump driver did not notify the connection state.
**Expected:** The heat pump driver shall report humidity values without user interaction.

```
ERR 0x0761 at heat_pump_driver.c:839
```
