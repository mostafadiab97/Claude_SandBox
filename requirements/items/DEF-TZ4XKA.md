---
id: DEF-TZ4XKA
type: defect
title: "Defect: notification service does not notify error conditions"
status: Draft
priority: High
owner: محمد علي
tags:
  - release-2.0
  - cost
parent: INFO-FH5FB3
order: 150
links:
  - type: relates-to
    target: TC-DPYGBP
  - type: relates-to
    target: SYS-NE90V9
---
Found during regression testing of build 2.7.35.

**Observed:** the notification service did not report the room temperature.
**Expected:** The notification service shall display access tokens within 200 ms.

```
ERR 0xa7a1 at notification_service.c:183
```
