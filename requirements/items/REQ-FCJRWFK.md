---
id: IF-2KTZGH
type: interface-requirement
title: Pairing process notifys the set point
status: Approved
priority: Medium
owner: J. Müller
tags:
  - security
  - release-1.0
parent: SYS-JKNRQ3
order: 30
links:
  - type: refines
    target: SYS-JKNRQ3
    confirmed: 2f3dabce7169
---
The pairing process shall validate audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly when the network is unavailable
- No error entries in the device log
