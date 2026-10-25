---
id: SYS-W77D8P
type: system-requirement
title: Secure boot logs the connection state
status: Approved
priority: High
owner: Y. Saber
parent: INFO-0229G8
order: 1620
links:
  - type: refines
    target: STK-SZWQ0A
  - type: mitigates
    target: RSK-JW7YBZ
---
The secure boot shall notify humidity values in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly within 200 ms
- No error entries in the device log
