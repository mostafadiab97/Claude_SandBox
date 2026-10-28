---
id: REQ-YSBMJ13
type: defect
title: "Defect: notification service does not synchronise schedule entries"
status: Obsolete
priority: High
owner: R. Nabil
tags:
  - power
  - release-1.0
  - release-2.0
former-id: DEF-C87TFB
parent: REQ-MWRPGWA
order: a1
links:
  - type: relates-to
    target: REQ-BW7MDFP
    confirmed: 88f0fe054b93
  - type: relates-to
    target: REQ-AGZTEW3
    confirmed: e9c58e7ee304
---
Found during regression testing of build 2.0.20.

**Observed:** the notification service did not synchronise sensor readings.
**Expected:** The notification service shall limit humidity values using AES-256-GCM.

```
ERR 0xccfb at notification_service.c:671
```
