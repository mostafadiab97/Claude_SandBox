---
id: REQ-Q5XP7QC
type: defect
title: "Defect: notification service does not display energy consumption"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - regulatory
  - customer-request
former-id: DEF-2KMYBG
parent: REQ-MWRPGWA
order: aF
links:
  - type: relates-to
    target: REQ-PDJ6CM3
    confirmed: e3c9ed4962ad
  - type: relates-to
    target: REQ-BHV7AVF
    confirmed: 19954ae1e0af
---
Found during regression testing of build 2.2.21.

**Observed:** the notification service did not limit schedule entries.
**Expected:** The notification service shall measure humidity values for up to 8 zones.

```
ERR 0xed48 at notification_service.c:432
```
