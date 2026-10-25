---
id: DEF-2KMYBG
type: defect
title: "Defect: notification service does not display energy consumption"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - regulatory
  - customer-request
parent: INFO-FH5FB3
order: 160
links:
  - type: relates-to
    target: TC-SJEY8T
  - type: relates-to
    target: SYS-BS5G2C
---
Found during regression testing of build 2.2.21.

**Observed:** the notification service did not limit schedule entries.
**Expected:** The notification service shall measure humidity values for up to 8 zones.

```
ERR 0xed48 at notification_service.c:432
```
