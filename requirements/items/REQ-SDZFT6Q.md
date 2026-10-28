---
id: REQ-SDZFT6Q
type: system-requirement
title: Device registry switchs the connection state
status: Approved
priority: High
owner: H. Mostafa
tags:
  - accessibility
  - release-1.0
former-id: SYS-E60WCX
parent: REQ-RE9ZKHF
order: b2A
links:
  - type: refines
    target: REQ-36Y9ND0
    confirmed: fbcfb8475f32
  - type: mitigates
    target: REQ-0QH3XJ3
    confirmed: be2e33598f0d
---
The device registry shall display relay events using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly within 200 ms
- No error entries in the device log
