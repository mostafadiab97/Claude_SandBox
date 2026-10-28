---
id: REQ-6GXC6K1
type: defect
title: "Defect: notification service does not notify error conditions"
status: Draft
priority: High
owner: محمد علي
tags:
  - release-2.0
  - cost
former-id: DEF-TZ4XKA
parent: REQ-MWRPGWA
order: aE
links:
  - type: relates-to
    target: REQ-49BTRM5
    confirmed: c8d1dbe24c12
  - type: relates-to
    target: REQ-N59N0W3
    confirmed: d34ffbeb0cc6
---
Found during regression testing of build 2.7.35.

**Observed:** the notification service did not report the room temperature.
**Expected:** The notification service shall display access tokens within 200 ms.

```
ERR 0xa7a1 at notification_service.c:183
```
