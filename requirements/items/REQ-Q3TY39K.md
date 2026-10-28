---
id: REQ-Q3TY39K
type: interface-requirement
title: Home dashboard logs the connection state
status: Draft
priority: Medium
former-id: IF-TK154K
parent: REQ-JXW2FTC
order: a2
links:
  - type: refines
    target: REQ-JXW2FTC
    confirmed: 39dcc2afc00b
---
The mobile app shall display access tokens at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly without user interaction
- No error entries in the device log
