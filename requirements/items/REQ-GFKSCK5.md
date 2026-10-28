---
id: REQ-GFKSCK5
type: system-requirement
title: Zigbee radio logs error conditions
status: Draft
priority: Medium
owner: N. Kamal
former-id: SYS-X57709
parent: REQ-6R94HFM
order: b0s
links:
  - type: refines
    target: REQ-YN3XNWJ
    confirmed: 1038f4e2e9d4
---
The Zigbee radio shall validate access tokens without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly when the network is unavailable
- No error entries in the device log
