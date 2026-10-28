---
id: REQ-CJSXPH6
type: system-requirement
title: Notification service detects relay events
status: Approved
priority: High
owner: A. Hassan
tags:
  - customer-request
  - release-1.0
former-id: SYS-XYBVJ4
parent: REQ-QYXGSQ4
order: b1e
links:
  - type: refines
    target: REQ-QZME2VX
    confirmed: 16def0c1f947
---
The notification service shall display audit records within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly without user interaction
- No error entries in the device log
