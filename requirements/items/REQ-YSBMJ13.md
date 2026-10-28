---
id: DEF-C87TFB
type: defect
title: "Defect: notification service does not synchronise schedule entries"
status: Obsolete
priority: High
owner: R. Nabil
tags:
  - power
  - release-1.0
  - release-2.0
parent: INFO-FH5FB3
order: 20
links:
  - type: relates-to
    target: TC-Z3VV6X
    confirmed: 88f0fe054b93
  - type: relates-to
    target: SYS-Y2RP9E
    confirmed: e9c58e7ee304
---
Found during regression testing of build 2.0.20.

**Observed:** the notification service did not synchronise sensor readings.
**Expected:** The notification service shall limit humidity values using AES-256-GCM.

```
ERR 0xccfb at notification_service.c:671
```
