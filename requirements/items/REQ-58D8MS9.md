---
id: REQ-58D8MS9
type: defect
title: "Defect: notification service does not detect energy consumption"
status: Review
priority: Low
former-id: DEF-EAH8G9
parent: REQ-MWRPGWA
order: a6
links:
  - type: relates-to
    target: REQ-SY2XQHW
    confirmed: 2c47ff4fb672
  - type: relates-to
    target: REQ-ZHKWT4C
    confirmed: 1d6deddc1634
---
Found during regression testing of build 2.4.18.

**Observed:** the notification service did not notify firmware images.
**Expected:** The notification service shall calibrate the operating mode within 200 ms.

```
ERR 0x22de at notification_service.c:740
```
