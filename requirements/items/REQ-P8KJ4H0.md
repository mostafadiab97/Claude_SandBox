---
id: REQ-P8KJ4H0
type: defect
title: "Defect: enclosure does not validate safety limits"
status: Review
priority: High
owner: H. Mostafa
tags:
  - i18n
  - power
  - release-2.0
former-id: DEF-HZH23E
parent: REQ-995FBPM
order: a1
links:
  - type: relates-to
    target: REQ-E48T4TZ
    confirmed: cd3775d15afe
  - type: relates-to
    target: REQ-9DQ3XFA
    confirmed: efe95468b71a
---
Found during regression testing of build 2.1.25.

**Observed:** the enclosure did not log error conditions.
**Expected:** The enclosure shall report the connection state below 0.5 W in standby.

```
ERR 0x70de at enclosure.c:193
```
