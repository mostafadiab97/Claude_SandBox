---
id: REQ-M999HY2
type: defect
title: "Defect: Zigbee radio does not authenticate the set point"
status: Approved
priority: High
owner: K. Tanaka
former-id: DEF-AYM03Y
parent: REQ-YW554H8
order: aA
links:
  - type: relates-to
    target: REQ-MKQRVXK
    confirmed: b68002d06e30
  - type: relates-to
    target: REQ-MA8CGH0
    confirmed: a53b6550389e
---
Found during regression testing of build 2.3.2.

**Observed:** the Zigbee radio did not notify energy consumption.
**Expected:** The Zigbee radio shall authenticate humidity values within 200 ms.

```
ERR 0x4390 at Zigbee_radio.c:502
```
