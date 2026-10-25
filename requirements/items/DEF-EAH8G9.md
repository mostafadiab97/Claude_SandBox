---
id: DEF-EAH8G9
type: defect
title: "Defect: notification service does not detect energy consumption"
status: Review
priority: Low
parent: INFO-FH5FB3
order: 70
links:
  - type: relates-to
    target: TC-95YRV4
    confirmed: 2c47ff4fb672
  - type: relates-to
    target: SYS-HJM62M
    confirmed: 1d6deddc1634
---
Found during regression testing of build 2.4.18.

**Observed:** the notification service did not notify firmware images.
**Expected:** The notification service shall calibrate the operating mode within 200 ms.

```
ERR 0x22de at notification_service.c:740
```
